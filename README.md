# mortgage_data
This repository contains the data and notebooks for a DrivenData classification competition which can be found at
https://datasciencecapstone.org/competitions/14/mortgage-approvals-from-government-data/page/43/

A summary of my understanding of the data, steps taken for generating predictions and results of the model evaluation and analysis are contained in the report.pdf.

## Data analysis notebook
The notebook data_inspection.ipynb contains statistics and visualizations for understanding the data. 

## Data transformation and machine learning notebook
The notebook model_catboost_final.ipynb contains the data transformation pipeline, as well as the catboost model building and evaluation.
In the last cells of the notebook, the model is used to make predictions on the score set and export the score set in the correct format to be uploaded on DrivenData.