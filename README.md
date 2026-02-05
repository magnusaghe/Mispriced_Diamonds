# Mispriced_Diamonds - Exploratory Data Analysis
This is an exploratory analysis of diamond pricing data to identify patterns in pricing, outliers, relationships, and potential mispricing across clarity categories.

## Setup Instructions
1. Clone the repository
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn
3. Run the Jupyter notebook

## Assumptions
- Identical diamonds may legitimately exist
- Outliers may represent valid but rare observations
- Outlier filtering is used for interpretability, not deletion

## Aggregated Views
- Summary statistics by clarity
- Outlier impact analysis
- Filtered correlation and pricing relationships

## Understanding Diamond Clarity
Diamond clarity refers to the presence of internal inclusions and surface blemishes, graded under 10× magnification. Clarity grades range from Flawless (FL) to Included (I), with higher grades indicating fewer imperfections.

- For reference, clarity categories in this dataset follow standard industry definitions commonly used by organizations such as GIA:

- IF (Internally Flawless): No internal inclusions; only minor surface blemishes

- VVS1 / VVS2: Very, very slight inclusions, extremely difficult to detect

- VS1 / VS2: Minor inclusions difficult to detect under magnification

- SI1 / SI2: Noticeable inclusions under magnification

- I1: Inclusions visible to the naked eye

These definitions provide domain context for interpreting price dispersion and identifying potential mispricing patterns.
