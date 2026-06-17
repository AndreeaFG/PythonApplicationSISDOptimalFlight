Intelligent Decision Support System for Flight Selection

Overview

This project implements an Intelligent Decision Support System (IDSS) designed to assist users in selecting the most suitable flight based on multiple decision criteria. The system evaluates available flight options according to ticket price, flight duration, number of layovers, and current weather conditions at the destination. The main objective is to automate the flight selection process and provide an optimal recommendation using a weighted multi-criteria decision-making approach.

Features
- Flight filtering based on destination and user-defined budget
- Three decision modes:
  Cheap (Cost-Oriented) – prioritizes lower ticket prices
  Fast (Time-Oriented) – prioritizes shorter travel times
  Balanced – provides a compromise between all criteria
- Integration with the OpenWeatherMap API for real-time weather information
- Automatic calculation of a final score for each flight option
- Ranking and recommendation of the best available flight
- "Surprise Me" mode for discovering the best destination regardless of location preference
- User-friendly graphical interface developed with Tkinter.
  
Implementation

The application was developed in Python using:
- Tkinter for the graphical user interface
- CSV files as a lightweight local database for flight information
- OpenWeatherMap API for retrieving weather data
- A weighted scoring model that evaluates flights based on normalized criteria:
  - Price
  - Duration
  - Number of layovers
  - Weather conditions
The scoring weights are dynamically adjusted according to the decision mode selected by the user.

Testing



The system was tested using multiple scenarios involving different destinations, budgets, and decision preferences. The results confirmed the correct operation of the filtering mechanism, ranking algorithm, weather integration, and recommendation process.
