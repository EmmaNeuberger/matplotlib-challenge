##Pymaceuticals

#Project Overview

The goal of this project was to analyze drug treatment on tumor volume, metastasis and survival using the Pandas Library and the Jupyter Notebook and Matplotlib.


Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the number of data points for each treatment regimen.

Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

Generate a line plot of time point versus tumor volume for a single mouse treated with Capomulin.

Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

Summary
Graph 'Tumor Response to Treatment' shows that the drug Capomulin had a better result, the tumors volume for the mice taking Capomulin shrunk in course of trial while for the mice taking the other drugs, tumors volume grew almost with the same rate.
Alt Text

Graph 'Metastatic Spread During Treatment' shows that all tumors had metastatic spread regardless of the drug, although the mice taking Capomulin had slowest metastatic spread and Placebo had the fastest spread.
Alt Text

Graph 'Survival During Treatment' shows that over 80% of the mice taking Capomullin has survived during the course of trial. For the other drugs survival rate dropped with almost same rate till day 30 and after that survival rate for Infubinol has significantly dropped.
Alt Text

According to these trends and tumor volume change percentage which we can see in the last graph, we could suggest Capomulin had the most favorable result between the compared drugs.
Alt Text