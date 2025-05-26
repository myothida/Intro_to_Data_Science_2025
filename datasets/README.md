---
title: IPU Dataset

---

# Dataset Description

The dataset contains global monthly rankings of women in national parliaments from 2019 to 2025.

## Datasets

**Dataset Name: `IPU2019_2025_raw.csv`**
   
     
### Data Collection

- The required data attributes for this analyis are extracted from here. [https://data.ipu.org/data-explorer/](https://)

   - **Format**: CSV (Comma-Separated Values)
   - **Size**: 
   `IPU2019_2025_raw.csv / 365 KB`

  
 
   - **Uesd Columns**:
     - `Year`
     - `Country name`
     - `Structure of parliament`
     - `Structure & status of parliament` 
     - `Current number of members` 
     - `Region` 
     - `Women` 
     - `Percentage of women` 
     - `Gender quota` 
     - `MEN`
     - `Percentage of men`
     



## How to Use the Data

1. **Loading the Data**: 
   You can load the dataset into your project using Pandas library. 
   
   Example for CSV:
   ```python
   import pandas as pd
   data = pd.read_csv('data/IPU2019_2025_raw.csv')
