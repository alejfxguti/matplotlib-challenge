# **Pymaceuticals - SCC Treatment Study**

Module 5 Challenge - analyzing pharmaceutical data and creating tables and figures

In this project, we analyze data from an animal study conducted by Pymaceuticals, a pharmaceutical company that specializes in anti-cancer medications. The study aimed to screen for potential treatments for squamous cell carcinoma (SCC), a common form of skin cancer.

As a senior data analyst at Pymaceuticals, you have been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

## **Results**

The results of the study are summarized in the **`pymaceuticals.ipynb`** notebook. They include:

- A DataFrame of summary statistics for each drug regimen, including mean, median, variance, standard deviation, and SEM of the tumor volume.
- Bar charts showing the total number of time points for all mice tested for each drug regimen throughout the study.
- Pie charts showing the distribution of female versus male mice in the study.
- A box plot showing the distribution of the final tumor volume for all the mice in each treatment group, highlighting potential outliers.
- A line plot of tumor volume versus time point for a mouse treated with Capomulin.
- A scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.
- The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment, plotted on top of the previous scatter plot.

## **Analysis**

- When comparing the top 2 Drug Regiments, Capomulin and Ramicane, Capomulin had less variabliity within its midrange. ALso of the top 4 drug regiments, Infubibnol was the only drug regiment shown to have an outlier which lies outside the lower bound.

- Ramicane and Capomulin also had a smaller Standard Deviations of their tumor size. This shows that the regimens produced more consistent results among the mice that they tested. The higher Standard Deviations of the other regimens show a more sporadic result range amongst the mice in those groups.

- As the weight of the mouse increases the tumor volume increases as well. This shows that there is a positive correlation between the weight and the tumor volume of the mice. The Pearson correlation coefficient of .84 shows that there is a high degree of correlation between these two varilables.

## **Conclusion**

Based on the results, we can draw conclusions about the effectiveness of the various drug regimens tested in the study. These conclusions can be used to guide further research and development of treatments for SCC.
