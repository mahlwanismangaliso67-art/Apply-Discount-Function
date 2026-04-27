💸 Apply Discount Function

📌 Description

This project provides a simple Python function, "apply_discount", that calculates the final price of an item after applying a percentage-based discount.

The function includes input validation to ensure accurate results and returns clear error messages when invalid data is provided.

---

⚙️ Features

- Accepts "price" and "discount" as inputs
- Validates that both inputs are numbers ("int" or "float")
- Ensures "price" is greater than 0
- Ensures "discount" is between 0 and 100
- Calculates and returns the final discounted price
- Returns helpful error messages for invalid input

---

🧠 How It Works

The function follows these steps:

1. Check if "price" is a valid number
2. Check if "discount" is a valid number
3. Validate that "price > 0"
4. Validate that "0 ≤ discount ≤ 100"
5. Calculate the discount amount
6. Return the final price

---

💻 Example Usage

from apply_discount import apply_discount

result = apply_discount(50, 20)
print(result)

✅ Output

40.0

---

📂 Project Structure

apply-discount/
│── apply_discount.py
│── README.md

---

🎯 Purpose

This project is designed for beginners learning Python. It demonstrates:

- Function creation
- Conditional logic ("if" statements)
- Input validation
- Basic arithmetic operations

---

🚀 Future Improvements

- Round results to 2 decimal places (currency format)
- Add user input (CLI version)
- Expand to handle multiple items

---

🧑‍💻 Author

Smangaliso Mahlwani 
