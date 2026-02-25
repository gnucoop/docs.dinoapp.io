---
title: Forms List
description: View, manage, and take action on all submissions for a specific form schema in Dino.
---

# Forms List

The Forms List page displays all submissions for a selected form schema. You can view, search, filter, and manage submissions from this central location.

## Page Overview

When you navigate to a specific form, you arrive at its Forms List page. This page shows a table where each row is a single submission. The columns display the data fields defined in the form schema, such as dates, text, numbers, or status.

Above the table, you will find:
*   A **search and filter bar** to find specific submissions.
*   **Breadcrumb navigation** showing your current location.
*   An **Export** button (if you have permission) to download the list data.

On the right side of the screen, you may see floating action buttons:
*   **Add New Form** (`+`): Opens the form to create a new submission.
*   **Import Forms** (cloud upload icon): Opens a dialog to import multiple submissions from a file.

## Working with the List

### Searching and Filtering
You can narrow down the list to find specific submissions.

1.  Use the **search box** to find text across all visible columns.
2.  Click the **filter icon** to open the filter panel.
3.  Select a field from the dropdown and define your filter criteria (e.g., "Status is Completed").
4.  Click **Apply**. You can add multiple filters.
5.  To save a filter combination for later use, click **Save as preset** after applying your filters.

### Viewing and Editing a Submission
You can open any submission directly from the list.

1.  Click anywhere on a row to select it and view a summary in the side panel.
2.  To open the submission for full viewing or editing, click the **expand icon** (arrow) at the end of the row, or click the **edit icon** (pencil) in the row's action menu.

### Row Actions
Each submission row has an action menu (vertical three-dots icon). The available actions depend on your permissions and the form's configuration. Common actions include:

*   **View**: Open the submission in a read-only view.
*   **Edit**: Open the submission for editing.
*   **Duplicate**: Create a new submission using the data from this one as a starting point.
*   **Print (PDF)**: Generate and download a PDF report of the submission.
*   **Download (DOCX)**: Generate and download a Word document report of the submission.
*   **Delete**: Permanently remove the submission (requires confirmation).

!!! warning "Status-Based Actions"
    The **Edit** and **Delete** actions may be disabled for submissions that are in a certain status, based on your form's workflow rules.

### Working with Multiple Submissions
You can perform actions on several submissions at once.

1.  Select the checkboxes next to the desired rows in the list.
2.  A toolbar will appear at the bottom of the screen with available bulk actions, such as **Delete** or **Bulk Edit**.
3.  Select the desired action to apply it to all selected submissions.

## Key Workflows

### Adding a New Submission
1.  Click the **Add New Form** floating action button (`+`).
2.  A new form will open for data entry.
3.  Fill in the required fields and click **Save**.

### Exporting List Data
1.  Apply any desired filters to narrow down the list you want to export.
2.  Click the **Export** button in the search bar.
3.  Choose your preferred file format (e.g., CSV, Excel).
4.  The file will download to your computer, containing the data visible in the current list view.

### Importing Submissions
1.  Click the **Import Forms** floating action button (cloud upload icon).
2.  In the dialog, click to select or drag-and-drop a valid data file (e.g., CSV, Excel).
3.  Map the columns in your file to the fields in the Dino form.
4.  Click **Import** to create the new submissions.

!!! tip "Quick Editing"
    For some form schemas, you can edit certain fields (like checkboxes or status) directly in the list view. Click on the field in the table to change its value.