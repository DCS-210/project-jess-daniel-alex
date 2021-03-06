Olympic Performances
================
by Shoes

## Summary

Info on Dataset:
For this project, we loaded in data from four different datasets. The first dataset we used was a tally of all the Summer Olympic medal winners between 1976-2012. The second dataset we used was a csv file that contained Country names, country codes and continent names and codes, which we merged with the Summer Olympic medal file so that we could compare how certain continents performed in the Olympic games. By doing this, we created a new file called Olympic_final, which was the csv file that we used to make the graphs for most of the project. In addition, we used another dataset called gdp_data, which was a csv file that contained gdp data for every country during this time period. The fourth dataset we used was the dev tools library package, gapminder, which had some gdp and population data in it. While working with the data, we realized that the names of certain countries have changed dramatically and that countries as a whole have ceased and formed, especially around the end of the Cold War. Therefore, to accommodate for these issues, we decided to filter our data and only use data between the years of 1996 and 2008.


Research Question:
Originally, our research question was: Which regions are the best in which specific sport? However, as we moved along with our project and began working with the data almost every day, our priorities and interests changed as well. Now, we can best define what our research question has turned into as: Do population and GDP have an impact on the amount of medals won at the Olympics? We have worked with our data for weeks now, merging, joining and running regressions on it to see if our original question can be answered. While we do not have a concrete answer on which region is the best in which specific sports, we have come to analyze our data on a deeper level, by seeing how population trends and overall economic development of countries has affected how they perform on the Olympic stage.


Methodology:
Overall, we really worked to understand what our data was trying to tell us after we had merged a few datasets together and joined our data. Our goal was to comprehend all of these different data entries across several decades and numerous wars to see what has changed and how socio-economic and geo-political divides have had an impact on the Olympic games and which countries perform best at what sports. To be able to make our project work, we had to turn medals into numeric values (Gold = 3, Silver = 2, Bronze = 1), so that we could quantify what each medal is worth and which Countries overall performed the best and won the most total medals.


Findings:
Our findings, to be fair, very much surprised us and were not what we were expecting in the slightest bit. After making numerous graphs that showed how the world powers were dominating the Summer Olympic games and sitting atop the leaderboards of the medal count, we determined that in fact, there is little to no correlation that proves there is a relationship between GDP and medals in the Summer Olympics. The r^2 value of gdp and medals won at the Summer Olympics was 0.012. This finding really shocked us, as all we kept seeing were graphs that were lead by the United States, the United Kingdom, Russia and China to some extent. Therefore, as we were leading up to the process of making our regressions, we were almost certain that there would be at least a moderate relationship between GDP and medals in the Olympics. Obviously, we proved ourselves wrong, as we determined this was indeed not the case. Afterwards, we then decided to put the population to the test. We thought that if there was no relationship between GDP and medals won, there had to at least be a relationship between population and medals won. The more people you have in your country, the more people you can send to the Olympics in numerous different events. It turns out that we were again very wrong. We found there to be a 0.0521 r^2 value between population and medal value, which can be interpreted as little to no relationship between the two variables. Again, our inklings had been proven wrong. Altogether, while our initial predictions for the relationship of GDP and medal values and Population and medal values were both very off, it was fascinating to discover the truth about these relationships and see how even while analyzing data for such a long period of time, your initial guess can be very off and simply be disproved by an easy r squared calculation.


## Presentation

Our presentation can be found [here](presentation/presentation.html).

## Data

D. Agrawal, Summer Olympics Medals (1976-2008), electronic dataset, Kaggle. (2020). (viewed November 1, 2021), https://www.kaggle.com/divyansh22/summer-olympics-medals.

Core, List Of Continent Codes, electronic dataset, Datahub. (2017). (viewed November 3, 2021), https://datahub.io/core/continent-codes#data-cli.

## References

https://www.kaggle.com/divyansh22/summer-olympics-medals

https://datahub.io/core/continent-codes#data-cli

https://stackoverflow.com/questions/69998377/ggplot-fill-by-proportion-with-a-geom-col

https://www.maths.usyd.edu.au/u/UG/SM/STAT3022/r/current/Misc/data-visualization-2.1.pdf

http://www.flutterbys.com.au/stats/downloads/slides/figure/factors.pdf
