---
title: Managing Metrics
description: How to browse, create, edit, view, import, and delete metric entries (areas, cases, locations, organisations, projects) in Dino.
---

# Managing Metrics

Each metric type — Thematic Areas, Cases, Locations, Projects, and Organisations — has a management page with the same structure: a searchable list, row actions to view, edit, or delete individual entries, and buttons to add or import entries in bulk.

!!! note "Permission required"
    Managing metric values requires specific permissions. If you cannot see the create, edit, or delete options, contact your administrator.

---

## Browsing the List

The list shows all entries for the selected metric type. Use the filter bar above the list to search and narrow down results.

Click the **Export** button in the filter bar to download the current list as a file.

Click a row to select or expand it.

---

## Row Actions

Each row has a set of action icons on the right:

- **View** (eye icon) — open the entry in read-only mode.
- **Edit** (pencil icon) — open the entry for editing.
- **Delete** (bin icon) — open a confirmation dialog before permanently deleting the entry.
- **Print** (printer icon) — generate a card PDF for this entry. *(Cases only.)*

---

## Bulk Delete

Select multiple entries using the checkboxes on their rows, then use the bulk delete action that appears in the toolbar. A confirmation dialog will appear before any entries are deleted.

---

## Creating a New Entry

Click the **+ button** (floating circular button at the bottom-right) to open the editor dialog for a new entry.

---

## Importing Entries

Click the **Import button** (cloud upload icon, floating button at the bottom-right) to bulk-import entries from a file.

1. Click **Choose file** and select an `.xls`, `.xlsx`, or `.csv` file from your device.
2. Optionally tick **Don't import metrics if name exists** to skip any rows whose name already exists in the system.
3. Click **Apply** to start the import.
4. Click **Close** when done.

---

## The Entry Editor

When you create or edit an entry, a dialog opens with the fields for that metric type. In view mode, the fields are read-only.

### Common fields (all metric types)

- **Name** *(required)* — the display name of this entry. Must be unique within the metric type.
- **Parent** — an optional parent entry that this entry belongs to, enabling hierarchical groupings (for example, a sub-location within a location). Start typing to search for and select the parent.

### Thematic Areas

| Field | Notes |
|---|---|
| Name | Required |
| Parent Area | Optional, autocomplete |

### Cases

| Field | Notes |
|---|---|
| Name | Required |
| Code | Read-only |
| Image | Upload a JPG/PNG (max 1 MB) or take a photo using the camera tab |
| Parent Case | Optional, autocomplete |

### Locations

| Field | Notes |
|---|---|
| Name | Required |
| Coordinates | Optional |
| Parent Location | Optional, autocomplete |

### Organisations

| Field | Notes |
|---|---|
| Name | Required |
| Logo Path | Optional |
| Website URL | Optional |
| Parent Organisation | Optional, autocomplete |

### Projects

| Field | Notes |
|---|---|
| Name | Required |
| Code | Read-only |
| Sectors of Intervention | Optional |
| Donors | Optional |
| Start Date | Optional, date picker |
| End Date | Optional, date picker |
| Parent Project | Optional, autocomplete |

### Additional Attributes

Below the main fields, an **Additional attributes** section lets you attach any number of custom key-value pairs to an entry. Click **+** to add a new attribute and **−** to remove one. These are hidden in view mode if no attributes have been set.

### Saving

Click **Save** to save the entry. A confirmation message will appear briefly.

!!! warning "Oops! Something went wrong while saving the Metric."
    If an error appears when saving, check that all required fields are filled in and that the name is not already used by another entry of the same type. If the problem persists, contact your administrator.

!!! warning "Offline image upload"
    If you are offline when saving an entry that includes an image, the image will not be uploaded. Save the image again once you are back online.

---

## Deleting an Entry

Click the **Delete** row action or use the bulk delete action. A confirmation dialog will ask you to confirm before the entry is permanently removed.
