# MealOrderSystem
Here's a well-structured `README.md` for your **Terminal-Based Restaurant Billing System** using pastel UI and `rich` library:

---

# 🍽️ Terminal Restaurant Billing System

A beautifully styled, terminal-based food ordering and billing application for restaurants, cafes, or food stalls — built in Python with `rich` UI for visually appealing menus and reports.

---

## 📋 Features

* 📦 **Menu Categories**: Foods, Drinks, and Other Services
* 🎨 **Rich UI**: Stylish layout with colors, panels, and tables
* 💸 **Auto Discounts**:

  * 5% on orders above RM 200
  * 10% on orders above RM 1000
  * 15% on orders above RM 5000
* 🧾 **Receipt Generation**: Saved to file with date and time
* 📁 **File-Based Data**: Items and past reports saved in local text files
* 🔁 **Looping Menus**: Navigate seamlessly between menus

---

## 🖥️ Screenshots

> You can attach terminal screenshots showing:

* Main menu in colored panel
* Foods & Drinks table with prices
* Sample receipt with discount

---

## 📂 Project Structure

```
restaurant_billing/
├── files/
│   ├── list_foods.fsd
│   ├── list_drinks.fsd
│   ├── list_services.fsd
│   └── report.fsd
├── restaurant_billing.py
└── README.md
```

---

## 📥 Setup Instructions

1. **Clone this repo** or copy the code:

   ```bash
   git clone <your-repo-url>
   cd restaurant_billing
   ```

2. **Install required package**:

   ```bash
   pip install rich
   ```

3. **Prepare item lists** in the `files/` folder:

   * `list_foods.fsd`, `list_drinks.fsd`, `list_services.fsd`
   * Format: `Item Name RM price` (e.g., `Burger RM 15.00`)

4. **Run the program**:

   ```bash
   python restaurant_billing.py
   ```



## ✏️ Sample Data Files

### `list_foods.fsd`

Burger RM 15.00
Fries RM 8.00
Pizza RM 22.00

### `list_drinks.fsd`


Cola RM 5.00
Juice RM 6.50
Water RM 3.00


### `list_services.fsd`


Home Delivery RM 10.00
Table Reservation RM 5.00



## ✅ Future Improvements (Ideas)

* GUI version with Tkinter or PyQt
* Export receipts as PDF
* Login system for admin reports
* SQL or JSON backend support
* Responsive CLI for mobile terminals



## 📜 License

MIT License — Feel free to use, modify, and share.




