## Course Project 1 - Exploratory Data Analysis

This project is for Course project 1 from Exploratory Data Analysis

More info at: https://www.coursera.org/learn/exploratory-data-analysis/peer/ylVFo/course-project-1

## Loading Data
When loading the dataset into R, please consider the following:

* The dataset has 2,075,259 rows and 9 columns. First calculate a rough estimate of how much memory the dataset will require in memory before reading into R. Make sure your computer has enough memory (most modern computers should be fine).
* We will only be using data from the dates 2007-02-01 and 2007-02-02. One alternative is to read the data from just those dates rather than reading in the entire dataset and subsetting to those dates.
* You may find it useful to convert the Date and Time variables to Date/Time classes in R using the \color{red}{\verb|strptime()|}strptime()  and \color{red}{\verb|as.Date()|}as.Date() functions.
* Note that in this dataset missing values are coded as \color{red}{\verb|?|}?.

## Making Plots
Our overall goal here is simply to examine how household energy usage varies over a 2-day period in February, 2007. Your task is to reconstruct the following plots below, all of which were constructed using the base plotting system.

First you will need to fork and clone the following GitHub repository: https://github.com/rdpeng/ExData_Plotting1

For each plot you should

* Construct the plot and save it to a PNG file with a width of 480 pixels and a height of 480 pixels.
* Name each of the plot files as \color{red}{\verb|plot1.png|}plot1.png, \color{red}{\verb|plot2.png|}plot2.png, etc.
* Create a separate R code file (\color{red}{\verb|plot1.R|}plot1.R, \color{red}{\verb|plot2.R|}plot2.R, etc.) that constructs the corresponding plot, i.e. code in \color{red}{\verb|plot1.R|}plot1.R constructs the \color{red}{\verb|plot1.png|}plot1.png plot. Your code file should include code for reading the data so that the plot can be fully reproduced. You must also include the code that creates the PNG file.
* Add the PNG file and R code file to the top-level folder of your git repository (no need for separate sub-folders)

When you are finished with the assignment, push your git repository to GitHub so that the GitHub version of your repository is up to date. There should be four PNG files and four R code files, a total of eight files in the top-level folder of the repo.