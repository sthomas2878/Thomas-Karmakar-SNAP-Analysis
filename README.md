# Thomas-Karmakar-SNAP-Analysis
This repository contains all of the data and code used in the paper "Understanding the Effect of the Supplemental Nutrition Assistance Program through Quasi-Experimental Methods" by Samuel Thomas and Bikram Karmakar.

## Files

### Documentation:

1. 1_Household Codebook PUF.pdf - Documentation for faps_household_puf.csv

2. 2_Individual Codebook PUF.pdf - Documentation for faps_individual_puf.csv

### Paper:

3. Final Paper.docx - "Understanding the Effect of the Supplemental Nutrition Assistance Program through Quasi-Experimental Methods" by Thomas and Karmakar

### Modeling Notebooks:

4. ProbitIV_R.Rmd - R Markdown file containing code for naive probit and probit instrumental variable models.

5. ProbitIV_R.html - HTML knit output of ProbitIV_R.Rmd.

6. RDD_R.Rmd - R Markdown file containing code for all rdd models.

7. RDD_R.html - HTML knit output of RDD_R.Rmd.

### Data Notebooks:

8. data_cleaning.ipynb - Python notebook containing code and output for data cleaning of faps_household_puf.csv.

9. data_cleaning_Indiv.ipynb - Python notebook containing code and output for data cleaning of faps_individual_puf.csv.

10. data_merge.ipynb - Python notebook containing code and output to merge cleaned household and individual datasets.

### Exploratory Data Analysis Notebook:

11. eda.ipynb - Python notebook containing code and output of exploratory data analysis section in Final Paper.docx.

### Data

12. faps_clean.csv - Output of data_merge.ipynb containing fully cleaned individual and household data used in Modeling Notebooks and Exploratory Data Analysis Notebook.

13. faps_household_clean.csv - Output of data_cleaning.ipynb containing clean household data.

14. faps_household_puf.csv - Original FoodAPS household dataset. Documentation for this dataset is 1_Household Codebook PUF.pdf.

15. faps_individual_clean.csv - Output of data_cleaning_Indiv.ipynb containing clean individual data.

16. faps_individual_puf.csv - Original FoodAPS individual dataset. Documentation for this dataset is 2_Individual Codebook PUF.pdf.
