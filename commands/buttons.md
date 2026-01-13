# Buttons
Buttons are available everywhere in the platform - on the top ribbon, inside a panel, in the navigation panel...They are accompanied with a text (can be hidden) and a hint to indicate what would happen when pressed.
In our platform we chose icons and toggle switches to serve as buttons. In this section we will explain the most common buttons you see on the top ribbon of a record or navigator.

## Save
Used when you want to store your changes and continue working in the same form.

### Steps
1. Open a record (new or existing).
2. Make your changes.
3. Click **Save**.

### Result
- The changes are saved to the database.
- The form remains open.
- If there are **no changes**, **Save** is disabled.
- If **validation fails**, the save is aborted and validation messages are shown.

---

## Save and Reload / Save and Close 

These options appears in Subforms (when a record is opened through another form)

- Use **Save & Reload** when you want to save your changes and refresh the form data and stay in the form. This will save and reload the form.
- Use **Save & Close** when you want to save your changes and exit the form. This will save data and close the form returning you to the starting form (e.g. another form or the navigator).

> **Note**  
> When a form is opened as a **sub-form (popup)**, **Save & Close** is the primary action.

---

## Close (X)

Use **Close (X)** when you want to exit the form without explicitly saving.

### Case 1: No unsaved changes
1. Click **X**.
2. The form closes immediately.

### Case 2: Unsaved changes exist
1. Click **X**.
2. A confirmation dialog appears with the following options:
   - **Always save automatically when closing** (checkbox)
   - **Save changes**
   - **Discard changes**
   - **Cancel**

#### Available actions
- **Save changes**  
  Saves the changes and then closes the form.

- **Discard changes**  
  Closes the form **without saving** the changes.

- **Cancel**  
  Keeps the form open so you can continue editing.

### Always save automatically when closing
- When enabled, this option is saved as a user preference.
- Closing the form with **X** will automatically save changes without showing the dialog.

---

## Discard

Use **Discard** when you want to leave the form without saving your changes.

### Steps
1. Click **Discard** (or choose **Discard changes** from the Close dialog).
2. The form closes and all unsaved changes are lost.

---

## Important Notes

- The unsaved changes dialog appears **only when closing the form using the X button**.
- If you refresh the browser page or navigate away from the form, the browser’s default confirmation dialog may appear instead. This behavior is controlled by the browser and cannot be customized.

## Close

## Toggle switch

## Edit

## New

## Discard

## Save layout
