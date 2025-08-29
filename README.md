# Discount Calculator

This Python program calculates the final price of an item after applying a discount.  

## Function Description
The program defines a function:

```python
def calculate_discount(price, discount_percent):
    if discount_percent >= 20:
        return price - (price * discount_percent / 100)
    else:
        return price
