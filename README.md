**Rules Implemented**

Rental Database needs to keep track of three main entities namely User, Car and Reservation.

- Car can be rented from a rental location with a specific address of each rental location.
- Rental location keeps track of contact phone number, contact email and rental location address with street name, state and zip code.
- Rental location can have multiple number of cars for rental.
- Each car is identified by VIN, Registration number, status as ‘Available’ and ‘Unavailable’, seating capacity of the car, disabled friendly features, color, model and manufactured year.
- Car has a parameter as Car Type.
- Type can be ‘Economy’, ‘Standard’, ’SUV’, ‘Premium’ and ‘Minivan’.
- Type defines the rental price per day.
- Users can take Insurance per day for the rental car.
- There are different types of insurance each having different medical insurance coverage, collision coverage and bodily coverage.
- Insurance Types are ‘Liability’ and ‘Comprehensive’.
- Car type and Insurance Type drives the Insurance price per day.
- Users can reserve a car for a number of days.
- Users can use any valid promotional code which is maintained by status.
- When an user books a car, they mention the start date and end date.
- The end date will be temporary at the time of reservation and updated with actual end date when the car is returned.
- If the actual end date is greater than end date mentioned initially, then a penalty is imposed.
- The total amount is calculated based on start date, end date, rental price per day, insurance price per day and promotional code used (if any).
- Users can cancel a reserved car before they rent.
- A reservation can have status as ‘Reserved’, ‘Completed’ and ‘Cancelled’.
- When the car is reserved, status will be in ‘Reserved’ Status.
- Once the reservation is completed and once the amount is paid, the status will be ‘Completed’.
- User can drop the car at any location.
- Car will be available for future use from the location where it is dropped.
- Users are categorized as guest or customer.
- Users can continue reserving car as a guest as long as he has not registered as customer.
- Users are uniquely identified by their license number.
- Users information consists of name as first name, middle name and last name, email address, physical address, date of birth and contact number.
- Registered user will be provided with login id and password.
- Users can save their credit/ debit card details for future payment.
