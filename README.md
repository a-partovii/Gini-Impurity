## Gini Impurity Calculation

This project provides a simple implementation to calculate Gini Impurity. The script calculates the Gini Impurity for each feature column and its values from a given dataset in an Excel file.

It includes two versions:
- **(Classic)**: Calculates Gini Impurity using the last column as the label, supporting only 'yes' or 'no' labels.
- **(Evolved)**: Can work with any feature and its values as the label column and label, relative to a user-specified target.

It is part of a practice project assigned by a university professor, designed to help students learn basic data analysis concepts.

### Attentions
1. Place the file path into the `file_path` variable inside the script. 
2. In the classic version the last column of the dataset must contain the target labels (`yes` or `no`). 
3. Make sure the dataset is an Excel file(`.xlsx` or `.xls`) and properly formatted.
 

### Requirements
- Python 3.x
- Libraries: `pandas` `termcolor`

### Documentation
All details, including the explanation of the code and its output, are available in the `gini-impurity.pdf` file provided with this project.

**This is a simple exercise and not intended for production use.**




