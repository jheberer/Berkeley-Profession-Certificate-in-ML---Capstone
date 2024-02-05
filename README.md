### Predict Hotel Cancelation Rate

**Jonathan Heberer**

#### Executive summary
Predicting hotel cancelations can be extremely beneficial for hotel businesses. In this analysis, we looked at the many characteristics of a reservation and the reserving party, to understand what features lead can be used to predict if a booking will get canceled. 
Our initial analysis found that factors like lead time, average daily rate, type of deposit are some of the key features in determining if a hotel reservation may get cancelled. We found discerning differneces in cancellation pattern of parties traveling with and without kids. We concluded that a random forest method can, in fact, give us a prediction model of desirable precision to predict cancellation rates. 

#### Rationale
Hotel cancellations, commensurate with travel boom, skyrocketed from 2019 to 2022. We experienced about 15% cancellations in 2019, which was up to 20% in 2022. An almost 33% increase. With the economic slowdown being what it is, this sort of prediction model can help hotel with revenue planning, staffing, and other operational planning.
Hotels can also use this pattern to inform their cancellation policies.

#### Research Question
What features of a reservation can predict hotel cancellation?

#### Data Sources
Importing hotel cancellation data sourced from Kaggle- https://www.kaggle.com/datasets/arezaei81/hotel-bookingcvs/data

High level data description: Data contains - Details of a reservation (lead time, dates, status, etc,) - Information on the booking party, such as number of kids, previous cancellation history - Information on the hotel, property type.

#### Methodology
Exploratory data analysis
Feature engineering/data cleanup
Machine learning models for classification such as random forest, decisions trees.

#### Results
1. Lead time i.e. time between making a reservation and reservation arrival time, features prominently in being to predict if a reservation will get cancelled.
2. Average daily rate: The more expensive the room is, the more likely it is that it may be cancelled. This could be promiment in cases where people will cancel the original reservation if they get a better deal elsewhere.
3. arrival day of the month:  The reservations booked for arrival in the later half of the month are more likely to get cancelled than earlier. This could be a budgetary situation where parties may reconsider hotel travel if they are rethinking their budget of the month. 

#### Next steps
1. This study included a lot of non refundale deposite propoerties. Another analysis with refundable bookings could yield more insight into that area specifically.
2. We found significant differences in cancellation time of reservations (as how many days before arrival time) based on "traveling with kids", "deposit type". A follow up research could be done to model for cancellation time and see if we can predict a desirable policy for hotels of various types.

#### Outline of project

- https://github.com/jheberer/Berkeley-Profession-Certificate-in-ML---Capstone/blob/main/hotelcancellations_21.ipynb


##### Contact and Further Information
Jonathan Heberer
Michigan
517-614-0626
jrheberer@gmail.com