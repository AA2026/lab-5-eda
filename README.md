# BU RISE Data Science Practicum Lab 5: Explanatory Data Analysis

## Purpose

The purpose of the repository is to give an overview of basic functions using a DataFrame which was imported from a CSV file through pandas. The CSV file contains student data, including their age, gpa, major, etc. The Jupyter notebook (eda.ipynb) shows various functions that can be applied to DataFrames including count, mean, median, variance, standard deviation, minimum, and maximum. The notebook also shows how histograms and scatterplots can be created using both pandas and seaborn. Finally, the major column in the dataset was cleaned to make the text more readable and easier to compare.

Lab tasks and observations are listed in ```eda.ipynb```


## Environment Setup

1. Clone the repository

```bash
git clone https://github.com/AA2026/lab-5-eda.git
```

2. Run the commands (wait for the first command to finish before continuing to the second one):

```bash
conda create -n lab_5 --file environment.txt -y
conda activate lab_5
```

## Dataset Description

The dataset lists different students and gives the following information for each students (some of the fields may be null/NaN for some students):

- student_id
- age
- gpa
- gender
- major
- year

The following statistics were calculated for the age and gpa categories (in Task C):

- count
- mean
- median
- variance
- standard deviation
- min
- max
