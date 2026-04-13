# Processed Data

## Overview  
This folder contains the cleaned and transformed datasets derived from the raw seismic event data. These datasets are used directly for model training and evaluation in the Tsunami Alert Classification project.

---

## Processing Steps Applied  

The following transformations were applied to the raw data:

- Handling of missing values  
- Removal of inconsistent or irrelevant records  
- Feature selection based on relevance and correlation  
- Encoding and formatting adjustments for modeling  
- Standardization of variables where applicable  

---

## Contents  
The processed dataset includes structured features such as:

- Magnitude  
- Depth  
- CDI (Community Determined Intensity)  
- MMI (Modified Mercalli Intensity)  
- SIG (Seismic Significance)  
- Geographic variables (if retained)  
- Target variable (tsunami classification)  

---

## Usage  
This dataset is used for:

- Training machine learning models  
- Model evaluation and validation  
- Feature importance analysis  
- Performance comparison across algorithms  

---

## Important Notes  
- This dataset is derived exclusively from the `raw/` folder  
- All transformations are documented in the project notebooks  
- It represents the final dataset used for modeling tasks  

---

## Purpose  
The processed data ensures consistency, reliability, and readiness for machine learning workflows.
