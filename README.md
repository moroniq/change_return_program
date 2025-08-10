# Change Return Program 💰

This Python script calculates the change to be returned to the customer after a purchase and breaks it down into specific coin denominations used in Poland.

## 📌 How it works

1. The user enters:
   - the cost of the purchase (in PLN, whole number)
   - the amount of money given (in PLN, can be decimal)
2. The program checks:
   - if the amount given is less than the cost → shows an error message
3. If valid, the program:
   - calculates the change
   - determines the number of coins for each denomination:
     - 5 PLN, 2 PLN, 1 PLN
     - 50 gr, 20 gr, 10 gr, 5 gr, 2 gr, 1 gr
   - displays both the list of coins and the count for each denomination

---

## 💬 Example interaction

Enter a cost in PLN: 17
Enter the amount of money given in PLN: 20
Coin 2 PLN, will be given back 1.0 times.
Coin 1 PLN, will be given back 1.0 times.

---

## 🛠 Technologies used

- Python 3
- `while` loop and `for` loop
- `try`/`except` for input validation
- Conditional statements and list iteration

---

## 🧠 What this project demonstrates

- Handling user input
- Performing calculations using floating point numbers
- Implementing conditional logic and loop-based refactoring
- Presenting results in a user-friendly way

---

## 📜 History of changes

**Commit 1** – *Initial detailed version*:  
- Step-by-step `elif` structure for each coin denomination  
- Explicit counting for each coin  
- Very verbose but clear structure

**Commit 2** – *Refactored shorter version*:  
- Replaced 9 `elif` blocks with a single loop over a list of coin denominations  
- Simplified logic  
- Kept the same functionality while reducing code size significantly

---

Created with 💡 by Olga
