### Statistics in the newsroom

*Rob Barry, WSJ @rob_barry*

*Steven Rich, Washington Post @dataeditor*


**Don't overthink things: Basics**

* counting, summing, grouping and ranking

**Seek the middle**

* Mean
* Median
* Both tell a different story, both have limitations. Be aware that if you are averaging something you may weight things heavily 

***Improper use of statistical methods can obscure reality and distort our stories***

**Other tools you can use:**

* Quartiles: medians on steroids
*  Correlation - measuring the degree to which groups of numbers move together. Range from -1 to 1
*  Example of using correlation in print - Libor furor: key rate gets new scrutiny (WSJ)

**Visualisation**

* Histograms: frequency - bins, buckets, groups - shows distribution of your numbers
* R >hist(salaries) - shows distribution in one line of programming

**Standard deviation and distribution**

* Standard deviation - measures distance from the average
* Normal distribution - bell curve
* Log-normal distribution - numbers grouped to the left
* Cauchy distribution - very sharp peak
* If you know the distribution you can make assertions of the probability of the values
* Monte Carlo distribution to show insider trading before companies report dismal results - improbably lucky trades
* By randomly shuffling the executive's trades we can calculate a distribution of possible returns

**P-values**

* Statistical significance
* Probability
* Significance levels -.05 (most common), -.01 (threshold)

**T-tests**

* Used to test hypotheses about means when the population variance is unknown
* Developed by Gossett for the quality control of beer
* Single sample t - one group, test against hypothetical mean
* Independent samples t - 2 means, 2 groups, no relation between groups

**ANOVA**

* Analysis of variance - compare three or more groups
* Within vs between groups

**Fisher's exact test**

* Good for small data series, small sample sizes
* Gives exact P-value
* Great for categorical data eg male vs female, RH vs LH

**Linear regression**

* Based on y=mx+b
* x - independent variable
* y = dependent variable
* m - slope
* b - ???

**R-square**

* How much the independent variable predicts the direct variable
* Anything above .8 is highly correlated

**Logistic regression**

* Variable isn't always continuous
* Race, gender - binary data

**Pearson's chi-squared**

* Observed vs expected
* Eg. tax lien auctions in DC (Washington Post)
* Wanted to look at how frequently irregular patterns occurred between bidders. Used this test

**How to avoid mistakes**

* Try to prove yourself wrong
* Run it by your targets - eg government office
* Ask someone who is smarter than you - call an expert
* Make sure you are doing the correct test
* <http://www.ats.ucla.edu/stat/sas/whatstat> - will tell you what test is important to run 

* When you are unsure what test to use, consult IRE tipsheets - David Donald, Jen Lafleur
* Try not to use higher level stats if you don't need to
* Ask yourself what the easiest way of solving the problem is
* Seek out the outliers but give context - this is where stats come in handy: how far from the expected value are they, and then attempt to explain why
* correlation does not equal causation