# Feature-selected datasets for Si-Al-Cu-Cr-Fe-Ni high-entropy alloys

This repository provides the feature-selected datasets used in the manuscript:

**Design of Si-Al-Cu-Cr-Fe-Ni high-entropy alloys with improved hardness based on data-augmentation and interpretable machine learning strategy**

## Dataset description

This repository contains two Excel files:

| File name       | Description                                                         |
| --------------- | ------------------------------------------------------------------- |
| `phase.xlsx`    | Feature-selected dataset for high-entropy alloy phase prediction    |
| `hardness.xlsx` | Feature-selected dataset for high-entropy alloy hardness prediction |

Both datasets were obtained after feature engineering and feature selection. The retained descriptors were used as model inputs for the machine-learning tasks reported in the manuscript.

## Data usage

The datasets can be used to reproduce or verify the data basis of the machine-learning models described in the manuscript, including:

* phase-structure prediction of Si-Al-Cu-Cr-Fe-Ni high-entropy alloys;
* hardness prediction of high-entropy alloys;
* analysis based on the selected physical and empirical descriptors.

## File format

The datasets are provided in `.xlsx` format and can be opened using Microsoft Excel, WPS Office, or Python packages such as `pandas` and `openpyxl`.

Example Python code for reading the datasets:

```python
import pandas as pd

phase_data = pd.read_excel("phase.xlsx")
hardness_data = pd.read_excel("hardness.xlsx")

print(phase_data.head())
print(hardness_data.head())
```

## Notes

Only the feature-selected datasets are provided in this repository. The datasets contain the descriptors retained after the feature selection process and were used for the phase prediction and hardness prediction models in the manuscript.

## Data availability statement

The feature-selected datasets used in this study are available in this repository.

## Contact

For questions regarding the datasets, please contact the corresponding author of the manuscript.
