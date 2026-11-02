# Data Cleaning and Preparation

## 1. Displacement Dataset

The displacement dataset was collected from IOM DTM snapshots covering the period from April 2023 to July 2026.

The following preparation steps were performed:

- Combined multiple displacement snapshots into a structured dataset.
- Standardized state and locality names.
- Corrected inconsistent administrative P-codes.
- Removed unnecessary and unnamed columns.
- Checked for missing values and duplicate records.
- Investigated unusual values and inconsistencies.
- Created a numerical snapshot identifier to support chronological analysis.
- Calculated total displaced individuals and households for each snapshot.

## 2. Returns Dataset

The returns dataset contains 13 snapshots covering the period from June 2025 to July 2026.

The following preparation steps were performed:

- Combined the available snapshots.
- Standardized state and locality names and P-codes.
- Checked for duplicate records and missing values.
- Verified the consistency of return totals.
- Preserved unavailable household values rather than treating them as zero.
- Prepared the dataset for chronological analysis.

## 3. Data Quality Considerations

- Multiple snapshots represent repeated observations over time, not unique individuals.
- Some historical displacement records have different origin-data structures.
- Missing information was preserved where appropriate.
- Changes in reporting coverage and methodology may affect comparisons between snapshots.

## 4. Tools

Microsoft Excel was used for data cleaning, validation, organization, and preliminary calculations.
