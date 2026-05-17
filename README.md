Ticket Booking System
🚀 Overview

This project simulates a basic ticket booking system using Python. It checks whether a user is eligible to book tickets, applies discounts, adds extra charges, calculates service fees, and finally computes the total ticket price.

🧠 Features
1. User Eligibility Check
Users above age 17 are allowed to book tickets.
Additional condition for evening shows based on age.
2. Membership Discount
Members aged 21 or above get a discount.
Non-members do not receive any discount.
3. Extra Charges
Extra charges apply for:
Weekend bookings
Evening shows
4. Service Charges

Based on seat type:

Premium → 5
Gold → 3
Others → 1
5. Final Price Calculation

Final price is calculated as:

final_price = base_price + extra_charges + service_charges - discount
🧾 Input Variables
base_price = 15
age = 21
seat_type = 'Gold'
show_time = 'Evening'
is_member = False
is_weekend = False
⚙️ Logic Flow
Check if user is eligible to book tickets
Check eligibility for evening shows
Apply membership discount (if any)
Add extra charges (weekend/evening)
Calculate service charges based on seat type
Compute final ticket price
🧪 Example Output
User is eligible to book a ticket
User is eligible for Evening shows
User does not qualify for membership discount
Discount: 0
Extra charges will be applied
Extra charges: 2
Service charges: 3
Final price of ticket: 20
💡 Concepts Used
Conditional statements
Logical operators
Nested decision-making
Real-world pricing simulation
📌 Future Improvements
Add user input system (input())
Convert into GUI or web app
Add multiple ticket booking support
Include dynamic pricing rules
