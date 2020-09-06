# Introduction
Data is often better understook when it is visualized and used to tell a story. This project is an exercise to visually present analysis results using Jupyter Notebook and the Python Matplotlib library. The fictional company Pymaceuticals is screening potential treatments for squamous cell carcinoma (SCC), a form of skin cancer, and this project aims to compare the performance of a drug of interest (Capomulin) over a 45 days-long study run on 250 mice identified with SCC tumor growth. The final plots are generated using both the Matplotlib `pyplot` module and Pandas. The code generates the following:
* Summary statistics for each of the studied treatments
* Bar plots showing the number of data points of each treatment regimen
* Pie plot showing the distribution of male and female mice in the study
* Final tumor volume of each mouse across the Campomulin, Ramicane, Infubinol, and Ceftamin regimens
* Whisker plot for all four treament regiments
* Line plot of time point versus tumor volume for individual mice
* Scatter plot of mouse weight versus average tumor volume for the Capomulin treatment

# Data set
This project is a practice exercise for basic data visualization using Python and is based in study results from a fictional company. _Under no circumstances should these results be used for further medical research_. The complete data set of this activity can be found in the `Mouse_metadata.csv` and `Study_results.csv` files, both included in this repository. These files were provided by the Tecnológico de Monterrey Data Analytics Bootcamp for the February - August 2020 term.

# Code description
To run this analysis, make sure to have the complete folder available with the corresponding data sets in the adequate folder, as the `Pymaceutical-Final-Report.ipynb` file calls them from your local folder.
