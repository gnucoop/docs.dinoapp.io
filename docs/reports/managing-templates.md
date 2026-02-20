---
title: Managing Report Templates
description: How to create and edit report templates (schemas) in Dino, including fields, required metrics, XLS import, and the live preview.
---

# Managing Report Templates

Report templates define the structure and layout of generated reports. Administrators and users with the appropriate permissions can create new templates and edit existing ones.

!!! note "Permission required"
    Managing report templates requires specific permissions. If you cannot see the create or edit options, contact your administrator.

---

## Accessing Template Management

From the Reports hub, navigate to the template you want to edit and click its **edit** action, or use the navigation to reach the **Create** option for a new template.

---

## Template Settings

Fill in the following fields to configure the template:

- **Report Name** — a unique internal identifier for this template. An error will appear if the name is already in use.
- **Report Label** — the display name shown to users in the interface.
- **Icon Set** — choose between *Default* (standard icons) and *Humanitarian* (icons specific to humanitarian contexts).
- **Icon Identifier** — type to search for and select the icon that represents this template.
- **Required Metrics** — select one or more metric types (such as project, location, or organisation) that must be provided when generating a report from this template.

---

## Associated Form Schemas

Below the settings fields, a read-only section lists the form schemas linked to this report template. These are set by the system and cannot be changed from this screen.

---

## Report Preview

A live preview of the report layout is displayed on the right side of the screen. The preview updates as you make changes to the template structure.

---

## Importing a Report Structure

If you have an existing report definition in XLS format, you can import it instead of building the structure manually.

1. Click the **Import** button.
2. Select your XLS file from your device.
3. Review the imported structure in the editor.
4. Make any adjustments needed, then save.

---

## Saving the Template

Click **Save** to save the template. A confirmation message will appear briefly at the bottom of the screen. After saving, you will be returned to the Reports hub.

!!! warning "Oops! Something went wrong saving the Report"
    If an error message appears when saving, check that the **Report Name** and **Report Label** fields are filled in and that the Report Name is not already used by another template. If the problem persists, contact your administrator.
