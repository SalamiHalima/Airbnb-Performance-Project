# Airbnb-Performance-Project

### Business Understanding:
Airbnb is an American company based in San Francisco, California. It operates an online marketplace for lodging, primarily homestays for vacation rentals, and tourism activities. The platform is accessible via website and mobile app.
 The company has two types of customers. One who hosts their place and the another who books the place for a particular time that is the end consumer utilizing the hosted place. 
Airbnb earns commission from both ends and hence have to make sure both of its customers are able to generate value from their business. They also have to make the hosted place offered on their platform provide the best services at reasonable prices and look out for the best technology to ease out the booking process for the end consumer without hassle.

### Background:
For the past few months, Airbnb has seen a major decline in revenue.
Now that the restrictions have started lifting and people have started to travel more. Hence, Airbnb wants to make sure that it is fully prepared for this change.
So, analysis has been done on a dataset consisting of various Airbnb listings in New York.

### Data Preparation: 	
Cleaned data to remove any missing values and duplicates. 
Dropped insignificant columns. 
Identified outliers.

### Feature Selection / Engineering
The most important step of the Data Pre-processing was to convert some of the numeric features into categorical variables by creating bins of them. 
Yet post conversion, we kept the numeric one’s handy tool for analysing. 

### Area Of Concentration:
In what time period the properties have received more or less number or reviews? 
Which months receives more bookings?
Which hosts have received the more reviews? 
Which locations are of high price? 
What type of properties are preferred by the customers? 
Which properties are available for more days in a year and in which location? 
Which properties and room types have more or less minimum night stay?
Which are the locations that are not performing well based on reviews and other parameters? 
Which are the room types that are not performing well? 
Which parameter makes the customer prefer the property and provide a review? 

### Reviews By Year
Initial years which were 2011 till 2014, last reviews were negligible.
The average number of reviews started increasing exponentially after 2015-2016. 
After that it is slowly going up and most of the last reviews are received in the recent years of the data that is 2019 and 2018.

### Total Bookings By Month And Neighbourhood Group
The 6th month of the year i.e June receives most of the reservation in all followed by 7th month. Manhattan have the overall highest  Bookings across almost all the months.
Which means, majority of the customers provide higher number of reservation during the summer period between the months of May till July or in the starting of the year which shows the higher booking window in a year. 

### Top 10 Host By Reviews
Michael, David, Alex, John and Daniel are the Top 5 hosts that seem to have received the highest number of reviews for their listed sites.
Most of the Host have Less than 3 reviews per month which indicates bad customer experience offered by majority sites. 
 Also, Majority of the sites have received less than 50 reviews till date which is kind of less.

### Average Price By Neighbourhood Group And Room Type
Manhattan has the highest average price of $197, then Brookyln with $124 for all room type. 
Queens and Bronx has the lowest average price $100 and $89 respectively.
Manhattan is the only Neighborhood in the Borough that lies in offering the Highest Price range properties on the platform followed by others with a Medium Price range on average. 
Prices offered above 120$ on average are considered to be a High Price, between 80$ to 120$, Medium Price range and less than 80$ to be considered Low Price range property.


### All Listings And Average Price
The Relationship between the Listing and Average price shows that Listing near the beach area are higher than the average price (Which are in Dark Blue).
Listing which are away from the shore are around the average price (Light Blue).
Having the highest average price to be $200, most of the listing close to the shore are around $1000 to over $7000 on average, which is a huge deal.

### Price Variation By Room Type And Neighbourhood Group
Entire home/apt has the highest average price by Neighbourhood group.
Private Room has a lesser average price.
Shared room is way lesser compared to Entire home/apt as expected.
In all of these, Manhattan have it room type to be more expensive than the others.

### Average Minimum Night By Neighbourhood Group
Average Minimum Night By Neighbourhood Group
Manhattan and Brooklyn are places providing the highest average number of minimum nights which makes them the top neighborhoods in offering maximum minimum nights stay.

### Reviews By Neighbourhood Group
Manhattan and Brooklyn has received the highest number of reviews and this is in relation to the availability to stay large amount of days in a year
We can confirm that the greatest parameter for any customer to prefer a property and provide a review is having a maximum or minimum night stay window booking and their probability of being open for more days in a year to some extent.

### Percentage Of Booking By Neighbourhood Group and Room Type
Majority of the sites hosted are either Entire apartments or Private rooms and very less Shared rooms across the 5 groups.
Manhattan and Brooklyn has received the highest number of booking and this can be based on the availability to stay open for large number of days in a year. 


## Recommendation
property owners in Staten Island, Queens and Bronx to identify their challenges for being fully functional for maximum number of days in a year and allow a booking of more than 10 days of minimum night stay. 
Create some sort of interaction between the Top 5 hosts to share their experience with the rest of the community for better improvement and value generating ideas. 
Provide discounted commission rates to property owners on keeping the minimum night stay booking window for more than 10 days and property functional for maximum number of days in a year.








