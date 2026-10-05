# 🛒 E-Commerce Checkout System (Java)

A console-based e-commerce checkout system developed in **pure Java** using Object-Oriented Programming (OOP). Inspired by the Fawry Rise internship challenge, the project simulates a basic e-commerce checkout workflow, including product management, shopping cart operations, shipping fee calculation, customer balance validation, and receipt generation.

## ✨ Features

* **Product management:** Supports expirable, non-expirable, shippable, and shippable-expirable products.
* **Shopping cart:** Adds products with quantity validation based on available stock.
* **Checkout process:** Validates cart contents, calculates the subtotal and shipping fees, checks the customer's balance, and updates inventory and balance after successful payment.
* **Shipping service:** Collects shippable items, displays shipment details, and calculates shipping fees based on package weight, at a rate of 30 per kg.
* **Error handling:** Handles empty carts, insufficient stock, expired products, and insufficient customer balance.
* **Receipt generation:** Prints an itemized receipt with the subtotal, shipping fees, total amount, and remaining customer balance.

## 🧱 OOP Concepts

* **Abstraction:** Defines common product behavior through an abstract base class.
* **Inheritance:** Extends product types to represent different product properties.
* **Polymorphism:** Handles different product types through shared abstractions.
* **Interfaces:** Defines a common contract for products that require shipping.
* **Encapsulation:** Manages product data, cart operations, and customer balance through dedicated classes.

## 🛠️ Technologies

* Java
* Object-Oriented Programming (OOP)
* Java Collections
* Exception Handling
* Console-based application

## 🚀 Getting Started

**Requirements:** JDK 11 or later.

```bash
git clone https://github.com/Shahdrabea2004/Ecommerce-Checkout-System.git
cd Ecommerce-Checkout-Java
javac -d out src/*.java
java -cp out Main
```

Alternatively, open the project in IntelliJ IDEA and run the `Main` class.

## 📄 Sample Output

```text
** Shipment notice **
2x Cheese 800.0g
1x Biscuits 700.0g
3x TV 30000.0g
Total package weight: 31.5 kg

** Checkout receipt **
2x Cheese 200.0
1x Biscuits 150.0
3x TV 900.0
1x ScratchCard 50.0
----------------------
Subtotal 1300.0
Shipping 945.0
Amount 2245.0
Customer Balance After Payment: 755.0
```

## 🎯 Learning Outcomes

Built as an early Java learning project to practice applying OOP principles, designing classes and interfaces, managing object relationships, validating business rules, and implementing a complete checkout workflow.

## 👩‍💻 Author

**Shahd Rabea**
