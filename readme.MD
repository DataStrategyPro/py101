The scripts in this project are designed to mimic a common data workflow. 

Note the 2 folders data/ and reports/ are empty placeholders which get populated by the python scripts. The scripts should be run in this order to get the necessary data. 

Step 1:
Run split_data_complete.ipynb 
This downloads a public dataset, splits it and populdates the data folder

Step 2:
Run visualize_complete.ipynb
This combines then visualizes all of the data files in the data folder

Step 3:
Run combine_complete.ipynb
This combines all of the data files in the data folder, and then creates a loop to generate reports from visualize_complete.ipynb for different filters and then saves each report as a separate file in the reports folder