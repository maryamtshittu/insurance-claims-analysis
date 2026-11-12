# Insurance Claims Analysis

## Project Overview

An exploratory data analysis project using Python to investigate a synthetic insurance claims dataset. The project explores claim patterns, claim amounts, resolution times and data quality, with a focus on how data can support business decision-making.

## Tools Used
- Python
- pandas
- NumPy
- Matplotlib
- Google Colab

## Methodology

- Inspected five related datasets covering claims, policies, dates, regions and product lines.
- Checked for missing values, duplicate records and invalid foreign-key references.
- Investigated inconsistencies in date fields and policy start and end dates.
- Corrected date attributes using the original date column as the source of truth.
- Combined related datasets for analysis.
- Analysed claim amounts, claim status, product lines and resolution times.
- Created visualisations to communicate patterns in the data.

## Key Findings

- The dataset contained 500 claims.
- Health claims had the highest average claim amount (£18,874.90).
- The overall average claim amount was £17,281.50, compared with a median of £13,882.76.
- 104 out of 200 policy records had an end date earlier than their start date.
- The linked dates table disagreed with the claims table's claim dates in 499 out of 500 records.

## Business Insights

The differences in average claim amounts across product lines could provide a starting point for further investigation into claim costs.

However, higher claim values do not necessarily indicate greater risk or lower profitability. Premium and exposure data would be needed to investigate this further.

The data-quality checks also highlighted the importance of validating information before using it for business reporting or decision-making.

## Limitations

- The dataset is synthetic and may not reflect real insurance operations.
- Premium and customer exposure data were unavailable.
- Some policy and date records contained inconsistencies.
- Findings identify patterns rather than establish causation.

## Project Files

- `Untitled1.ipynb` — notebook containing the Python analysis.
- `insurance_claims_analysis.csv` — combined dataset.
- `cleaned_dates.csv` — corrected date attributes.

## Future Improvements

- Investigate regional differences in claim frequency and average claim values.
- Explore trends over time using the claims table's claim dates.
- Investigate potential drivers of claim costs using additional data.
