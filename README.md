# Visualizing Covid-19

## Announcement:

This is my first r-project.
 
As you know, Covid-19 coronavirus was first identified in the Wuhan region of China in December 2019. 
The World Health organization (WHO) declared the outbreak as the pandemic in March 2020.  

In this project, I am going to analyze the patterns of Covid-19 spread around the world. 
For example, how quickly does covid-19 virus spread around the world? 
What are the numbers of confirmed cases between China vs other countries?
Which countries are most affected by the pandemic? What is the infection rate among top 7 hard-hit countries over time?

The data used here was pulled from WHO on Mar 17, 2020 by Datacamp so the analysis here focuses on the early trend of covid-19 up to Mar 2020.

To download the data and script, clone this repo to your computer by copying and pasting the following in your command line interface.

 ```git clone https://github.com/ychoi3-git/Homework_0.git```

This repo contains rmd file and data for analysis in R-studio.

## Contents of the analysis:

1. What are the trends of worldwide confirmed cases over time? 

2. What are the patterns of confirmed cases of China vs the rest of the world over time? 

3. Let's annotate the milestone dates to the plot! 

4. Let's add a trend line for China!

5. Then add a trend line as well to the rest of world!

6. Which countries outside of China have been stricken hard by covid-19?
 
7. Let's plot top 7 the most stricken countries outside of China over time!


## Results:

1. By the time around Mar 15, 2023, the confirmed covid cases were 170,000 around the world.

2. The confirmed cases slowed down around Feb 25 in China while increased drastically around Mar 15 in other countries outside of China.

3. Global emergency was declared on 2020-01-30.  Pandemic was declared on 2020-03-11.

4. China: the confirmed cases’ growth slowed down than a linear trend line as of Mar 9 in China.  It is likely that corona virus was contained at this time in China.

5. Other countries outside of China: as of Mar 9, the confirmed cases increased much more than linearly in other countries.   When we transformed on a logarithmic scale, the line was almost the same to the linear line.  It indicates that confirmed cases were increasing exponentially during mid-March.

6. Seven top hard hit countries: while China was the most hit country in Asia, there was only one country (South Korea) in Asia out of top 7 countries. In addition, there were 4 countries (France, Germany, Italy, and Spain) in Europe, and Iran was the only country in the Middle East.  US was included in this list.

7. Italy and Iran were the countries where the confirmed cases increased the most dramatically around Mar 16.