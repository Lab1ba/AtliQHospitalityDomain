# Revenue Insights in Hospitality Domain

### Dashboard Link : https://app.powerbi.com/groups/me/reports/98b32e98-e696-4dfd-82e5-b4d104857fba/ReportSectionbd9c6580dcb089eea7ca?experience=power-bi

PROBLEM STATEMENT

AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

Task:  

You are a data analyst who has been provided with sample data and a mock-up dashboard to work on the following task. You can download all relevant documents from the download section.

- Create the metrics according to the metric list.
- Create a dashboard according to the mock-up provided by stakeholders.
- Create relevant insights that are not provided in the metric list/mock-up dashboard.

METRICS REQUIREMENT

All the required metrics with their dax formula are given in the metrics list.xlsx file.

To calculate week on week change of revenue, occupancy, realization etc I've added one new column to get the week number as wn and changed the day type from weekend from Saturday, Sunday to Friday, Saturday and others as weekday to see the changes of key metrices between weekday and weekend.

- Details of Hospitality Domain data

The database has five tables named dim_date, dim_hotels, dim_rooms, fact_bookings, fact_aggregated_bookings where the dim is dimension table and they make a star schema connected through dimension table's primary to fact table's foreign key and make one to many relation. Here is our data model:


![Screenshot (5)](https://github.com/Lab1ba/AtliQHospitalityDomain/assets/100675446/17627718-172d-4be2-b1fd-71d9e094e891)


# Hospitality Insights in PowerBI
- Report Snapshot (Power BI DESKTOP)

Key Insights

![Screenshot (6)](https://github.com/Lab1ba/AtliQHospitalityDomain/assets/100675446/083c565b-94bc-4dff-b4a6-ec8120b118ce)

Key Insights with Revenue Trend

![Screenshot (8)](https://github.com/Lab1ba/AtliQHospitalityDomain/assets/100675446/67bbd931-7e8e-45ea-b810-e614798f621f)

Key Insights with RevPAR Trend

![Screenshot (9)](https://github.com/Lab1ba/AtliQHospitalityDomain/assets/100675446/ac2fd58e-6c2a-4f4a-b1e5-b3508ecb7a66)

Key Insights with ADR Trend

![Screenshot (10)](https://github.com/Lab1ba/AtliQHospitalityDomain/assets/100675446/e09bc847-df79-4b5f-bbdf-f77b9a4e29b2)

General Insights

![Screenshot (7)](https://github.com/Lab1ba/AtliQHospitalityDomain/assets/100675446/ffa2ae52-cc50-41b4-81cd-01e36ba75ddd)

In the powerbi report, if we hover on the six key metrices then we would see their weekly trend in both weekdays and weekends.

% values in bottom of the key metrices are week on week change. The down arrow indicates that the values decreases from their previous week, up arrow shows that the values increases from their previous week and flat arrow indicates that there is no change in the values from their previous week. 

![Screenshot (12)](https://github.com/Lab1ba/AtliQHospitalityDomain/assets/100675446/c556bab0-fb58-40e3-bb5b-ef4aa4938643)

We can breakdown through the property name and see which type of rooms are mostly booked of a particular property. 

![Screenshot (18)](https://github.com/Lab1ba/AtliQHospitalityDomain/assets/100675446/e271fe92-5d2f-4e81-9c39-8eb036c6f1f0)

We can also see which particalur property earns the most revenue par available rooms and then in depth we get to know which category they have business, luxury or both and then again in each category which type of room class provides most RevPAR and which least.

![Screenshot (19)](https://github.com/Lab1ba/AtliQHospitalityDomain/assets/100675446/3a435dcc-2eab-446e-9fbb-f5ee13252526)


In general insights page, we have different filters like booking platform, properties, city, room type, status (cancelled, checked out, no shows). Also from this insights we found that,

- AtliQ Hotel's average rating is 3.62 out of 5. 

- Occupancy% is high in Delhi city but highest revenue comes from Mumbai.

- On weekend, occupancy% is higher than the weekday.

- Most bookings come from mumbai city.

- Weekday has more bookings but number of no show is more than weekend.

- Most of the bookings are done through the other type of platform. 

By looking at the ADR (Avearage Daily Rate) weekly trend, we can tell that there is no pricing strategy in their domain system. They didn't have any  attractive offers to get more customers and that's one of the main reasons why their business is falling.
