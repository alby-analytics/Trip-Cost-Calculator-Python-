# Trip-Cost-Calculator-Python-
A modular Python program that calculates the total cost of a trip by combining hotel stay, flight charges, car rental, and additional spending money. This project demonstrates clean function-based design, real-world business logic, and modular programming principles.

# Project Description
This system simulates a real-world trip planning backend module. It helps users calculate the full cost of a trip by breaking down expenses into independent components such as:
+ Hotel stay
+ Flight charges
+ Car rental
+ Additional spending money
Each component is handled using a separate function, making the program easy to maintain, extend, and reuse.

# Features
+ Modular function-based architecture
+ Clean and readable Python code
+ Real-world pricing logic
+ Discount logic implementation
+ Scalable design
+ Beginner to intermediate friendly
+ Industry-style cost calculation structure

# Functional Modules
1️. hotel_cost(nights)
+ Calculates hotel stay cost
+ Cost per night: $140
+ Returns total hotel cost

2. plane_ride_cost(city)
+ Returns round-trip flight cost based on destination

3.rental_car_cost(days)
+ Base cost: $40/day
+ Discount Rules:
1. >= 7 days → $50 discount
2. >= 7 days → $50 discount
 Only one discount applied

4.trip_cost(city, days, spending_money)

Combines:
+ Hotel cost
+ Flight cost
+ Rental car cost
+ Spending money
+ Returns total trip cost

# Learning Outcomes
+ Function-based design
+ Parameter passing
+ Return values
+ Conditional logic
+ Modular programming
+ Business logic modeling
+ Code reusability
+ Clean architecture principles

# Future Enhancements
+ User input interface
+ Menu-driven system
+ GUI version (Tkinter)
+ Web version (Flask)
+ Database integration
+ API integration
+ Currency conversion
+ Trip report generation
+ PDF invoice generation
