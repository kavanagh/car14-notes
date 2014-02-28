### Introduction to R

##### Sharon Machlis, Computerworld

<http://bit.ly/RGuideIntro>
<http://bit.ly/Rresources>

R project for statistical computing - great for sophisticated data analysis, but also useful for basic and intermediate work eg. grouping, plotting, exploratory data visualisations. Works primarily on the command line

**When to use R over Excel:**

* Amazing community and lots of add-on packages
* Writing scripts - reproducable research - check, share, reproduce again and again. Create script once and use again and again

**Tour of R**

* Console - where you type in scripts
* Top right - history of all commands you have run
* Environment tab - as you store variables, they will appear here
* Bottom right - where visualisations will appear, where you can view add on packages, help files etc
* When you run equations, it will show the number of your results in brackets
* First command: library(lattice)
* install.packages
* data() - loads sample datasets
* plot(melanoma) - loads a chart of melanoma data in the bottom right window
* Up arrow cycles through the history of commands
* Create our own function:
	* regline <- lm(melanoma$incidence ~ melanoma$year)
	* lm: linear model
	* abline: trend line
	* <- is equals
	
* Store variables eg. x <- 5
* C function - concatenate
* Starts at 1 not 0, unlike other computer languages

When searching for column figures, always remember to add comma after, eg. melanoma[5,] Shows everything in column 5
