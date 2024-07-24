# Exploratory Data Analysis on Stress Levels

## Project Overview

This project focuses on analyzing stress levels based on various parameters such as gender, age group, occupation, sleep duration, BMI category, heart rate, and blood pressure. Using Python libraries like numpy, pandas, matplotlib, and seaborn, we performed comprehensive data cleaning and exploratory data analysis to uncover patterns and insights.

## Conclusion

Our analysis concluded that:
- Men aged 46-50 in Sales Representative roles with a sleep duration of 5-6 hours, Overweight BMI, heart rate between 71-75, and blood pressure around 131/86 exhibit the highest stress levels.

## Table of Contents

- [Installation](#installation)
- [Dataset](#dataset)
- [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Conclusion](#conclusion)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ujgoel/stress-level-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd stress-level-analysis
    ```
3. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Dataset

The dataset contains multiple columns including:
- `gender`
- `age group`
- `occupation`
- `sleep duration`
- `BMI category`
- `heart rate`
- `stress level`

Ensure you have the dataset in the `data` directory.

## Data Cleaning and Preprocessing

Performed meticulous data cleaning and preprocessing steps to ensure data integrity:
- Handling missing values
- Deleting unwanted columns
- Converting data types
- Standardizing categorical variables

## Exploratory Data Analysis

Conducted comprehensive exploratory data analysis using:
- **Pandas** for data manipulation
- **Numpy** for numerical operations
- **Matplotlib** and **Seaborn** for data visualization

Key findings include identifying the demographic and health-related factors contributing to high stress levels.

## Results

Developed detailed visualizations to effectively communicate the insights. The analysis revealed:
- Men aged 46-50 in Sales Representative roles with specific health metrics have the highest stress levels.

## Acknowledgements

- Thanks to the authors of the numpy, pandas, matplotlib, and seaborn libraries.
