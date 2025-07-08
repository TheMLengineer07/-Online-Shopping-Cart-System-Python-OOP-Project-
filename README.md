#  🛒 Online Shopping Cart System

A simple command-line-based Python project that simulates a basic online shopping experience. This system allows customers to add products to their shopping cart, apply discounts, view the cart, and checkout.

# 📌 Features

- Add/remove products from the cart  
- Apply discount to specific products  
- View cart contents with subtotal and total  
- Checkout with summary  
- Handles product stock and availability  
- Object-oriented structure with classes: `Product`, `ShoppingCart`, and `Customer`

## 🧩 Project Structure




✅ How to Run

<pre> ```bash python shopping_cart.py ``` </pre>

No setup required – runs directly in terminal or any Python IDE.

👨‍💻 Example Output

``` bash

1 x Laptop added to the cart.
2 x Mouse added to the cart.

Alice's shopping cart:
cart contains
Laptop (ID: P001) -₹60000 | in stock:4 | Quantity: 1 | Subtotal: ₹60000
Mouse (ID: P002) -₹800 | in stock:8 | Quantity: 2 | Subtotal: ₹1600
Total: ₹61600

Alice's Checkout Summary:
cart contains
Laptop (ID: P001) -₹60000 | in stock:4 | Quantity: 1 | Subtotal: ₹60000
Mouse (ID: P002) -₹800 | in stock:8 | Quantity: 2 | Subtotal: ₹1600
Total: ₹61600
Thank you for shopping!
```


🛠️ Technologies Used
Python 3

Object-Oriented Programming (OOP)

📂 Classes Overview
Product: Represents a product with price, stock, and discount capabilities.

ShoppingCart: Handles all cart operations like adding, removing, applying discount, and totaling.

Customer: Represents a customer with a unique cart and checkout process.

📈 Future Enhancements
Add product categories

Save cart to file or database

Add login/signup functionality

GUI version using Tkinter or Web framework

📄 License
This project is open-source and available under the MIT License.






