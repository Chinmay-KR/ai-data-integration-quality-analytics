# AI-Driven Data Integration Quality for Multi-Source Analytics

## Overview

This project focuses on improving data quality across multiple data sources using AI-based techniques such as entity resolution, similarity matching, and text normalization.

The system integrates data from multiple customer datasets and identifies duplicate or inconsistent records to create a cleaner unified dataset.

This project was originally developed during my internship at **Rooman Technologies** as part of a collaborative team project.  
This repository represents my personal portfolio version demonstrating the implementation.

---

## Problem Statement

Organizations often collect data from multiple systems such as CRM platforms, transaction systems, and marketing tools.  
These datasets frequently contain:

- Duplicate records
- Inconsistent naming formats
- Missing information

Poor data quality leads to inaccurate analytics and business decisions.

---

## Solution

The system performs the following pipeline:
Multiple Data Sources
↓
Data Preprocessing
↓
Similarity Matching
↓
Entity Resolution
↓
Clean Unified Dataset

---

## Technologies Used

- Python
- Pandas
- Scikit-learn
- FuzzyWuzzy
- Data Visualization

---

## Project Structure
data/ → Raw customer datasets
docs/ → Project documentation
src/ → Core processing modules
run_project.py → Main execution script
requirements.txt → Python dependencies

---

## Key Modules

### preprocess.py
Handles data cleaning and normalization.

### similarity.py
Calculates similarity scores between records.

### entity_resolution.py
Detects duplicate entities across datasets.

### visualize.py
Generates visual insights from the processed data.

---

## How to Run

Install dependencies:
pip install -r requirements.txt

Run the project:
python run_project.py


---

## Example Use Cases

- Customer data deduplication
- Data warehouse integration
- Multi-source analytics pipelines
