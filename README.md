# polynomial
# Polynomial Constant Term Calculator

This is an Express.js application that calculates the constant term of a polynomial based on given roots. The application uses Lagrange interpolation to compute the constant term \( c \).

## Features

- Decodes roots from various bases.
- Calculates the constant term of the polynomial using Lagrange interpolation.
- API endpoint to handle requests and return the computed value.

## Technologies Used

- **Node.js**: JavaScript runtime for building server-side applications.
- **Express**: Web framework for Node.js.
- **Body-Parser**: Middleware for parsing incoming request bodies.
- **Big-Integer**: Library for handling large integers.
- **Morgan**: HTTP request logger middleware.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/polynomial-calculator.git
   cd polynomial-calculator
