# Matplotlib-Challenge

This project focused on the data of the study carried out on 249 mice identified with SCC tumor growth and were treated with a variety of Drug Regimens.

The first section of this challenge focuses on the how the dataset used in the course of this project was clensed as well as using groupby and summary statistical methods to calculate the mean, median, variance, standard deviaton and SEM value by grouping the drug regimen with the tumor volume. The result series was then assembled into a single summary DataFrame.

A histogram was plotted in order to check if the data was even distributed using the tumor volume column of the cleaned DataFrame. 

Two different bar chart was plotted showing the total number of timepoints for all mice tested for each drug regimen using Panda and Matplotlib respectively.

Two different pie chart was plotted showing the distribution of female or male mice in the study using Pandas and Matplotlib.

The second section of this challenge focuses on calculating the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin and the quartiles and IQR was calculated to determine if there are any potential outliers across all four treatment regimens.

A grouped DataFrame showing the max value of the timepoint for each mouse was generated and merged with the original cleaned DataFrame. 

A list that holds the treatment names, as well as a second empty list that holds the tumor volume data was created, which makde it possible to loop through each drug in the treatment list, locating the rows in the merged DataFrame that correspond to each treatment.  The final tumor volumes result was then append for each drug to the empty list and the outliers was determined using the upper bound and the lower bound.

In the final part of this challenge, a mouse that was treated with Capomulin was selected and analysed, and a line graph was plotted showing the tumor volume vs. timepoint for that mouse.

A scatter graph was also plotted showing the tumor volume versus mouse weight for the Capomulin treatment regimen. 

The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment was calculated and the linear regression model was plotted showing a trend on top of the previous scatter graph.
