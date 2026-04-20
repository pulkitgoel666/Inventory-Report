README — Images folder

Purpose

    This folder contains images used in the inventory data-cleaning project: screenshots, charts, dashboards, and diagrams referenced by the main README and reports.

Contents

    screenshots/ — step-by-step Excel / Power Query screenshots (named step-01.png, step-02.png, ...).
    charts/ — exported charts used in the dashboard (bar-stock-by-category.png, low-stock-table.png).
    dashboard/ — full-dashboard exports (dashboard-overview.png, dashboard-filtered.png).
    diagrams/ — architecture and ER diagrams (er-diagram.png, workflow.png).
    thumbnails/ — smaller preview images for README display.

Filenames & Conventions

    Use descriptive, kebab-case names: category-action-detail.png (e.g., inventory-cleaning-powerquery-step1.png).
    Include resolution in filename only if needed: name-1200x800.png.
    Keep originals in .png; provide .jpg only for very large photographic assets.

How images were produced

    Charts/screenshots: Exported from Excel Online / Power BI Desktop using Export → PNG.
    Diagrams: Created with draw.io / diagrams.net and exported as PNG.
    Screenshots: Taken with system screenshot tool; annotated with simple arrows/text using Paint or Preview.

Usage

    Refer to images in markdown with relative paths, e.g.: [Image blocked: Power Query step 1]
    Use thumbnails in README and link to full-size images for detail.

Guidelines for adding images

    Add image file to the appropriate subfolder.
    Name file using kebab-case and a short descriptive label.
    Add a one-line caption to docs/README-images.md listing the new file and a short description.
    Commit images under 5 MB where possible; for larger files consider hosting externally and linking (document link in README-images.md).

Accessibility & Alt text

    For each image added, update the main README or docs with a short alt-text description. Example:
        Alt: "PivotTable showing total stock by category."

Contact / Questions

    If unsure where to place an image or how to name it, add a note in docs/README-images.md and open an issue.
