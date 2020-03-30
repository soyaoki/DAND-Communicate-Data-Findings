# Bay Wheels Ride Data in 2018 Exploration and Visualization
## by Soya AOKI


## Dataset
> Bay Wheels is a regional public bicycle sharing system in the San Francisco Bay Area, California operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States.

> The dataset used for this exploratory analysis is System Data of Bay Weels(https://www.lyft.com/bikes/bay-wheels/system-data). It consists of monthly individual trip data from January 2018 to December 2018 in CSV format covering the greater San Francisco Bay area. Each trip in the Dataset is anonymized and includes:

  - Trip Duration (seconds)

  - Start Time and Date

  - End Time and Date

  - Start Station ID

  - Start Station Name

  - Start Station Latitude

  - Start Station Longitude

  - End Station ID

  - End Station Name

  - End Station Latitude

  - End Station Longitude

  - Bike ID

  - Bike Share for All (https://www.lyft.com/bikes/bay-wheels/bike-share-for-all)

  - User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)


## Summary of Findings

> I was interested in how people use the Bay Wheels. Summarization of all of findings from exploration are shonw below.

  - Distribution of duration is very skewed to the right and has one peak.

  - Most used station to start and end is "San Francisco Caltrain Station 2". And most used root is "San Francisco Caltrain Station 2" ↔︎ "Townsend St at 7th St".

  - 85% of users are subscribers.

  - Users of Bike-Share-for-All is almost 10%.

  - There is no difference of trip duration between months.

  - Users take long trip on Saturday and Sunday.

  - There are two peaks of long trip at 1 a.m and 2 p.m.

  - Subscribers use more short time.

  - Trend of count of use is not difference between Customer and Subscriber.

  - Customer has one peak at 5 p.m. On the other hand, Subscriber has 2 peaks at 8 a.m and 5 p.m.

  - Customer's use inscreases at weekend. But Subscriber's use decrease at weekend.

  - Customers tend to return the bike to the start station more than Subscribers.

  - Customers uses the bike at weekend. On the other hand, Subscribers uses the bike on weekdays at 8 a.m and 5 p.m.


## Key Insights for Presentation

> Most important insight I want to tell others was "Customers uses the bike at weekend. On the other hand, Subscribers uses the bike on weekdays at 8 a.m and 5 p.m."　So to tell the insight clearly, some designs of visualization were changed from exploring, shown below.

  - Setting axis-label, legend and titile.

  - Setting colors Customer as blue and Subscriber as orange.
