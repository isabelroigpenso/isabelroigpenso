# Prediction-Of-Used-Cars-Prices

## Problem Definition

### The Context:
This is a predictive analysis of prices of use car in the Indian market with the goal of finding the optimal price for profiting while keeping a competitive advantage in the Indian Automobile market.

The used car industry in India has grown a lot in the past few years. It has even managed to grow over the new car market in India. In 2018-19, the used car industry was valued at 4M, while the new car industry was valued at 3.6M.
This growing market is opening opportunities for business and asiigning the right price.
While the market for new cars is relatively deterministic and does not have so much variance, since it is managed by OEMs, the market for used cars has many more variables to take into account and can create a lot of variability in the final price. Therefore, the need to assign the right price to a used car is needed to break into the industry.

### The objective:
Create a statistical model that effectively predicts the price of a used car in the Indian Market to be able to correctly assign the price to a used car at the time of selling.
The key questions:
Which supervised learning model predicts the price of a used car better?
Which varibles are of higher importance when calculating the price of a used car? Which variables are not?
Which variables have high interaction with one another?
The problem formulation:
Generate a statistical model with a continuous dependent variable (price) using the "usedcars" dataset.

### Data Dictionary
- S.No. : Serial Number
- Name : Name of the car which includes Brand name and Model name
- Location : The location in which the car is being sold or is available for purchase (Cities)
- Year : Manufacturing year of the car
- Kilometers_driven : The total kilometers driven in the car by the previous owner(s) in KM
- Fuel_Type : The type of fuel used by the car (Petrol, Diesel, Electric, CNG, LPG)
- Transmission : The type of transmission used by the car (Automatic / Manual)
- Owner : Type of ownership
- Mileage : The standard mileage offered by the car company in kmpl or km/kg
- Engine : The displacement volume of the engine in CC
- Power : The maximum power of the engine in bhp
- Seats : The number of seats in the car
- New_Price : The price of a new car of the same model in INR 100,000
- Price : The price of the used car in INR 100,000 ( *Target Variable* )
