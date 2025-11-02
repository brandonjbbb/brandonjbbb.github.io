# Titanic Survival Analysis

**Author:** Brandon 
**Date:** November 2, 2025  

---

## Project Overview

This project explores the Titanic dataset to see which factors influenced passenger survival. It follows the same ML workflow used in your first project: inspect → explore → clean → engineer features → select X/y → split.

---

## Goals
- Inspect and understand the dataset
- Handle missing values (`age`, `embark_town`, `embarked`)
- Visualize survival by class and gender
- Create `family_size` feature
- Encode categorical data for modeling
- Compare basic vs. stratified train/test split

---

## Key Steps

1. **Import & Inspect** – load Titanic, view shape, info, head, missing values, and correlations.  
2. **Explore** – scatter plots, histograms, and count plots (class vs survived).  
3. **Clean** – fill missing ages with median, fill embark values with mode, drop `deck` (too many NaNs).  
4. **Feature Engineering** – `family_size = sibsp + parch + 1`, encode `sex`, encode `embarked`, convert `alone` to int.  
5. **Feature Selection** –  
   - **X:** `age`, `fare`, `pclass`, `sex`, `family_size`  
   - **y:** `survived`  
6. **Splitting** – used `train_test_split` and `StratifiedShuffleSplit` to keep survival ratios similar in train and test.

---

## Files (in main project repo)

- `notebooks/project02/ml02_brandonjean.ipynb`
- `notebooks/project02/titanic.csv`
- Repo: https://github.com/brandonjbbb/applied-ml-brandon

---

Made by **Brandon** 🟣
