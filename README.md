# E-Commerce Sales & Logistics Dashboard
**Excel portfolio project · Sales channels · Customer ratings · Delivery performance**

An interactive workbook for exploring transaction patterns and operational measures in an e-commerce dataset.

[Dashboard workbook](dashboard/ecommerce-sales-logistics-dashboard.xlsx) · [Source workbook](dataset/dataset.xlsx) · [Interaction video](images/dashboard_interaction.mp4)

![Dashboard preview](images/dashboard_preview.png)

## Business questions

- How does order volume vary over the displayed weekly period?
- How are orders distributed across sales channels?
- Which products and customer segments account for activity?
- Where are customers located?
- How do delivery times and customer ratings vary?

## Reporting scope

The dashboard presents orders, quantity, total amount, average rating, and delivery duration alongside charts for sales and logistics exploration.

These measures need context: an average delivery time alone does not establish whether service targets were met, and sales by channel do not establish conversion rates without visitor or lead counts.

## Interaction demo

![Dashboard interaction](images/dashboard_interaction.gif)

## How to use

1. Download the dashboard workbook and open it in Excel.
2. Use the available dashboard controls to explore segments.
3. Clear selections before comparing your view with the preview.
4. Use the source workbook to inspect the underlying records.

For reuse with another dataset, check column names, formulas, PivotTable sources, and refresh behavior before replacing data. This repository does not demonstrate a live data connection or scheduled refresh service.

## Validation before business use

- Confirm whether each row represents an order or an order line; use distinct order IDs where appropriate.
- Verify currency and date coverage before presenting monetary totals.
- Reconcile dashboard totals to the source workbook.
- Check missing ratings and invalid delivery dates before interpreting averages.
- Agree operational targets before assigning healthy, warning, or critical status.

These are validation requirements, not completed test results.

## Deliverables

| Folder | Contents |
| --- | --- |
| [dashboard](dashboard/) | Excel dashboard |
| [dataset](dataset/) | Source workbook |
| [images](images/) | Screenshot, GIF, and video walkthrough |

## Project boundaries

This portfolio demonstrates interactive reporting. It does not claim measured revenue growth, inventory health, real-time alerts, or client deployment. Source provenance and verified numerical findings are the next documentation improvements.

[Repository license](LICENSE)

**Author:** Sharan Kumar Rathod
