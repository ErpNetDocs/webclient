# Overview

Social follows is a key aspect in Social ERP.They allow users to express interest in business objects and stay informed when something happens in their context.

Originally, following an object was treated as a single action: you either followed it or you did not. Following was implicitly understood as “this object matters to me” and was closely tied to concepts such as **favorites, notifications**, and visual indicators in the UI. As the system evolved, this simple model became limiting.<br>
Following is no longer a simple “follow/unfollow” state. Instead, each follow has a **Follow level** that indicates *why* you follow an object and *how important* it is to you.
## Why the model evolved

In practice, not all follows are the same.

Some follows exist because:
- the system automatically involved the user (mentions, assignments)
- the user explicitly chose to keep track of an object
- the object is truly important and needs quick access and higher visibility

Treating all these cases identically led to:
- important objects being mixed with incidental ones
- limited control over visibility and prioritization
- a rigid notification model that could not scale

Follow levels were introduced to address this.

## Follow levels as a unifying concept

Follow levels extend the original idea of following by adding intent and importance.

Instead of answering only "is this object followed?", the system can now also answer:
- why the object is followed
- how important it is to the user

This enables:
- automatic follows (e.g. mentions) without overstating importance
- explicit follows without cluttering high-priority views
- Favorites as a deliberate, high-interest choice

  ### Follow levels

- **Tagged**  
  You are following the object automatically, typically because you were mentioned or assigned. 

- **Following**  
  You explicitly chose to follow the object.

- **Favorite**  
  You explicitly marked the object as a favorite. Favorites are shown in the **Favorites** app.
  
There is no zero level for unfollowed objects and such objects are indicated by a **No Follow** icon.
![followicons](pictures/followicons.png)

## [Favorites](../my-apps/favorites/index.md) in the new model

In the previous model, following an object automatically implied:
- receiving notifications
- the object appearing in Favorites-related views

In the new model:
- Favorites are an explicit decision, represented by the highest follow level
- not all follows result in a Favorite
- automatic follows no longer create Favorites by default

This separation makes Favorites meaningful, limited, and intentional.

## Long-term purpose

The introduction of follow levels provides a stable foundation for:
- clearer user intent
- better prioritization of information
- consistent behavior across clients
- future extensions such as smarter notifications and filtering

Rather than adding more special cases, follow levels allow the system to grow while remaining understandable — for users and for developers alike.

## What was intentionally removed from the old model

The following behaviors from the legacy article no longer apply and were intentionally redesigned:
- Following an object does not automatically make it a Favorite
- Automatic follows do not create Favorites
- Favorites are not a side effect of notifications
- Visual tiles are no longer created for every follow

This change is deliberate and aligns the system with clearer user intent and scalable behavior.

## Getting Started

This section describes the shortest path to start using follow levels in the Web Client.

### Change follow level from the form header

1. Open the object you want to follow (e.g. a document, a case, etc.).
2. Use the **star (follow) button** in the form header.
3. Each click moves to the next state in a cycle:

   - **Not followed** → **Following**
   - **Tagged** → **Following**
   - **Following** → **Favorite**
   - **Favorite** → **Not followed** (unfollow)

Expected result:
- If you set an object to **Favorite**, it becomes available in the **Favorites** app.

### Change follow level from the context menu

The context menu follow action uses the **same behavior as the form header button** (the same click-cycle logic).

## Quick follow/unfollow actions (Ctrl/Shift + click)

In addition to the standard follow-level click cycle, you can use the following shortcuts on the **Follow (star) icon** to perform the most common actions immediately:

### Add to Favorites (skip the cycle)

- **Ctrl + Click** on the Follow (star) icon → sets the object to **Favorite** (adds it to the *Favorites* app).

Use this when you want to mark an object as a favorite without cycling through the intermediate follow levels.

### Unfollow immediately

- **Shift + Click** on the Follow (star) icon → **Unfollow** (removes the follow record).

Use this when you want to stop following the object in a single action.


