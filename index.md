# Titanic Survival Analysis

**Author:** Brandon Jean  
**Date:** November 2, 2025  

---

## Project Overview

This project analyzes the Titanic dataset using Python and Seaborn to explore which factors influenced passenger survival. It walks through data inspection, visualization, feature engineering, and model preparation.

---

## Goals

- Understand the structure of the dataset  
- Identify and handle missing values  
- Visualize relationships between features  
- Engineer useful features for modeling  
- Define input features (X) and the target variable (y)  
- Perform train/test splits with stratification  

---

## Dataset

The Titanic dataset includes **891 passengers** with features like:

- `survived` (0 = No, 1 = Yes)  
- `pclass` (passenger class)  
- `sex`, `age`, `fare`  
- `sibsp` (siblings/spouses aboard)  
- `parch` (parents/children aboard)  
- `embarked` (port of embarkation)  

Some columns, like `age` and `deck`, contain missing values that were cleaned using median or


