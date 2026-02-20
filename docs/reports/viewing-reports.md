---
title: Viewing & Managing Reports
description: How to browse, filter, view, export, favourite, and delete reports in Dino.
---

# Viewing & Managing Reports

The reports list shows all reports generated from a specific template. From here you can browse, search, view, export, mark as favourite, and delete individual reports.

---

## Browsing the List

The list displays all reports for the selected template. Use the **pagination controls** to move between pages.

The list includes the following columns: user, name, status, collected since, collected until, and optionally location, organisation, project, area, and case (shown only if the relevant metric types are active).

---

## Searching and Filtering

A filter bar above the list lets you narrow down which reports are shown:

- **Project, location, area, case, organisation** — filter by specific metric values.
- **Saved filters (presets)** — save your current filter combination as a preset for quick access later. Use the preset menu in the filter bar to save, load, or delete presets.

---

## Row Actions

Each row has a set of action icons on the right. The actions available depend on your permissions:

- **View** (eye icon) — open the report in read-only mode, with export options.
- **Add to favourites** (star icon) — mark this report as a favourite.
- **Remove from favourites** (star icon, filled) — remove this report from your favourites.
- **Delete** (bin icon) — permanently delete the report. A confirmation prompt will appear.

!!! note "Permission-based actions"
    Not all actions are visible to every user. The actions shown depend on your assigned permissions.

---

## Viewing or Editing a Report

When you open a report, the full report is displayed. If the template requires metrics, you will first be taken to a metrics selection step before the report is shown.

### Selecting Metrics

Choose the metric values (for example: project, location, or organisation) and any date range filters, then click **Next** to load the report.

### Report Display

The report is displayed with its title, the date range covered, and the selected metrics. The content is rendered based on the report template's structure.

!!! note "AI-generated content"
    Some reports include AI-generated text. When this is the case, a progress indicator is shown while the content is being prepared (*"Generating report prompt X of Y"*). This happens automatically and does not require any action from you.

### Exporting the Report

From the report view, you can export the report in the following formats:

- **PDF** — click the PDF button to download a PDF version.
- **Excel (XLSX)** — click the Excel button to download a spreadsheet.
- **Word (DOCX)** — click the Word button to download a Word document.

!!! warning "No exportable content"
    If the Excel export shows a message that no exportable widget was found, the report template does not contain any table or chart data that can be exported to a spreadsheet.

---

## Troubleshooting

### "No Forms were found for this Report"

!!! warning
    The report could not load because there is no data associated with this report template. Ensure that submissions have been collected using the linked form template before generating or viewing a report.
