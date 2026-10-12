**Netflix Data Analysis**: An exploratory data analysis project examining catalog growth, content types, and global distribution patterns on the streaming platform, Netflix, using Python.

**Goal**: This project investigates the evolution of Netflix's library over time using a dataset of 8,000+ titles. The goal is to perform data cleaning, contextual imputation of missing attributes, date-time feature engineering, and exploratory visual analysis to uncover core platform strategies.

**Tech Stack and Libraries:**
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab

**Key Data Cleaning & Preprocessing Steps**
**Handling Missing Values:**
   * Contextually filled missing `director` and `cast` entries with `'No Director Listed'` and `'No Cast Listed'`.
   * Imputed missing `country` values using the mode (most frequent country).
   * Handled missing content ratings by categorizing them as `'Not Rated'`.
**Feature Engineering & Parsing:**
   * Cleaned and converted `date_added` into proper `datetime` format.
   * Extracted `year_added` to track historical catalog growth trajectory.

**Business Insights & Findings**
* **Content Mix:** Movies dominate the overall library, outnumbering TV Shows by roughly a 2:1 ratio, highlighting a strong focus on movie acquisitions alongside series.
* **Catalog Expansion:** Platform additions experienced a massive surge between 2018 and 2021, marking Netflix's aggressive global content strategy and original production investments.
* **Rating Demographics:** The catalog is heavily skewed toward mature audiences, defining the platform's primary demographic targets.
