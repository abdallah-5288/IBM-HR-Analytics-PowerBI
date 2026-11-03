# IBM HR Analytics Dashboard

An interactive, IBM-themed Power BI report exploring **1,470 employee records** across workforce demographics, attrition, income, and employee experience.

![IBM HR Analytics dashboard preview](preview.svg)

## Project overview

The report combines **40 documented DAX measures**, **12 helper columns**, and **five report pages** with slicers, chart interactions, animated header accents, and hover feedback.

| Page | Analysis |
| --- | --- |
| Home | Overview KPIs and animated navigation |
| Workforce | Employees by department, age, education, and tenure |
| Attrition | Attrition rates by job role, department, overtime, and tenure |
| Employee Experience | Satisfaction, work-life balance, and income comparisons |
| Metric Guide | Definitions, navigation, and interpretation notes |

## Tools and methods

- **Power Query:** prepared source data and corrected numeric data types.
- **Data modeling:** created readable categories and grouped age, tenure, and other fields.
- **DAX:** calculated employee and leaver counts, attrition and retention rates, income metrics, and group comparisons.
- **Power BI:** designed interactive charts, page navigation, IBM-inspired branding, and animated SVG elements.

## Key observations

- **237** employees left and **1,233** stayed: **16.12%** sample attrition.
- Sales has **92 departures among 446 records**, a sample attrition rate of **20.63%**.
- Average monthly income is **6,502.93**, compared with a median of **4,919**.
- Average tenure is approximately **7 years**.

These are descriptive results from the IBM HR sample dataset. Attrition is calculated as employees marked Yes divided by all employees in the selected group. The source contains no hiring or exit dates, so this is **sample attrition rather than annual turnover**. Associations do not establish cause. Income is shown in the dataset's original units, without assuming a currency.

## Files

- [IBM HR Analytics - Animated.pbix](IBM%20HR%20Analytics%20-%20Animated.pbix): complete report with loaded data and measures.
- [Measures.dax](Measures.dax): readable catalogue of all 40 measures.
- [preview.svg](preview.svg): animated home-page preview.

## Open and explore

1. Download the PBIX and open it in Power BI Desktop.
2. Use the Department, Gender, and Job role slicers on each analysis page.
3. Select chart bars to filter or highlight related visuals; select again to clear.
4. Hold **Ctrl** while clicking page navigation actions in Desktop.
5. Hover over home tiles and KPI cards to see the visual feedback.

The data is embedded for viewing. To refresh on another computer, update the CSV source path in Power Query to your copy of the IBM HR Employee Attrition dataset.

## Portfolio

[View my portfolio](https://portfolio-eta-rust-27.vercel.app/#work)

IBM branding is used as the visual theme for this portfolio project. The eight-bar logo comes from the [IBM Carbon Design Language repository](https://github.com/carbon-design-system/design-language-website/blob/master/src/images/resource-cards/ibm.svg).
