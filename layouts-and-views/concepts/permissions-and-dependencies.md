# Layout permissions and dependencies in @@webclient

This document explains **who can edit layouts** in the ERP.net Web Client and **what layout customization depends on**.

## 1. Who can customize layouts

Layout customization is restricted by **permissions and roles**.

### Global layout manager

- A **functional permission** that grants full layout customization rights.
- Users in this group can customize **menus**, **views**, **panels**, and **forms**.
- Configured at: _Setup → Security → System Security Permissions → Layout → Global Layout Manager_
- If no groups are listed, all users can edit layouts.

📄 **Source**: [Access to Views – ERP.net Docs](https://docs.erp.net/webclient/introduction/how-to/ui-customization/access-to-views.html)

---

### Role with "Is layout admin" flag

- If the user is not a Global layout manager, but their **role** has `Is layout admin` enabled, they have advanced layout customization rights.
- Useful for allowing layout editing without full system privileges.
- Unable to access customization of a Single-record form
---

### Users without layout customization permissions

- Cannot save layout changes.
- Can only view the UI as configured for their role.

| User Status | Customize menus | Customize Module and Navigator forms | Customize Single-record forms |
|-------------|----------------------|--------|----------------|
| **Global Layout Manager** | ✅ | ✅ | ✅ Full access |
| **Role with `Is Layout Admin`** | ✅ | ✅ | ❌ Not allowed|
| **No layout permissions** | ❌ | ❌ | ❌ Not allowed |

---

## 2. What does layout customization depends on?

Layout editing depends on **two main factors**:

### 1) Security permissions

Layout changes require at least one of the following:

- Belong to **Global layout manager**
- Have a role with `Is layout admin` enabled
- Permissions are managed under: _Setup → Security → System Security Permissions → Layout_
 
📄 **Source**: [ERP.net Docs – Access to Views](https://docs.erp.net/webclient/introduction/how-to/ui-customization/access-to-views.html)

---

### 2) Role-based views

- Layouts in the web client are **role-based**, not user-based.
- A layout change applies to **all users** assigned to the same role.
- Users without layout rights cannot save customizations.

📄 **Source**: [Role-Based Views – ERP.net Support](https://support.erp.net/hc/en-us/articles/5241528675228-Role-base-views-in-the-web-client-v-22)

---

## 3. What can users with permissions customize?

Authorized users can modify:

- ✅ **Main menus**
- ✅ **Panels and forms**
- ✅ **Views** (collection of panels)
- ✅ **Navigators** (rows and columns)
- ✅ **Details views**

📄 **Source**: [ERP.net Docs – UI Customization](https://docs.erp.net/webclient/introduction/how-to/ui-customization/access-to-views.html)

---

## 4. Behavior of layout changes

### Save layouts

- "Save layout" button appears only if the user has layout permissions.
- Temporary customizations may be possible during a session but are **not persisted**.

---

### Personal vs. Role layouts

- Web client does **not** use per-user saved layouts.
- Layouts are tied to **roles**, not to individuals.
- Users in the same role share the same layout.

📄 **Source**: [ERP.net Support – Role Views](https://support.erp.net/hc/en-us/articles/5241528675228-Role-base-views-in-the-web-client-v-22)
