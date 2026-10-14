# Tourist Footfall Trend Analysis

## Project Overview

**Tourist Footfall Trend Analysis** is a Project-Based Learning (PBL) mini-project for the course **Data Analytics Using Python**. It uses the Indian Tourist Attraction Dataset to explore patterns in recorded tourist-attraction visit records and communicate those patterns through data cleaning, exploratory data analysis (EDA), summary tables, and visualizations.

The project examines how records are distributed across years, months, seasons, states, and attraction categories. It also explores selected attributes such as user ratings, recommendation scores, entry fees, and weather conditions.

> **Interpretation note:** Counts in this project describe records in the supplied dataset. They should not be presented as official nationwide tourist-footfall totals unless the dataset source explicitly establishes that meaning.

## Academic Details

- **University:** ITM University, Gwalior
- **Programme:** B.Tech. CSE (Artificial Intelligence & Machine Learning)
- **Semester / Section:** III / E
- **Course:** Data Analytics Using Python
- **Course Code:** CSL0312
- **Faculty Mentor:** Dr. Sanjay Jain

### Project Team

| Role | Name | Roll Number |
|---|---|---|
| Team Leader | Akshat Srivastava | BETN1AI25124 |
| Team Member | Jay Yadav | BETN1AI25139 |
| Team Member | Krish Kumar | BETN1AI25134 |

## Dataset

- **Dataset:** Indian Tourist Attraction Dataset
- **Dataset author:** Dakshineswar M
- **Source:** [Kaggle — Indian Tourist Attraction Dataset](https://www.kaggle.com/datasets/dakshineswarm/indian-tourist-attraction-dataset)
- **Original CSV:** `indian_tourist_places_dataset.csv`
- **Cleaned CSV:** `cleaned_indian_tourist_places_dataset (2).csv`

The supplied cleaned CSV used for the report contains **13,000 rows and 34 columns**. In that file, the quality checks found **0 missing cells** and **0 exact duplicate rows**. These figures should be checked again if the notebook is rerun and a new cleaned file is exported.

## Objectives

- Inspect the dataset structure, columns, data types, missing values, and duplicate records.
- Prepare the data for consistent analysis by cleaning and transforming selected fields.
- Explore record distributions by year, month, season, state, and tourist-attraction category.
- Summarize selected numeric attributes using descriptive statistics.
- Visualize tourism-related patterns and compare selected variables.
- Present findings accurately, noting that dataset-level patterns are not automatically official measures of total tourist footfall.

## Tools and Libraries

- **Python** — analysis workflow
- **Jupyter Notebook** — interactive execution
- **Pandas** — data cleaning and tabular analysis
- **NumPy** — numerical operations
- **Matplotlib and Seaborn** — visualizations, where used
- **Scikit-learn preprocessing utilities** — encoding or scaling, where used

## Workflow

1. Load the original tourist-attraction CSV.
2. Inspect rows, columns, data types, missing values, and duplicate rows.
3. Clean and standardize relevant values, handle missing data, and parse date fields.
4. Apply the preprocessing steps documented in the notebook, such as selected outlier capping, encoding, and scaling.
5. Explore yearly, monthly, seasonal, state-wise, and category-wise record distributions.
6. Summarize relevant numeric attributes and create charts.
7. Validate the final cleaned dataset and ensure the notebook, CSV, charts, and report use the same data version.

## Project Files

Keep the files together in one project folder. For example:

```text
Tourist-Footfall-Trend-Analysis/
├── README.md
├── Tourist_Footfall_Trend_Analysis_PBL.ipynb
├── indian_tourist_places_dataset.csv
├── cleaned_indian_tourist_places_dataset (2).csv
└── Tourist_Footfall_Trend_Analysis_Cleaned_Dataset_Report.docx
```

Your actual filenames may differ; update this list to match the final folder before submission.

## How to Run

1. Install Python and Jupyter Notebook, or open the notebook in Google Colab.
2. Put the required CSV file(s) in the same folder as the notebook, or update the file paths in the notebook.
3. Install any missing packages:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

4. Open `Tourist_Footfall_Trend_Analysis_PBL.ipynb`.
5. Select the correct Python kernel/runtime.
6. Run the notebook cells in order, from top to bottom.
7. Review the generated tables, charts, and cleaned CSV.
8. Confirm that the CSV export occurs **after all intended cleaning, encoding, scaling, and data-type conversions**.
9. Recheck the output dimensions, missing values, duplicates, and report figures.

### Reproducibility Check

Before final submission, make sure the notebook exports the final dataset only after all preprocessing steps. The supplied cleaned CSV used for the report already contains the final transformations; if a notebook run produces different results, verify the pipeline and update the report accordingly. A score scaled to 0–1 should not be described as the original sentiment polarity without supporting documentation.

## Analysis Scope

The project focuses on descriptive analysis of:

- Year-wise and month-wise record counts
- Seasonal distribution
- State-wise distribution
- Tourist-attraction categories
- User ratings and recommendation scores
- Entry fees and free-entry indicators
- Weather-related attributes, including temperature, humidity, and rainfall
- Relationships among selected numeric variables

## Limitations

- Findings depend on the supplied dataset and the final preprocessing pipeline.
- Record counts should not be treated as official total visitor counts without confirmation from the source.
- Correlation or association does not prove causation.
- Outlier capping may change genuine extreme observations, so the method should be explained and justified.
- The cleaned CSV, notebook output, and report must be kept synchronized.

## Deliverables

- Jupyter Notebook (`.ipynb`)
- Original dataset (`.csv`)
- Cleaned dataset (`.csv`)
- PBL report (`.docx`)
- Project README (`.md`)

## Reference

Dakshineswar M, *Indian Tourist Attraction Dataset*, Kaggle:  
https://www.kaggle.com/datasets/dakshineswarm/indian-tourist-attraction-dataset

## Academic Integrity

Review and understand the code, analysis, charts, and conclusions before submission. Disclose any AI assistance in accordance with the course instructor's requirements, and verify all final results against the notebook and dataset.
