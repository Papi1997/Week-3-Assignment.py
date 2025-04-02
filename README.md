# Week-3-Assignment.py
#ANSWERS
#1.
def calculate_discount(price, discount_percent):
#Calculates the final price after applying a discount
    if discount_percent >= 20:
        discount_amount = (discount_percent / 100) * price
        return price - discount_amount
    return price 


# 2 .Prompt user for input
original_price = float(input("Enter the original price of the item: "))
discount_percentage = float(input("Enter the discount percentage: "))

#3. Calculate the final price
final_price = calculate_discount(original_price, discount_percentage)

#4. Display the result
print(f"Final price after discount: ${final_price:.2f}")# Using f string liberals
