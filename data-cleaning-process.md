# Power Query – Data Cleaning & Transformation

## Objective

Prepare the raw CPI dataset for structured analysis in Excel.

## Workflow

1. Import the raw CPI dataset into Power Query.
2. Review the source structure and identify the required fields.
3. Clean and standardize the month/year fields.
4. Prepare the sector and CPI category fields.
5. Unpivot the detailed CPI category columns to create a normalized analytical table.
6. Retain the original CPI category in `Original Classification`.
7. Create broader analytical buckets in `Classified as`.
8. Create a numeric month field for chronological analysis.
9. Validate the transformed table.
10. Load the result into Excel for PivotTable analysis and visualization.

## Output

The final transformed structure contains:

- Sector
- Year
- Month
- Original Classification
- CPI Value
- Classified as
- Month Number

The detailed Power Query screenshots and methodology are available in the project documentation PDF.
