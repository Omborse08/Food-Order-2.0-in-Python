# 🍔 Python Food Ordering System

A simple **Command-Line Food Ordering System** built in Python.  
You can browse the menu, place orders, remove items, apply discounts, and save your bill to a file.

---

## 🚀 Features
- 📜 **View Menu** → Shows available food items with prices.
- ➕ **Add Items** → Add food items to your order.
- ❌ **Remove Items** → Remove items from your order by ID.
- 💰 **View Total** → Displays the total bill amount.
- 🎯 **Discount Option** → Apply a 10% discount to the total bill.
- 💾 **Save Bill** → Save your bill details to `BillFile.txt`.
- 📂 **Open Bill File** → Option to open saved bill automatically.
- 📌 **Decorators** → Used to log menu display with clean formatting.
- 🏷 **Inheritance** → Demonstrates subclassing (`dances` inherits from `foodies`).

---

## 🧠 Concepts Used
- **Object-Oriented Programming (OOP)**
  - Classes & Objects
  - Constructor (`__init__`)
  - Inheritance (`dances` → `foodies`)
- **Python Decorators** → For clean section formatting in menu display.
- **File Handling**
  - Create file if it doesn’t exist
  - Write bill details to file
- **Lambda Functions** → For applying discounts.
- **Dictionaries** → For storing menu and orders.
- **Loops & Conditionals** → Menu-driven order system.
- **os module** → Check file existence and open bill file.

---

## 📂 Project Structure
```
Food-Ordering-System/
│
├── main.py          # Main Python program
└── README.md        # Project documentation
```

---

## 📸 Example Output
```
Bill File Created!
=== Welcome to Online Food Ordering System ===

Sr  Name   Price
--------------------------------------------------
1. pizza - ₹250
2. burger - ₹150
3. pasta - ₹200
4. fries - ₹80
--------------------------------------------------
Enter item to add (or 'done' to finish): pizza

> Added To Your Inventory
Enter item to add (or 'done' to finish): done

=== Current Order ===
1. pizza - ₹250
Total Amount: 250
Apply %10 discount? (yes/no): yes

Discounted Offer: ₹225.0
Wanna Save Bill (Yes/No): yes

> Bill Saved Successfully
=== Thank You! Visit Again ===
```

---

## 💻 How to Run
1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/Python-Food-Ordering-System.git
   ```
2. **Navigate into the project folder**:
   ```bash
   cd Python-Food-Ordering-System
   ```
3. **Run the program**:
   ```bash
   python main.py
   ```

---

## 📌 Future Improvements
- Multiple quantity support
- Category-based menu
- Persistent order history
- GUI version using Tkinter or PyQt
