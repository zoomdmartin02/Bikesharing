# Bikesharing:  Anyalysis of NYC Citi Bike Service

## Overview of the analysis
The purpose of this analysis is to examine data associated with the New York City Citi Bike Service in order to present data to possible investors who may invest in brining this service to our client's home town of Des Moines, Iowa. ![Des Moines, Iowa](/Resources/Des_Moines_Iowa.png).

## Technology
The primary technology associated with this analysis is Tableau for presenting visualizations that will convince the investors to invest.  The data file is a large flat .csv file.  However, a key column of data is not in the needed format to prepare visualizations.  Therefore, a second technology used is Python Pandas where the .csv is read in and the trip duration column is converted from the original integer format in seconds to the new format of Hours:Minutes:Seconds.  After converting the tripduration column, Pandas is used to export the converted dataframe to a new .csv.  From this second .csv, the visualations are prepared.

## Results 
There are five primary visualizations generated for this data.

### Checkout Times for All Users
The following link is to the visualization that indicates the hour of the day and how many bikes are checked out and for what duration they are checked out:
[Checkout Times for All Users](https://public.tableau.com/views/NYCCitiBikeAnalysisChallenge/CheckoutTimesforUsers?:language=en&:display_count=y&:origin=viz_share_link)

### Checkout Times for All Users, Segregated by Gender
The following link is to the visualization that indicates the same data as the previous link, except with this visualization, the data is segregated by gender:
[Checkout Times by Gender](https://public.tableau.com/views/NYCCitiBikeAnalysisChallenge/CheckoutTimesbyGender?:language=en&:display_count=y&:origin=viz_share_link)

### Trips by Weekday for Each Hour
The next link is to a visualization of a heat map that shows the days of the week and the hours of the day where the activity is most active:
[Trips by Weekday for Each Hour](https://public.tableau.com/views/NYCCitiBikeAnalysisChallenge/TripsbyWeekdayforEachHour?:language=en&:display_count=y&:origin=viz_share_link)

### Trips by Weekday for Each Hour by Gender
Again, this visualization is a heat map like the prior, but is broken down by gender:
[Trips by Weekday for Each Hour by Gender](https://public.tableau.com/views/NYCCitiBikeAnalysisChallenge/TripsbyGender?:language=en&:display_count=y&:origin=viz_share_link)

### User Trips by Gender by Weekday by Subscriber vs Ad Hoc Customers
Last, this visualization shows the number of bike rentals per day, indicating busyness by day and which gender:
[User Trips by Gender by Weekday by Subscriber vs Ad Hoc Customers](https://public.tableau.com/views/NYCCitiBikeAnalysisChallenge/UserTripsbyGenderbyWeekday?:language=en&:display_count=y&:origin=viz_share_link)

## Summary: 
In summary, the New York City Citi Bike Service data indicates that the highest number of bikes out on rent are about 3000 bikes for a trip duration between 5 and 6 hours.  Men are the highest users and more men than women keep the bikes out for longer durations.

The most busy time of the week is during morning and evening commutes, but Thursdays between 5 and 6 PM are the absolute busyiest times.  The same pattern for men and women being morning and evening commutes and Thursday being the heaviest day, but men by far are utlizing the service the most.

Subscriber rentals are much heavier than ad hoc customers.  This would indicate that the bikes are being utilized heavily for commutes over tourism.  Ensuring that pickup and drop-off centers in Des Moines where urban professionals live in high concentrations instead of concentrating on tourist locations would make sense based on the data.

A link to the full Tableau Story is as follows:  [Story](https://public.tableau.com/views/NYCCitiBikeAnalysisChallenge/BikeTripAnalysis?:language=en&:display_count=y&:origin=viz_share_link)

Other visualizations that might be useful would be to simulate Des Moines possible usage based on calculating a ratio of Des Moines population vs NYC population.  In other words, applying a fraction to the data to represent Iowa population would give you a count of bikes that would be needed for the Des Moines service.

I would also recommend visualizations that reflect the distances of the trips traveled in NYC to see if they match the urban geography of Des Moines.  In other words, if the proximity of work centers to living centers is within the general distances that NYC riders are traversing it would be a good indicator that Des Moines could support a Citi Bike service.