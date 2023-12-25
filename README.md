# total-sales-in-every-month
Total Sales In Every Month using NumPy

# Divine Flowers - Monthly Sales Calculator

## Overview

Divine Flowers is a flower shop that specializes in offering a variety of beautiful flowers. This Python script is designed to calculate the total sales for each month based on the quantity of flowers sold for different types and their respective unit prices.

## Usage

The script utilizes the NumPy library to efficiently handle array operations. The key components include:

- `unit_sold`: A NumPy array representing the quantity of flowers sold for each type in different months.
- `price_per_unit`: A NumPy array containing the price of one unit for each type of flower.
- `total_sales`: The result of multiplying the quantity sold by the price per unit, providing a comprehensive view of the total sales for each type in each month.

## Code

```python
import numpy as np

unit_sold = np.array([[50, 60, 25],
                      [10, 13, 5],
                      [40, 70, 52]])

price_per_unit = np.array([20, 30, 15])

total_sales = unit_sold * price_per_unit
