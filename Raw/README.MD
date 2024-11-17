# Subfolder Name: Data Analysis 

## Overview
This folder contains scripts and datasets for the analysis phase of the project. The focus is on preprocessing, exploratory data analysis (EDA), and feature engineering.

## File Structure
- `preprocessing.py`: Script to clean and preprocess the raw data.
- `eda.ipynb`: Jupyter Notebook with exploratory data analysis.
- `data/`: Subfolder containing all raw and processed datasets.
  - `raw_data.csv`: Original dataset.
  - `processed_data.csv`: Dataset after preprocessing.

## Data Dictionary
### raw_data.csv
| Column Name | Data Type | Description                     |
|-------------|-----------|---------------------------------|
| `id`        | Integer   | Unique identifier for records. |
| `age`       | Integer   | Age of the individual.         |
| `income`    | Float     | Annual income in USD.          |

### processed_data.csv
| Column Name  | Data Type | Description                     |
|--------------|-----------|---------------------------------|
| `id`         | Integer   | Unique identifier for records. |
| `age_group`  | String    | Age categorized into groups.   |
| `income_log` | Float     | Log-transformed income.        |

## Change Log
| Date       | Change Type | Description                         | Updated By |
|------------|-------------|-------------------------------------|------------|
| 2024-11-17 | Added       | Created `eda.ipynb`.                | J. Doe     |
| 2024-11-18 | Modified    | Updated `preprocessing.py` logic.   | J. Doe     |

## To-Do Items
- [ ] Add visualizations to `eda.ipynb`.
- [ ] Refactor `preprocessing.py` for scalability.
- [ ] Document new variables in the data dictionary.


