---
layout: page
root: .
title: Data Carpentry at the Fed - Details
---

**April 7th - 8th, 2016**

<br>**Time:** 8:30am - 4:30pm



[Workshop materials](#materials) |  [Tenative Schedule](#schedule)

<a name="materials"></a>
### Workshop Materials

#### About the Data
In this workshop, we will be using a subset of the Gapminder dataset [http://www.gapminder.org](http://www.gapminder.org). This is world wide statistical data collected and curated to allow for 
a 'fact based worldview'. This data includes things like employment rates, birth rates, death rates, % of GDP that's Agriculture and many, many more data types. There are currently 519 overall, with time series for each. 

In this workshop we're going to be focusing just on
- Country
- Continent
- Year data was collected
- Life expectancy at birth
- Total population
- per-capita GDP

We'll work with this data as a spreadsheet and read it in to R and SQL. It is also available as an R package
([repo](https://github.com/jennybc/gapminder), [CRAN](cloud.r-project.org/package=gapminder))
and there are some nice summary statistics and visualizations. 

There's also a great TED talk by Hans Rosling on this dataset and some awesome statistics.  
[http://www.ted.com/talks/hans_rosling_shows_the_best_stats_you_ve_ever_seen?language=en](http://www.ted.com/talks/hans_rosling_shows_the_best_stats_you_ve_ever_seen?language=en)

**Downloading the data**  
Download the data for this workshop from [this link](https://github.com/JohnRMoreau/2016-04-07-FederalReserveBoard/raw/gh-pages/data/gapminder-sql-data.zip). The data includes
* Messy spreadsheet data - gapminder-messy.xls or gapminder-messy.xlsx
* Messy data for cleaning in OpenRefine - gapminder-messy-openrefine.csv
* Clean data for R and SQL - gapminder-FiveYearData.csv

**Lesson materials**
* [Spreadsheet lessons](http://johnrmoreau.github.io/spreadsheet-gapminder-lesson)
* [OpenRefine lessons](http://johnrmoreau.github.io/openrefine-gapminder-lesson)
* [R lessons](http://tracykteal.github.io/r-novice-gapminder)
* [SQL lessons](http://johnrmoreau.github.io/sql-gapminder-lesson-DC)

<a name="schedule"></a>
### Tentative Schedule
### Day 1
<table>
<tr><td>8:30</td><td>Welcome and Introduction</td></tr>
<tr><td>9:00</td><td><a href=http://johnrmoreau.github.io/spreadsheet-gapminder-lesson>Spreadsheets</a></td></tr>
<tr><td>10:15</td><td>Coffee</td></tr>
<tr><td>10:45</td><td><a href=http://johnrmoreau.github.io/openrefine-gapminder-lesson>OpenRefine for data cleaning</a></td></tr>
<tr><td>12:00</td><td>Lunch</td></tr>
<tr><td>1:00</td><td>
Introduction to RStudio and R<br>
- <a href=http://tracykteal.github.io/r-novice-gapminder/01-rstudio-intro.html>RStudio Introduction</a><br>
- <a href=http://tracykteal.github.io/r-novice-gapminder/02-project-intro.html>Setting up a project in RStudio</a><br>
- <a href=http://tracykteal.github.io/r-novice-gapminder/03-seeking-help.html>Getting help</a>
</td></tr>
<tr><td>2:30</td><td>Coffee</td></tr>
<tr><td>2:45</td><td>Data types in R<br>
- <a href=http://tracykteal.github.io/r-novice-gapminder/04-data-structures-part1.html>Data structures part 1</a><br>
- <a href=http://tracykteal.github.io/r-novice-gapminder/05-data-structures-part2.html>Data structures part 2</a><br>
- <a href=http://tracykteal.github.io/r-novice-gapminder/06-data-subsetting.html>Data subsetting</a><br>
</td></tr>
<tr><td>4:00</td><td>Wrap up</td></tr>
</table>

### Day 2
<table>
<tr><td>8:30</td><td>Day 2 Welcome</td></tr>
<tr><td>8:40</td><td><a href=http://johnrmoreau.github.io/sql-gapminder-lesson-DC>SQL for data management</a>
</td></tr>
<tr><td>10:15</td><td>Coffee</td></tr>
<tr><td>10:30</td><td>SQL Part 2</td></tr>
<tr><td>11:30</td><td>SQL and R</td></tr>
<tr><td>12:00</td><td>Lunch</td></tr>

<tr><td>1:00</td><td>Functions and data manipulation in R<br>
- <a href=http://tracykteal.github.io/r-novice-gapminder/07-functions.html>Functions</a><br>
- <a href=http://swcarpentry.github.io/r-novice-gapminder/12-plyr.html>plyr</a><br>
- <a href=http://swcarpentry.github.io/r-novice-gapminder/13-dplyr.html>dplyr</a><br>
</td></tr>

<tr><td>2:30</td><td>
Coffee</td></tr>

<tr><td>2:45</td><td>
Graphics and reporting in R<br>
- <a href=http://tracykteal.github.io/r-novice-gapminder/08-plot-ggplot2.html>ggplot2 for Plotting</a><br>
- <a href=http://resbaz.github.io/r-intermediate-gapminder/18-rmd.html>R Markdown and knitr</a> <br>
- Capstone - Time Permitting<br>
</td></tr>
<tr><td>4:00</td><td>Wrap up</td></tr>
</table>



#### Additional Materials

### <a name="before">Before the Workshop

### <a name="setup"></a>Setup and Software Installation

To participate in this Data Carpentry workshop, you will need working copies of the software described at the setup page. For this workshop, it will be in a computer lab and the software has already been installed. For information on what was installed and how to install it on different operating systems, information is here:

[Setup Instructions](http://datacarpentry.github.io/2015-06-30-FederalReserveBoard/install.html)

### <a name="surveys"></a>Workshop surveys

You will receive a post-workshop survey after the workshop so you can provide feedback and help us gauge the effectiveness of the materials. 
