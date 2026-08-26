# IMDb Top 1000 Movies — Data Analysis Project

A complete exploratory data analysis (EDA) project on the **IMDb Top 1000 Movies** dataset using Python, Pandas, NumPy, Matplotlib, and Seaborn.

The project follows an end-to-end data-analysis workflow: understanding the dataset, cleaning and preprocessing the data, investigating practical analytical scenarios, and creating visualizations to communicate insights.

## Project Objective

The objective of this project is to analyze IMDb movie data and identify meaningful patterns across:

- IMDb ratings
- Movie genres
- Release years
- Runtime
- Number of votes
- Gross revenue
- Meta scores
- Directors and cast
- Movie certificates

The analysis demonstrates practical skills in **data cleaning, exploratory data analysis, visualization, and insight generation**.

## Dataset

The project uses the **IMDb Top 1000 Movies** dataset.

The raw dataset contains movie-level information including:

- Poster_Link
- Series_Title
- Released_Year
- Certificate
- Runtime
- Genre
- IMDb_Rating
- Overview
- Meta_score
- Director
- Star1
- Star2
- Star3
- Star4
- No_of_Votes
- Gross

The original dataset is stored in the `Raw_data/` directory. The cleaned dataset produced during the analysis is stored separately in `cleaned_data/` so that the original raw data remains unchanged.

## Project Structure

```text
IMDb-Data-Analysis/
│
├── README.md
│
├── Raw_data/
│   └── imdb_top_1000.csv
│
├── cleaned_data/
│   └── imdb_cleaned.csv
│
└── notebook/
    ├── 1_Understanding.ipynb
    ├── 2_cleaning.ipynb
    ├── 3_Realtime_Scenario.ipynb
    └── 4_dataVisualization.ipynb
```

### Directory Description

| Directory/File | Purpose |
|---|---|
| `Raw_data/` | Stores the original, unmodified IMDb dataset |
| `cleaned_data/` | Stores the cleaned dataset generated during preprocessing |
| `notebook/` | Contains the Jupyter notebooks covering the analysis workflow |
| `README.md` | Project documentation and overview |

## Analysis Workflow

### 1. Understanding the Dataset

The first stage focuses on understanding the structure and characteristics of the dataset.

Activities include:

- Loading the dataset using Pandas
- Inspecting rows and columns
- Checking data types
- Reviewing summary statistics
- Identifying unique values
- Examining missing values
- Understanding the distribution of important variables

Notebook: `notebook/1_Understanding.ipynb`

### 2. Data Cleaning

The raw dataset contains missing and inconsistent values that need to be addressed before analysis.

Cleaning activities include:

- Identifying missing values using `isnull()`
- Handling missing values
- Checking for duplicate records
- Converting columns into appropriate data types
- Cleaning numerical fields such as `Runtime`, `Released_Year`, and `Gross`
- Preparing a cleaned dataset for analysis

The cleaned dataset is saved as `cleaned_data/imdb_cleaned.csv` while the original raw dataset remains unchanged.

Notebook: `notebook/2_cleaning.ipynb`

### 3. Real-World Analysis Scenarios

The project applies the cleaned dataset to practical analytical questions, such as:

- Which genres have the highest average IMDb ratings?
- How have movie releases changed over the years?
- Which directors have the highest number of movies in the dataset?
- Is there a relationship between movie revenue and IMDb rating?
- How are IMDb ratings distributed?
- Which movie certificates are most common?
- What patterns can be observed across ratings, votes, revenue, and other movie attributes?

Notebook: `notebook/3_Realtime_Scenario.ipynb`

### 4. Data Visualization

Visualizations were created using Matplotlib and Seaborn to communicate analytical findings clearly.

Examples include:

- Histogram of IMDb ratings
- Distribution of movie certificates
- Average IMDb rating by genre
- Movie releases over the years
- Gross revenue vs. IMDb rating
- Top directors by number of movies

Notebook: `notebook/4_dataVisualization.ipynb`

## Key Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

## Skills Demonstrated

### Data Analysis

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Missing-value analysis
- Duplicate detection
- Data-type conversion
- Descriptive statistics
- Trend and relationship analysis

### Python

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Data Visualization

- Histograms
- Bar charts
- Line charts
- Scatter plots
- Distribution analysis

### Analytical Skills

- Problem formulation
- Pattern identification
- Trend analysis
- Data-driven insight generation
- Communicating findings through visualizations

## Example Analysis

One of the analyses investigates the relationship between **Gross Revenue** and **IMDb Rating** using a scatter plot. This helps assess whether higher-rated movies in the dataset tend to be associated with higher box-office revenue.

Another analysis compares **average IMDb ratings across genres**, allowing genres to be evaluated based on their observed rating performance in the dataset.

## Project Outcome

This project demonstrates an end-to-end data-analysis workflow starting from a raw dataset and progressing through:

**Raw Data → Data Understanding → Data Cleaning → Exploratory Analysis → Visualization → Insights**

The project was developed as a practical exercise in applying Python-based data analysis techniques to a real-world dataset.

## Tools Used

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive analysis |
| VS Code | Development environment |
| GitHub | Project version control and portfolio |

## Author

**Sayali Chopade**

B.Tech Manufacturing Engineering | COEP Technological University

Interested in **Data Analytics, Business Analytics, Supply Chain, and Business/Strategy roles**.

*This project was created to demonstrate practical data-analysis skills using Python and publicly available IMDb movie data.*
