#  Pandas for Data Science

> A comprehensive repository covering the fundamentals of **Pandas** for Data Science through well-structured Jupyter notebooks, descriptive notes, and hands-on projects.

---

## 📖 About

Pandas is one of the most widely used Python libraries for data manipulation and analysis.

This repository documents my learning journey while building a strong foundation in Pandas through structured notebooks, descriptive notes, and practical projects using real-world datasets.

The content progresses from the basics of Series and DataFrames to more advanced topics such as GroupBy, Pivot Tables, and DataFrame operations.

---

# 🛠 Installation

### Clone the repository

```bash
git clone https://github.com/SVyeole08/Pandas-for-DataScience.git
```

### Navigate into the project

```bash
cd Pandas-for-DataScience
```

### Install dependencies

```bash
pip install pandas numpy notebook
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📂 Repository Structure

```text
Pandas-for-DataScience
│
├── 📒 1) Series.ipynb
├── 📒 2) DataFrames.ipynb
├── 📒 3) MissingData.ipynb
├── 📒 4) Merging, Joining, Concatenation.ipynb
├── 📒 5) GroupByAggregation.ipynb
├── 📒 6) PivotTables.ipynb
├── 📒 7) Operations.ipynb
│
└── 📁 Projects
    ├── Countries.ipynb
    └── FeatureExtraction.ipynb
```

---

# 📚 Topics Covered

| Topic                | Status |
| -------------------- | :----: |
| Series               |   ✅   |
| DataFrames           |   ✅   |
| Indexing & Selection |   ✅   |
| Missing Data         |   ✅   |
| Merge                |   ✅   |
| Join                 |   ✅   |
| Concatenation        |   ✅   |
| GroupBy              |   ✅   |
| Aggregation          |   ✅   |
| Pivot Tables         |   ✅   |
| Crosstab             |   ✅   |
| DataFrame Operations |   ✅   |

---

# 📂 Projects

## 🌍 Countries Analysis

I analyzed a dataset covering 194 countries. I used this to practice going from raw, sparsely populated data to actual answers

**What this involved:**

- Reading in the CSV and getting a first look at structure and data types
- Filtering to isolate specific countries or groups based on conditions
- Sorting to rank countries by different metrics
- String operations to clean and standardize text fields (country names, regions, etc.)
- Missing value detection to figure out which columns were actually usable
- Value counts to see how categorical data was distributed
- Statistical queries to answer specific questions about the dataset (min/max, averages, comparisons across countries)

---

## 🎌 Anime Feature Extraction

I worked with a messy anime dataset where most of the useful information was buried in unstructured text fields - things like combined date ranges, inconsistent genre strings, and free-text columns that needed to be broken apart before they were actually usable for analysis.

I focused on building parsing logic that actually held up against the inconsistencies in the raw data - mismatched date formats, missing values disguised as placeholder text, and fields that packed multiple pieces of information into one column.

**What this involved:**

- Data cleaning to handle inconsistent formatting and placeholder/missing values
- Parsing and processing date fields (including split or combined date ranges)
- Feature engineering - extracting new, usable columns out of raw text
- Custom parsing functions for handling irregular string patterns
- `apply()` for row-wise transformations
- String manipulation to clean and standardize text fields

---

## 🏥 Healthcare Data Analysis

I took a healthcare dataset and ran it through a full cleaning and exploration pipeline.

The goal wasn't just to "clean data" as an abstract exercise. It was to practice the actual judgment calls that come up: which missing values are safe to drop vs. impute, how to catch duplicate patient records that aren't exact duplicates, how to engineer useful features out of raw dates and strings, and how to summarize patterns without lying to yourself about what the data supports.

**What this involved:**

- Loading and inspecting the raw dataset : column types, obvious garbage, structure
- Missing value analysis (not just `.isnull().sum()` and calling it a day - deciding *why* something's missing)
- Duplicate detection and handling
- Boolean filtering to isolate patient subgroups
- Feature engineering from existing columns
- Parsing and manipulating date/time fields (admission dates, stay lengths, etc.)
- String cleanup - inconsistent casing, whitespace, formatting errors
- Custom functions with `apply()` and lambdas for row-wise logic
- Sorting, ranking, and groupby aggregations to pull out actual insights

---

---

# 🧠 Learning Roadmap

```text
Series
   │
   ▼
DataFrames
   │
   ▼
Missing Data
   │
   ▼
Merge • Join • Concatenate
   │
   ▼
GroupBy & Aggregation
   │
   ▼
Pivot Tables
   │
   ▼
Operations
   │
   ▼
Projects
```

---

# 📌 Resources

* Pandas Official Documentation
* NumPy Documentation
* Jupyter Notebook

---

<p align="center">This repository is part of my journey toward becoming proficient in Data Science, Machine Learning, and Artificial Intelligence by building a strong foundation in Python's scientific computing ecosystem.
If you find this repository helpful, consider giving it a ⭐.

**Open for learning and reference : fork it, use it, improve on it.**

</p>
