# Driver-Incentive-Program
A Java-based program to help drivers maximize monthly earnings by calculating optimal trip schedules based on vehicle capacity, trip duration, and passenger count.
## Table of Contents

- [About](#about)
- [Program Features](#program-features)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [License](#license)

## About

The Driver Commission Optimizer is designed for a car company’s driver incentive program, allowing drivers to maximize their monthly commission by optimizing trip schedules. Each driver earns R10 per passenger, and this program calculates:

1. The maximum number of passengers a driver can carry over the month.
2. The maximum commission based on the optimal passenger count.
3. The sequence of cars that should be driven to achieve this commission.

## Program Features

- **Optimal Trip Scheduling**: Uses dynamic programming to find the best sequence of trips for maximizing passengers.
- **Commission Calculation**: Computes the daily and monthly commission based on passenger count.
- **Output to File**: Results are written to an `output.txt` file, detailing passengers carried, cars used, and commission earned.

## Usage

### Requirements

- Java Development Kit (JDK) installed.

### Running the Program

1. Clone this repository:
   ```bash
   git clone https://github.com/White0011Fang/Driver-Incentive-Program.git
