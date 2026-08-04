# 🧪 A/B Testing Analysis

![A/B Testing Dashboard](assets/ab-testing-dashboard.png)

> **Note:** Add a screenshot of your dashboard or charts in the `assets`
> folder and name it `ab-testing-dashboard.png`.

------------------------------------------------------------------------

## About the Project

A/B testing is a simple but powerful way to compare two versions of a
feature and understand which one performs better. In this project, I
analyzed the results of an A/B experiment to determine whether the new
version (Variant B) performed better than the existing version (Variant
A).

Instead of relying on assumptions, the analysis uses data and
statistical testing to support decision-making.

------------------------------------------------------------------------

## Objective

The main objective was to compare two versions of a product feature and
determine whether the observed difference in performance was
statistically significant.

------------------------------------------------------------------------

## Dataset

The dataset includes information such as:

-   User ID
-   Experiment Group (A/B)
-   Number of Visitors
-   Conversions
-   Conversion Rate
-   Revenue (if available)
-   Date

------------------------------------------------------------------------

## Tools & Technologies

-   Python
-   Pandas
-   NumPy
-   SciPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook

------------------------------------------------------------------------

## Project Workflow

1.  Loaded and explored the dataset.
2.  Cleaned missing or inconsistent values.
3.  Calculated conversion rates for both groups.
4.  Performed exploratory data analysis.
5.  Conducted a statistical hypothesis test.
6.  Compared the performance of Variant A and Variant B.
7.  Summarized the findings with business recommendations.

------------------------------------------------------------------------

## Statistical Approach

-   Null Hypothesis (H₀): There is no significant difference between
    Variant A and Variant B.
-   Alternative Hypothesis (H₁): There is a significant difference
    between the two variants.
-   Significance Level (α): 0.05

The decision was based on the p-value obtained from the statistical
test.

------------------------------------------------------------------------

## Key Insights

-   Compared conversion rates between both variants.
-   Determined whether the observed improvement was statistically
    significant.
-   Identified which version delivered better overall performance.
-   Highlighted whether the new version should be adopted or further
    tested.

------------------------------------------------------------------------

## Visualizations

-   Conversion Rate Comparison
-   Daily Conversion Trend
-   Distribution of Conversions
-   Revenue Comparison (if applicable)
-   Summary Dashboard

------------------------------------------------------------------------

## Folder Structure

    A-B-Testing/
    │
    ├── data/
    ├── notebooks/
    ├── assets/
    │   └── ab-testing-dashboard.png
    ├── README.md
    └── requirements.txt

------------------------------------------------------------------------

## Business Recommendations

-   Deploy the better-performing variant if the improvement is
    statistically significant.
-   Continue testing if the results are inconclusive.
-   Monitor user behavior after deployment to ensure consistent
    performance.
-   Run additional experiments on other product features to optimize
    user engagement.

------------------------------------------------------------------------

## Future Improvements

-   Automate A/B test reporting.
-   Build an interactive dashboard for experiment monitoring.
-   Analyze results across different customer segments.
-   Compare multiple experiment variants.

------------------------------------------------------------------------

## Author

**Bhagya Sree**

If you found this project useful, feel free to ⭐ the repository.
