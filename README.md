# Commercial Airlines Analysis

## Point of Interest and Purpose
For our project, we have chosen to focus on the passenger loads of airplanes, and how the number of people booked for a flight compared to the flight’s capacity correlates with the revenue earned by the airline as a result of the flight. We chose this topic because we were interested in the process of overbooking that often occurs on major airlines. In fact, our plane on the way to GTE had to pay several thousands of dollars to get extra passengers off of the flight. We were wondering the extent to which overbooking flights is beneficial, which led us to the analysis we are hoping to make: what is the optimal capacity to book a flight that will maximize airline revenue and consumer satisfaction?

## Data Collection Process
In the process of selecting our datasets, we searched for information relevant to the observations we were trying to make (load factors, passenger counts, revenue, domestic vs. international). We found this data by looking through government statistics sites because we knew they would have errors to be cleaned, and we also found information general to specific airlines. There was a lot of internet digging while looking for these sets because some information wasn’t readily accessible.

## Data
Dataset 1: Air Carrier Statistics (CSV File)
The data contains details on the availability of seats on each flight. Along with that, the dataset contains variables such as aircraft type, service class, scheduled and performed departures. These variables will allow us to identify specific factors that contribute to an optimal load factor. The relationship between these factors and the load factor will allow us to determine the efficiency and reliability of an airline's operations, which directly impacts revenue. 

Dataset 2: Revenue and Financial Data of Delta (HTML)
The dataset contains financial information of Delta by year along with the passenger load factor. This will help to analyze the relationship between overbooked flights and the total revenue of the company. It will enable us to determine the impact of load factor on the financial performance of a company. 

Dataset 3: Los Angeles International Airport - Passenger Count By Carrier (JSON)
The dataset provides passenger counts for different airport carriers operating at LAX. The data will provide a focus on passenger volumes for the different airlines. This will allow us to evaluate their performance in relation to this data. The dataset will help to validate if the observed trend between load factor and revenue holds in a major airport hub such as LAX.

Dataset 4: Load Factor (passenger-miles as a proportion of available seat-miles in percent (%))
This dataset includes the load factor for all U.S. carriers across all airports. Load factor is a key performance indicator that measures the percentage of available seating capacity that is actually filled with passengers. This data will be used to determine the efficiency of airline operations in terms of seat utilization. The load factor is a critical variable for testing our hypothesis.

Dataset 5: Operating Revenue (In Thousands of Dollars $000)
This dataset includes the operating revenue for all U.S. carriers across all regions. This data will be used to analyze the financial performance of airlines in relation to their operational efficiency. It provides a direct measure of the revenue generated, which is crucial for validating our hypothesis about the relationship between load factor and revenue.

Dataset 6: Net Income (In Thousands of Dollars $000)
This dataset includes the net income for all U.S. carriers across all regions. Net income measures the profitability of airlines after all expenses have been deducted. This data will be used to assess the financial health of airlines and is crucial for validating our hypothesis on the relationship between operational efficiency and profitability.

## Overall Results and Conclusion
Through our project, we found that passenger load factor and net profit margin have a positive correlation, with international load factors tending to be a bit lower than domestic load factors on average. We also found that Delta Airlines has a higher and more consistent load factor than other airlines on average, and Delta has a lower average difference between departures scheduled and departures performed than many airlines, corresponding to its increased load factor. Because of the relationships between our data, we conclude that to maximize efficiency and revenue, an airline must have a consistently high passenger load factor. This is beneficial to both the airline and the customers because the airlines can maximize their profits and customers can reliably get to where they want to go.

This assignment gave us an opportunity to further familiarize ourselves with class content, and to apply it in a way that enhanced our learning. We learned new methods like pd.merge()  to join our three extra sources together into a single DataFrame. One of the greatest challenges of our team was finding data that was relevant to our topic, because much of the information we found gave us only a few columns to work with, so we combined the insights of multiple datasets to draw conclusions about our topic as a whole.
