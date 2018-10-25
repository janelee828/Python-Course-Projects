# Python-Course-Projects Unit 1
# Creates system that prints receipt for a furniture store
# Date completed: 2018-10-25

# Add item lovely_loveseat for sale

lovely_loveseat_description = """
Lovely Loveseat. Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white.
"""

# Set item price for lovely_loveseat

lovely_loveseat_price = 254

# Add item stylish_settee for sale

stylish_settee_description = """
Stylish Settee. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black.
"""

# Set item price for stylish_settee

stylish_settee_price = 180.50

# Add item luxurious_lamp for sale

luxurious_lamp_description = """
Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade.
"""

# Set item price for luxurious_lamp

luxurious_lamp_price = 52.15

# Define sales tax rate at 8.8%

sales_tax = 0.088

# Set first customer's purchase price total

customer_one_total = 0

# Set first customer's purchase list

customer_one_itemization = ""

# Add price of lovely_loveseat to first customer's total

customer_one_total = customer_one_total + lovely_loveseat_price

# Add description of lovely_loveseat to first customer's purchase list

customer_one_itemization = customer_one_itemization + lovely_loveseat_description

# Add price of luxurious_lamp to first customer's total

customer_one_total = customer_one_total + luxurious_lamp_price

# Add description of luxurious_lamp to first customer's purchase list

customer_one_itemization = customer_one_itemization + luxurious_lamp_description

# Calculate first customer's sales tax

customer_one_tax = customer_one_total * sales_tax

# Add sales tax to first customer's total

customer_one_total = customer_one_total + customer_one_tax

# Print receipt for first customer

print("Customer One Items:")
print(customer_one_itemization)
print("Customer One Total:")
print(customer_one_total)

# Set second customer's purchase price total

customer_two_total = 0

# Set second customer's purchase list

customer_two_itemization = ""

# Add price of stylish_settee to second customer's total

customer_two_total = customer_two_total + stylish_settee_price

# Add description of stylish_settee to second customer's purchase list

customer_two_itemization = customer_two_itemization + stylish_settee_description

# Add price of luxurious_lamp to second customer's total

customer_two_total = customer_two_total + luxurious_lamp_price

# Add description of luxurious_lamp to second customer's purchase list

customer_two_itemization = customer_two_itemization + luxurious_lamp_description

# Calculate second customer's sales tax

customer_two_tax = customer_two_total * sales_tax

# Add sales tax to second customer's total

customer_two_total = customer_two_total + customer_two_tax

# Add line in between receipts

print("")

# Print receipt for second customer

print("Customer Two Items:")
print(customer_two_itemization)
print("Customer Two Total:")
print(customer_two_total)

