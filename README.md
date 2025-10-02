# Pandas Practice Exercises

Welcome to **Pandas Practice**, a beginner-friendly repository designed to help you practice different tasks using **pandas**, the popular Python data analysis library. This repository contains exercises, examples, and guidance to help you understand pandas functionality from the basics to intermediate-level operations.

---

## 📋 Overview

This notebook covers exercises based on the **Quick Introduction to Pandas** and allows you to explore pandas functionality hands-on. Each exercise includes instructions and comments, and solutions are available in a separate notebook, but it’s recommended to try solving them yourself first.

The exercises cover:

- Creating and manipulating **Series** and **DataFrames**
- Reading and writing CSV files
- Viewing data with `head()`, `tail()`, `info()`, `describe()`
- Selecting data with `.loc` and `.iloc`
- Performing aggregation and statistical operations (`mean`, `sum`, `groupby`, `crosstab`)
- Handling missing data with `fillna()` and `.dropna()`
- Adding, modifying, and removing columns
- Shuffling data with `sample()` and resetting indexes
- Working with numeric and string data, including conversion and cleaning
- Basic plotting with **Matplotlib**

---

## 🛠 Exercises Covered

Here is a breakdown of the topics and tasks included:

1. **Pandas Basics**
   - Import pandas
   - Create Series and DataFrames
   - Combine Series into a DataFrame
   - Export DataFrame to CSV

2. **Exploring Data**
   - Check data types
   - View dataset info and summary statistics (`info()`, `describe()`)
   - Access column names and dataset length
   - View first and last rows of the DataFrame

3. **Selecting Data**
   - Use `.loc` and `.iloc` to select rows
   - Select specific columns
   - Filter rows based on conditions

4. **Aggregation & Grouping**
   - Calculate mean, sum, etc.
   - Create crosstabs
   - Group data with `groupby` and compute averages

5. **Data Cleaning**
   - Remove punctuation and extra characters from columns
   - Convert columns to numeric types
   - Handle missing data (`fillna`, `.dropna`)
   - Modify string columns permanently (e.g., lowercasing)

6. **Adding and Modifying Columns**
   - Add new columns with static or random values
   - Compute new derived columns (e.g., price per kilometer)
   - Remove columns with `.drop()`

7. **Data Sampling and Shuffling**
   - Randomly shuffle rows using `sample(frac=1)`
   - Reset indexes after shuffling
   - Convert units using lambda functions (e.g., km → miles)
   - Rename columns appropriately

8. **Visualization**
   - Basic plots using `plot()` and `hist()`
   - Handle non-numeric columns for plotting

---

## 📈 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/pandas-practice.git

2. **Navigate to the folder:**
   ```bash
   cd pandas-practice

   Open the Jupyter Notebook:
   jupyter notebook


📚 Resources
    
    Pandas Documentation
    
    10 Minutes to Pandas
    
    Stack Overflow – Pandas Questions

💡 Tips for Beginners

    Always try to solve exercises before looking at solutions.
    
    Play with different pandas functions to see how they behave.
    
    Make mistakes — it’s part of the learning process!
    
    Explore filtering, grouping, and plotting your own datasets to reinforce concepts.
