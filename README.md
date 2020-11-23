# Pymaceuticals
 Week 5 Homework

In this assignment, the study of performance of a treatment drug, Capumolin, was compared to other drugs' performance in tests on mice.

The data was first imported to jupyter notebook from csv files and two files Mouse_metadata.csv which contained the mice and which drug they were tested on and Study_results.csv which contained the results of the trials were merged.

The data was cleaned to drop any repeated timepoints for the mice. One mouse was dropped from the study due to duplicate data.

The mean, median, variance and standard deviation of the tumor volumes across all drug regimens. Capumolin and Ramicane showed the best results at a low mean and median and low variance and standard deviation.  Capumolin was slightly outperformed in all areas by Ramicane.
This data was shown by using group by and summary statistics as well as using an aggregate function to simplify the code.

Pandas and Matplotlib were used to show the number of mice tested in each regimen

Pandas and Matplotlib were used to show the distribution of male vs. female mice

The max timepoint for each mouse in Capomulin, Ramicane, Infubinol and Ceftamin were calculated using a loop compiling into a list of lists.  IQR, quartiles, upper bound, and lower bound of Tumor Volume were calculated then represented on a box and whisker plot showing only Ifubinol having any outlying tumor volumes.

In a closer analysis of the Capumolin results a mouse was chosen with the most timepoints, w914 to show tumor volume vs. timepoint in days on a line graph. The results showed dramatic decreases in tumor volume over time

A scatter plot was created to show mouse weight vs average tumor volume.  In the last step a regression line was calculated and overlaid on the scatter plot.  This showed that the larger the mouse was the larger the tumor volume.






