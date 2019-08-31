# PISA Dataset Analysis
## by Simón Muñoz

## Preliminary Wrangling

According to [Wikipedia](https://en.wikipedia.org/wiki/Programme_for_International_Student_Assessment), the Programme for International Student Assessment (PISA) is a worldwide study by the Organisation for Economic Co-operation and Development (OECD) in member and non-member nations intended to evaluate educational systems by measuring 15-year-old school pupils' scholastic performance on mathematics, science, and reading.

Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

In this notebook, we´re going to process the PISA dataset from 2012, which we downloaded from [Udacity servers](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1566844420961000).

## Main findings from the exploratory Analysis

* Wealth level of students has a clear positive effect on their PISA scores
* Wealthy students do not study out of class more than non wealthy ones
* Students with more books at home tend to obtain better scores.
* Also, owning a computer seems to be positively correlated with getting better scores.
* Wealthy students have greater chances of having more books at home and owning a computer.
* Students with a high number of books at home and who own a computer are ones getting the higher scores.

## Resources used during the development of this notebook

* Udacity Data Analyst Nanodegree
* [Matplotlib Documentation](https://matplotlib.org/3.1.1/contents.html)
* Seaborn [API Reference](https://seaborn.pydata.org/api.html)
* Stackoverflow [Pandas](https://stackoverflow.com/questions/tagged/pandas), [Matplotlib](https://stackoverflow.com/questions/tagged/matplotlib) and [Seaborn](https://stackoverflow.com/questions/tagged/seaborn) tags
