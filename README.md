# Joint Assessment of Cardiac Index with Mean Arterial Pressure and Risk of Acute Kidney Injury in the Surgical Intensive Care Unit 

## System requirements/installation
Built using Python 3.9.18. All package ruqirements in `requirements.txt`

Requirements can be installed in a conda environment via:
```
pip install -r requirements.txt
```
## Notebook files

### Notebook 01
This notebook performs hemodynamic feature engineering only.  
No outcome information is used in this notebook.

### Notebook 02
This notebook performs final model training, evaluation, and interpretation.  
Hyperparameters are fixed and loaded from prior cross-validated tuning.

## Data
Due to patient privacy restrictions, we do not provide patient-level datasets. This notebook validates expected input schemas and reproduces cohort summary statistics when run on an analysis-ready dataset.
