# Receipts for Lovely Loveseats 🛋️

A Python 3 project from Codecademy that calculates customer receipts for a fictional furniture store — *Lovely Loveseats for Neat Suites on Fleet Street.*

## 👨‍💻 Author
**Mohammad Z. Sohail**

> Fun fact: I do Codecademy for free time!

---

## 🧾 Description
This beginner-friendly program demonstrates how to:
- Use **variables** to store product descriptions and prices  
- Perform **basic arithmetic** to calculate totals and taxes  
- Combine strings for **formatted customer receipts**

---

## 🐍 Code Example
```python
# Lovely Loveseat Description
lovely_loveseat_description = "Lovely Loveseat. Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white."
lovely_loveseat_price = 254.00

# Stylish Settee
stylish_settee_description = "Stylish Settee. Fawn leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black."
stylish_settee_price = 180.50

# Luxurious Lamp
luxurious_lamp_description = "Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade."
luxurious_lamp_price = 52.15

# Tax rate
sales_tax = 0.088

# Customer 1 purchase
customer_one_total = lovely_loveseat_price + luxurious_lamp_price
customer_one_tax = customer_one_total * sales_tax
customer_one_total += customer_one_tax

print("Customer One Items:")
print(lovely_loveseat_description)
print(luxurious_lamp_description)
print("Customer One Total:")
print(customer_one_total)
