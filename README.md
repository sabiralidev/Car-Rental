# Car Rental Management System

A small, console-based C++ program for managing a rental from a predefined list of three cars.

## Features

- View cars and their availability
- Rent an available car and calculate the cost by day
- Return a car and view active rental details
- Validate menu choices and rental duration

## Build and run

Compile with a C++11-compatible compiler:

```sh
g++ -std=c++11 car_rental.cpp -o car_rental
```

Run `car_rental` (on Windows, run `car_rental.exe`).

Rental data is kept in memory and resets when the program exits.
