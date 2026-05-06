# 📊 Pandas Practice – Hierarchical Dataset Analysis

## 📌 Overview

This project is a hands-on practice using **pandas** to explore and analyze a real-world hierarchical dataset.

The dataset contains structured information with levels defined by an `Indent` column and categories defined by a `Group` column.

---

## 🎯 Objectives

* Understand dataset structure
* Perform data filtering and selection
* Handle missing values
* Explore hierarchical relationships using `Indent`

---

## 🗂️ Dataset Features

* Contains multiple columns like:

  * `Description`
  * `Group`
  * `CommonName`
  * `ScientificName`
  * `Indent` (hierarchy level)

---

## 🔍 Tasks Performed

### ✅ Basic Exploration

* Viewed dataset using `head()` and `info()`
* Checked data types and structure

### ✅ Data Cleaning

* Identified missing values
* Used `isnull()` to analyze null data

### ✅ Filtering

* Filtered rows based on `Indent`
* Searched text using `.str.contains()`

### ✅ Column Selection

* Extracted specific columns for analysis

---

## 🌳 Understanding `Indent`

The `Indent` column represents hierarchical levels:

* `0` → Main category
* `1` → Subcategory
* `2` → Sub-subcategory

This helps in understanding parent-child relationships in the dataset.



## 🛠️ Tools Used

* Python
* Pandas
* Google colab

---

## 📁 File

* `day1.ipynb` – Contains all code and practice

---

## ✍️ Author

* Jaswanth

