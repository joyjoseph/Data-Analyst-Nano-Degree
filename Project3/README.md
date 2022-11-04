# Airline Passenger Satisfaction
## By Joy Joseph

## Dataset

Customer's satisfaction is a major factor to any successful business. In many industries, satisfing customers
could mean that few customers are dissatisfied, hence helps to reduce the cost of failures. The provided dataset was collected from [Kaggle](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction). There are 129,880 survey entries and passenger/flight details from a US airline with 24 features. Most variables are numeric, and few being categorical in nature.

- Satisfaction : Airline satisfaction level(Satisfaction, neutral or dissatisfaction).
- Age : The actual age of the passengers.
- Gender : Gender of the passengers (Female, Male).
- Type of Travel : Purpose of the flight of the passengers (Personal Travel, Business Travel).
- Class : Travel class in the plane of the passengers (Business, Eco, Eco Plus).
- Customer Type : The customer type (Loyal customer, disloyal customer).
- Flight Distance : The flight distance of this journey.
- Inflight Wifi Service: Satisfaction level of the inflight wifi service (0:Not Applicable;1-5).
- Ease of Online Booking : Satisfaction level of online booking
- Inflight Service : Satisfaction level of inflight service.
- Online Boarding : Satisfaction level of inflight service.
- Inflight Entertainment: Satisfaction level of inflight entertainment.
- Food and drink: Satisfaction level of Food and drink.
- Seat comfort: Satisfaction level of Seat comfort.
- On-board service: Satisfaction level of On-board service.
- Leg room service: Satisfaction level of Leg room service.
- Departure/Arrival time convenient: Satisfaction level of Departure/Arrival time convenient.
- Baggage handling: Satisfaction level of baggage handling.
- Gate location: Satisfaction level of Gate location.
- Cleanliness: Satisfaction level of Cleanliness.
- Check-in service: Satisfaction level of Check-in service.
- Departure Delay in Minutes: Minutes delayed when departure.
- Arrival Delay in Minutes: Minutes delayed when Arrival..

## Summary of Findings

 When investigating variables, Arrival Delay had missing values, the ID column was not useful for gaining insights. All of the missing data were dropped, the ID column was dropped as well from the dataset to move forward.
 
 The Distribution of Airline Passengers shows that among the 129,880 Airline Passengers, 56.6% are Neutral or Dissatisfied while 43.4% are satisfied. The ratings are from 0-5, 0 being the lowest raing and 5 being the highest. We see that Airline service with the highest ratings of 4 and 5 are In-flight Service, Baggage Handling, follwed by On-board Service, Seat Comfort, Online Boarding, Leg Room Service, Cleanliness, In-flight Entertainment, Departure and Arrival Time Convenience and Check-in Service. On the other hand, Airline service with the lowest ratings of 2 and 3 are In-flight Wifi Service, Ease of Online Booking.

 The categorical column plots shows that the Percentage Distribution of Airline Passengers is more for female, Returing customers, Business purpose and Business-Class than the rest. This means that, the Distribution of Airline Passengers is 50.74% female, 81.69% Returning customers, 69.08% for Business purpose and 47.87% Business-Class type compared to the rest. The plots with numerical columns, shows that the Percentage Distribution of Airline Passengers by their age is more around 20 - 50 than the rest.
 
 The correlation plot shows that, there is little or no correlation between Airline passener Age and flight distance, however, it shows a high correlation between Airline Departure Delay and Arrival Delay. This implies a linear relationship between them. The correlation between Departure Delay and Arrival Delay is very high. Age and Flight Distance don't have strong correlations with any other numeric variables in the dataset.

 The Flight Distance is more for perssengers on Business class compared to the rest. This means that Business Class Passengers are more comfortable with longer flight distance. There doesn't seem to be that much interaction between Gender and Customer Type of Airline Passenger, there seems to be some interaction between the Type of Travel and Customer Type of Airline Passenger, as the numbers of Airline Passenger for business reasons is more with the Business class than the Economy Class, the numbers of Airline Passenger for personal reasons is more for Economy Class than the rest.

 It is interesting to note that there are some positive relationships between the categorical variables and numeric variable Flight distance. We see that the gender variable does not have so much insight, as there is no difference between the male and female. However, for Returning Airline Passenger the level of satisfaction and travel distance is high compared to the First time Airline Passenger. Also, for the Business-Class type, the level of satisfaction and travel distance is high compared to Economy and Economy plus-Class. More also for Airline Passenger travelling for Business reason than personal.
 
 The multivariate exploration showed that there is a positive relationships between the categorical variables and numeric variables such as: Flight distance and the categorical variables, Departure delay and Arrival delay, Cleanliness, Food and drink variable.
 
 From the Analysis, it can be concluded that the most satisfied customers are those in the Business-Class and the least satisfied customers were those in The Economy-Class. The Returning customers are the most satisfied customers while the first time customers were the least satisfied customers. Also, Airline Passenger travelling on Business purpose are the most satisfied customers than those travelling for Personal reason. 

 Furthermore, there are some positive relationships between the categorical variables and numeric variables of interest. The plot shows that Airline passengers who are younger tend to choose Economy-Class more while the middle age tend to choose Economy plus-Class and the older people tend to choose Business-Class. And Business-Class Passengers are more comfortable with longer flight distance.

 Finally, we can recommend that in order to improve overall satisfaction, Airlines should focus more on the Economy-Class, First time Passengers and Passenger travelling for Personal reasons


## Key Insights for Presentation

 For the presentation, I started by introducing the percentage of Airline Passenger who are Satisfied or Neutral/Dissatisfied, followed by the distribution of each variable and then the relationships between features in the dataset.