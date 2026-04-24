🛒 Amazon Cart App
📌 Overview

The Amazon Cart App is a console-based (or extendable GUI) application that simulates the core functionality of an e-commerce shopping cart similar to Amazon. It allows users to browse products, add/remove items, manage quantities, and calculate total costs.

This project is designed to demonstrate key programming concepts such as object-oriented design, data structures, and user interaction.

🚀 Features
🧾 Product Catalog
Displays a list of available products
Each product includes:
Unique ID
Name
Price
Easily expandable for additional products
➕ Add to Cart
Add items using Product ID
Supports multiple quantities
Automatically updates cart contents
➖ Remove from Cart
Remove specific items from the cart
Option to remove all quantities of an item
Handles invalid product IDs gracefully
🔄 Update Item Quantity
Increase or decrease item quantity
Prevents negative or invalid values
Updates total price dynamically
🛍️ View Cart
Displays all cart items including:
Product name
Quantity
Price per item
Subtotal per item
💰 Checkout System
Calculates:
Total price of items
Optional tax (if implemented)
Final checkout total
Provides a clear purchase summary
🧹 Clear Cart
Removes all items from the cart instantly
🧠 Concepts Used
Object-Oriented Programming (OOP)
Classes & Objects
Arrays / ArrayLists
HashMaps (for efficient lookups)
Loops & Conditionals
User Input Handling
Modular Method Design
📂 Project Structure
AmazonCartApp/
│
├── Main.java # Application entry point
├── Product.java # Defines product attributes
├── Cart.java # Handles cart operations
├── CartItem.java # Represents items inside the cart
└── README.md # Project documentation
🛠️ How It Works
The application starts and displays a menu
The user selects an action:
View products
Add item to cart
Remove item
Update quantity
View cart
Checkout
The cart updates in real time
At checkout, the total cost is calculated and displayed
▶️ Example Usage
Welcome to Amazon Cart App!

View Products
Add to Cart
Remove from Cart
View Cart
Checkout
Exit
Enter your choice: 2
Enter Product ID: 101
Enter Quantity: 2

Item added to cart successfully!
⚙️ Installation & Setup

Clone the Repository
git clone https://github.com/yourusername/amazon-cart-app.git
Open Project
Open the project in your preferred IDE (e.g., IntelliJ IDEA, Eclipse, VS Code)
Run the Application
Run Main.java to start the program
🔮 Future Enhancements
GUI interface (JavaFX / Swing)
User login and authentication
Persistent cart (file or database storage)
Product search and filtering
Discount codes and promotions
Payment integration simulation
