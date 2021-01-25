# Bikesharing:  Anyalysis of NYC Citi Bike Service

## Overview of the analysis: 
The purpose of this analysis is to examine data associated with the New York City Citi Bike Service in order to present data to possible investors who may invest in brining this service to our client's home town of Des Moines, Iowa. ![Des Moines, Iowa](/Resources/Des_Moines_Iowa.png).

## Technology:
The primary technology associated with this analysis is Tableau for presenting visualizations that will convince the investors to invest.  The data file is a large flat .csv file.  However, a key column of data is not in the needed format to prepare visualizations.  Therefore, a second technology used is Python Pandas where the .csv is read in and the trip duration column is converted from the original integer format in seconds to the new format of Hours:Minutes:Seconds.  After converting the tripduration column, Pandas is used to export the converted dataframe to a new .csv.  From this second .csv, the visualations are prepared.

## Results: 
There are five primary visualizations generated for this data.

### Checkout Times for All Users
The following link is to the visualization that indicates the hour of the day and how many bikes are checked out and for what duration they are checked out:
[Checkout Times for All Users](https://public.tableau.com/views/NYCCitiBikeAnalysisChallenge/CheckoutTimesforUsers?:language=en&:display_count=y&:origin=viz_share_link)

### Checkout Times for All Users, Segregated by Gender
The following link is to the visualization that indicates the same data as the previous link, except with this visualization, the data is segregated by gender:
[Checkout Times by Gender](https://public.tableau.com/views/NYCCitiBikeAnalysisChallenge/CheckoutTimesbyGender?:language=en&:display_count=y&:origin=viz_share_link)

### Trips by Weekday for Each Hour

[Trips by Weekday for Each Hour](https://public.tableau.com/views/NYCCitiBikeAnalysisChallenge/TripsbyWeekdayforEachHour?:language=en&:display_count=y&:origin=viz_share_link)

### Trips by Weekday for Each Hour by Gender

[Trips by Weekday for Each Hour by Gender](https://public.tableau.com/views/NYCCitiBikeAnalysisChallenge/TripsbyGender?:language=en&:display_count=y&:origin=viz_share_link)

### User Trips by Gender by Weekday by Subscriber vs Ad Hoc Customers

[User Trips by Gender by Weekday by Subscriber vs Ad Hoc Customers](https://public.tableau.com/views/NYCCitiBikeAnalysisChallenge/UserTripsbyGenderbyWeekday?:language=en&:display_count=y&:origin=viz_share_link)

## Summary: 
Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.

;