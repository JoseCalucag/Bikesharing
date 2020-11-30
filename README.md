<h1 align = "Center"> Bikeshare
</h1>

<p align = "center">
<img src = "https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/citi-bike-share-1527877670.jpg?crop=1xw:0.7496251874062968xh;center,top&resize=480:*">
</p>
<br>

<h2> Overview of the analysis </h2>

The purpose of this project is to see if the bike rental business is worth investing in for the city of Des Moines. Using 2019 data from the city of New York during the month of August, we will create visualizations to help illustrate some data points. 

<h2> Preparation </h2>
Prior to this, we need to change a data type of one of the columns ('tripduration') from reading as an integer into a timedate data; so it can be broken down into hours, minutes and seconds. We will do this by taking the csv into Python and converting the column into the proper data type. Once converted and exporting the newly transformed csv, we can then take it into Tableau to start our visualizations.

<h2> Results </h2>
Using the data, here are some of the key points that were visualized:

* There was a total of 2,344,224 NYC Citibike trips in the month of August in 2018.

* Of that total, 1,900,359 users subscribe to Citibike while there were 443,865 one time trip transactions.

* The average bike trip was approximately 5 hours, occuring on weekdays between 5-7 PM.

* When looking at the gender, we're seeing Males (1,530,272 trips) are outusing the females (588,431).

* More so, Male subscribers are predominantly using Citibikes.

You can see the visualizations [here](https://public.tableau.com/profile/jose.calucag#!/vizhome/NYC_Citibike_Challenge_16066928250250/CitiBikeNYCData?publish=yes).

<h2> Summary </h2>
With an average Yelp review of 3.6 out of 5 stars, there are noted flaws noted about Des Moines transit system (DART). Average weight times of 20-40 minutes and some areas too far out for most transit lines, Des Moines residents could use an alternative to get around the city. However, looking at a summer month shouldn't be the end all. I would also recommend to see if there is any data for the summer months to see if this business is seasonal or it can deal keep afloat all year around. Secondly, it would be beneficial to see data from Des Moines residents that would actually use the bike sharing service so, once initiated, Citibike can place the stations in proximity to customers that would use them.
