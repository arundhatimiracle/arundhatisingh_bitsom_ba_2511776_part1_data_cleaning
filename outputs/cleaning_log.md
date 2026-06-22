# Cleaning Log

## 1. Issues Found

During the review of the dataset, a few data quality issues were identified:

* Duplicate order records were present.
* Some date values were not in a valid format.
* A few text fields contained inconsistent formatting.
* Missing or incomplete values were found in certain columns.
* Some records required additional validation based on business rules.

## 2. Cleaning Actions Performed

The following cleaning steps were carried out:

* Removed duplicate records from the dataset.
* Standardized text fields such as customer names, categories, and segments.
* Checked date columns and flagged invalid date values.
* Created calculated fields required for analysis.
* Reviewed missing values and retained records where sufficient information was available.

## 3. Business Rules Applied

The following business rules were used during data preparation:

* Shipping delay was calculated using order and shipment dates.
* Sales and profit related calculated fields were created for reporting.
* Category and segment values were standardized to maintain consistency.
* Data quality flags were used to identify records requiring review.

## 4. Assumptions Made

* Blank cells were treated as missing values.
* Invalid dates were flagged instead of being manually corrected.
* Existing business categories and customer segments were considered valid after standardization.

## 5. Records Removed

* Duplicate records identified during the cleaning process were removed from the final dataset.

## 6. Records Flagged

* Records containing invalid dates were flagged for further review.
* Any record failing validation checks was marked using the data quality flag.

## 7. Limitations

* Some data quality issues may require domain knowledge for complete correction.
* Flagged records were not manually altered to avoid introducing assumptions into the dataset.
* Results depend on the quality of the original source data provided.
