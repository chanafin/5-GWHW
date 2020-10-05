
Mice Cancer Treatment Studies - This represents an introduction in how Python and Pandas can be useful tools when it comes to statistical and graphical analysis. The goal is to draw insights from cancer treatment data, apply statistical helpful visualizations. 

Before the visuals are constructed, it is important to study the data after it is read in to the notebook. After sorting the values of each mouse by their ID, it is apparent that data has duplicates. Using .duplicated() to identify the duplicate mouse, the mouse is then removed from the DataFrame.

A summary statistics table is created by calculating the mean, median, variance, standard deviation & standard error for each drug type using a groupby and python functions. The data is then compiled into a DataFrame.




