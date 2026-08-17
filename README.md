# Netflix Movies & TV Shows — Exploratory Data Analysis

## Pluto Academy AI & Machine Learning Internship — Project 01

This project performs an Exploratory Data Analysis (EDA) of the **Netflix Movies & TV Shows dataset**. The objective is to understand the dataset, clean the data, identify important patterns and trends, create meaningful visualizations, and generate data-driven insights.

## Project Objective

The main objectives of this project are:

* Load and inspect the Netflix dataset.
* Identify and handle missing values.
* Check and handle duplicate records.
* Perform exploratory data analysis using Pandas and NumPy.
* Answer five analytical questions about the dataset.
* Create different types of visualizations to identify patterns and trends.
* Generate five data-backed insights.
* Identify the most surprising finding from the analysis.

## Dataset

**Dataset:** Netflix Movies & TV Shows

The dataset contains information about movies and TV shows available on Netflix, including:

* Show ID
* Type
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Listed In
* Description

**Dataset Source:** Kaggle — Netflix Movies and TV Shows Dataset

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* Jupyter Notebook

## Project Workflow

### 1. Data Loading & Inspection

The dataset was loaded using Pandas and inspected for:

* Number of rows and columns
* Column names
* Data types
* Missing values
* Duplicate records

### 2. Data Cleaning

The following cleaning operations were performed:

* Missing values in `director`, `country`, `cast`, `rating`, and `duration` were replaced with `"Unknown"`.
* The `date_added` column was converted into datetime format.
* Duplicate records were checked.
* The original dataset was preserved by creating a separate cleaned DataFrame.

The cleaning decisions were made to preserve as much of the original data as possible while preparing it for analysis.

### 3. Exploratory Data Analysis

Five questions were investigated:

1. What is the distribution of Movies and TV Shows?
2. Which countries have the highest number of Netflix titles?
3. How has the number of Netflix titles added changed over the years?
4. What are the most common content ratings on Netflix?
5. How is Netflix content distributed across release years?

## Visualizations

The project contains the six visualization types required for the analysis:

1. **Bar Chart** — Movies vs TV Shows
2. **Line Chart** — Netflix titles added by year
3. **Histogram** — Distribution of titles by release year
4. **Scatter Plot** — Release year vs year added
5. **Pie Chart** — Percentage distribution of Movies and TV Shows
6. **Heatmap** — Content type across release decades

All visualizations include appropriate titles and axis labels.

## Key Insights

The analysis produced the following major findings:

1. Movies represent the larger share of titles in the Netflix dataset compared with TV Shows.
2. The United States is among the leading countries contributing titles to the Netflix catalog.
3. The number of titles added to Netflix increased considerably during the later years represented in the dataset.
4. Mature-audience ratings such as TV-MA are highly represented in the Netflix catalog.
5. The dataset contains a strong concentration of relatively recent content.

## Most Surprising Finding

The most surprising finding was the strong concentration of Netflix titles in recent release years. The analysis indicates that a significant portion of the catalog consists of relatively recent content. The yearly addition analysis also shows substantial growth in Netflix's catalog during the later years represented in the dataset.

## Conclusion

This exploratory data analysis provided useful insights into the Netflix content catalog. The analysis examined content types, countries, ratings, release years, and yearly additions to the platform. Data cleaning and visualization helped identify important patterns and trends within the dataset. Overall, the project demonstrates how Python-based exploratory data analysis can be used to transform a raw dataset into meaningful and understandable insights.

## Project Structure

```text
Netflix-EDA-Project/
│
├── Netflix_EDA_Project_01.ipynb
├── README.md
└── netflix_titles.csv
```

## How to Run the Project

### Using Google Colab

1. Open the project notebook in Google Colab.
2. Upload `netflix_titles.csv`.
3. Run the notebook from the beginning.
4. Execute all cells in order.
5. Review the generated outputs and visualizations.

### Using Jupyter Notebook

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

Then open:

```text
Netflix_EDA_Project_01.ipynb
```

and run the cells sequentially.

## Project Deliverables

* Public GitHub repository
* Python/Jupyter Notebook (`.ipynb`)
* README documentation
* Google Colab notebook

## Internship

**Program:** Pluto Academy AI & Machine Learning Internship
**Project:** Project 01 — Exploratory Data Analysis & Insights Report

## Author

**Dipal Patil**

B.Tech — Computer Science & Engineering (Artificial Intelligence & Machine Learning)

---

*This project was developed as part of the Pluto Academy AI & Machine Learning Internship Program.*
