# Menstrual Hygiene Access in Punjab

## Question
Which groups of women in Punjab have the least access to appropriate menstrual hygiene?

## Data
Punjab Multiple Indicator Cluster Survey (MICS) 2017-18, Table WS.4.1.
Women aged 15-49 who reported menstruating in the last 12 months (68,491 women).
Numbers were copied by hand from the published report into a CSV file.

## Tools
Python, pandas, matplotlib, seaborn (Kaggle Notebook)

## Key Findings
- Poorest women: 79.3% use appropriate materials. The other four wealth groups are between 89.6% and 92.3%.
- Women with no education or only preschool: 84.0%, compared with 90.9% to 91.9% for women with any education.
- Urban vs rural gap is small: 89.8% vs 88.4%.
- When appropriate materials and a private place to wash and change are counted together, the poorest women (73.9%) and women with no schooling (78.7%) are furthest below the Punjab average of 83.4%.

## Recommendation
Programs that distribute menstrual hygiene resources should reach the poorest households and women with no schooling first.

## Limitations
- Data covers Punjab by group (wealth, education, area), not by district.
- The survey is from 2017-18, so the situation may have changed.
- "Appropriate materials" is defined by MICS (see the footnote in the report).
- Women aged 15-49 are included, not only girls.

## Files
- The `.ipynb` file: the analysis notebook with charts
- `punjab_data.csv`: the data used
