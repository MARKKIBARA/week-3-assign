# week-3-assign
week three assignment
# 💲 Discount Calculator in Python

This simple Python program calculates the **final price of an item after applying a discount**.  
The discount is only applied if it is **20% or higher**; otherwise, the original price is returned.

---

## 🚀 Features
- Takes original price and discount percentage as input.
- Applies discount only when it is **≥ 20%**.
- Displays the final price clearly.

---

## 🛠️ How It Works
1. The program defines a function:
   ```python
   def calculate_discount(price, discount_percent):
       if discount_percent >= 20:
           discount_amount = (discount_percent / 100) * price
           return price - discount_amount
       else:
           return price
