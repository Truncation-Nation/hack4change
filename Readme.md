# Truncation Nation - Hack4Change
<b>Hack4Change Hackathon</b>
DataLink is a hackathon - an event where you have less than 24 hours to perform data analysis on public datasets. Compete to perform analysis to test your theories and write a report on your findings before the time is up!

## About us
We are 4 3rd year Computer Science with Data Science scholars at UCD, with a keen interest in statistical data analytics. As proficient Python programmers, we felt it was only natural to use Jupyter Notebooks as the environment for our analysis.

* <a href="https://github.com/ciaranpflanagan">Ciaran Flanagan</a>
* <a href="https://github.com/brianbyrne99">Brian Byrne</a>
* <a href="https://github.com/mcglincheyeoghan">Eoghan McGlinchey</a>
* <a href="https://github.com/willisevan">Evan Willis</a>

# Can we find a correlation between air travel and Covid related incidents? 
Our group wanted to examine the relationship between air travel and Covid cases and
deaths. In particular we wanted to discover what impact air travel had on Covid cases
and deaths. We were also interested in finding how counties which had airports were
affected by Covid versus counties which do not have airports. Surprisingly we found that
the reducing levels of air travel did not lead to similar trends in the levels of Covid cases
in Ireland.

## Relationship between air travel and daily Covid cases
The first thing we examined was the relationship between the air traffic in Ireland and
the number of Covid cases. We did this by plotting a scatter plot of the number of flights
versus the number of confirmed daily cases and creating a time series that displayed
how both the number of flights and the number of cases progressed over time. We were
also able to plot a line of best fit on the scatter plot and display the correlation
coefficient. We were surprised to find out that there was a very weak negative
relationship between the number of flights and the number of cases. The correlation
coefficient was just -0.12, although upon inspecting the scatter plot, we could identify
many outliers. Upon inspecting the time series, we recognised that the trends of the
number of cases and the number of flights simply did not correlate.

## Relationship between air travel and daily Covid deaths
Next, we examined the relationship between the air traffic in Ireland and the number of
Covid deaths. Once again, we used a scatter plot with a line of best fit and a time series
graph to interpret the results. This time we found that there was a weak moderate
relationship between the number of flights and the number of Covid deaths, since the
correlation coefficient was -0.57. Although the fact that the correlation coefficient was
negative implies that as the number of flights increased, the number of Covid deaths
actually decreased. Once again, upon inspecting the time series, we observed no
correlation between the trends of the number of flights and the number of confirmed
cases.

## Relationship between air travel and total number of Covid cases and deaths
Next, we examined the relationship between the number of flights and the total number
of Covid cases and deaths. We did this using a scatter plot with two lines of best fit. We
found that the relationship between the number of flights and the total number of Covid
cases and deaths was extremely weak with correlation coefficients of just -0.06 and 0.13
respectively. This suggests that the number of flights did not have a significant effect on
the number of Covid cases and deaths in this country.

## Relationship between daily Covid cases and the number of patients hospitalised due to Covid
Next, we examined the relationship between the number of daily Covid cases and the
number of patients hospitalised due to Covid. We did this using a scatter plot with a line
of best fit. We found that the relationship between the daily Covid cases and the number
of patients hospitalised due to Covid was very weak with a correlation coefficient of just
0.2. This might suggest that not many people who contract the virus need to go to
hospital, which also might suggest that most of the people who contract the virus do not
have underlying health conditions or are old.

## Relationship between daily Covid cases and daily Covid deaths
Next, we examined the relationship between the number of daily Covid cases and the
number of Covid deaths. We did this using a scatter plot with a line of best fit. We found
that the relationship between the daily Covid cases and the number of Covid deaths was
very weak with a correlation coefficient of just 0.23. This might suggest that the virus has
a very low mortality rate. However, it is worth noting that the scatter plot did contain
many outliers.

## Conclusion
After analysing the data we came to the conclusion that there was no strong correlation
between the number of flights or air travel and the number of Covid cases in the country.
We would have expected to see a rise in the number of Covid cases once the airports
reopened in mid summer. We also saw a big rise in the number of Covid cases in late
Autumn whereas the number of air travel stayed relatively quiet. Furthermore, it would appear that the international airports have necessary Covid-19
procedures and controls, to prevent an extreme spread of the virus. A promising sign.


