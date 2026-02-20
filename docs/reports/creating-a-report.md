---
title: Creating a Report
description: How to generate a new report from a report schema in Dino, including selecting metrics and setting a date range.
---

# Creating a Report

To generate a new report, open a report schema from the Reports hub and click the **+ button** (floating circular button at the bottom-right of the page).

!!! note "Permission required"
    The add button is only visible if you have permission to create reports for this schema.

---

## Step 1 — Report Metrics

If the schema requires metrics, the first step asks you to select the metric values that this report will cover (for example: project, location, or organisation).

Fill in all required metrics and click **Next** to continue.

---

## Step 2 — Report Data

In the second step, fill in the following fields:

- **Report Name** *(required)* — a name to identify this report.
- **Collected Since** *(optional)* — the start of the date range for data included in the report.
- **Collected Until** *(optional)* — the end of the date range.

The date range is optional. If left blank, the report will include all available data for the selected metrics.

If the schema does not use metrics, you will see only the report name and date range fields directly, with no stepper.

---

## Saving the Report

Click the **Save report** button (floating circular button) to generate and save the report.

- If the report is generated successfully, a confirmation message will appear and you will be returned to the reports list.

!!! note "AI-powered reports"
    Some report schemas use AI to generate content. Creating a report from these schemas costs AI credits. The credit cost is shown on the add button tooltip before you begin. If your account does not have enough credits, a message will appear and the report cannot be created.
