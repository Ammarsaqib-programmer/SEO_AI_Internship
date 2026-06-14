# SEO_AI_Internship Task 1
## Desi Restaurant Management System

### Student Information
**Name:** Ammar Saqib

---

## Assignment Overview

This project is a Python-based Desi Restaurant Management System developed as part of the AI Internship Assignment.

The program demonstrates the use of:

- Functions
- If-Else Statements
- Loops
- User Input Handling

---

## Tasks Implemented

### Q1. Menu Function
A function that checks the selected menu item and returns the appropriate response.

Supported Items:
- Karhai
- Biryani
- BBQ
- Chai

Unavailable items return:
```
Item not available ❌
```

### Q2. Customer Serving System
A loop is used to serve 5 customers. Each customer's order is processed using the `menu()` function.

### Q3. Karhai Spice System
A function that manages Karhai spice levels:

| Spice Level | Output |
|------------|----------|
| high | Very Spicy Karhai |
| medium | Normal Karhai |
| low | Mild Karhai |
| other | Invalid input |

### Q4. BBQ Platter System
A function that determines BBQ platter size based on the number of pieces.

| Pieces | Output |
|---------|---------|
| 10 or more | Full BBQ Platter |
| 5–9 | Half BBQ Platter |
| Less than 5 | Small BBQ Plate |

### Q5. Chai System
A function that determines chai sweetness level.

| Sugar Level | Output |
|-------------|---------|
| 0 | No Sugar Chai |
| 1 | Normal Chai |
| 2 or more | Sweet Chai |

---

## Final Combined Project

The final restaurant management system:

1. Serves 5 customers.
2. Accepts food orders.
3. Calls the `menu()` function.
4. Handles additional inputs:
   - Spice level for Karhai
   - Number of pieces for BBQ
   - Sugar level for Chai
5. Displays the final result for each customer.

---

## Sample Output

```text
Customer 1
Enter item: biryani
Biryani is ready

Customer 2
Enter item: chai
Enter sugar level: 3
Sweet Chai

Customer 3
Enter item: karhai
Enter spice level: high
Very Spicy Karhai

Customer 4
Enter item: bbq
Enter number of BBQ pieces: 7
Half BBQ Platter

Customer 5
Enter item: burger
Item not available ❌
```

---

## Technologies Used

- Python 3
- Google Colab / Jupyter Notebook
- GitHub

---

## Learning Outcomes

Through this assignment, I learned:

- Creating and calling functions
- Using conditional statements
- Implementing loops
- Handling user input
- Building a simple menu-driven application

---

## Repository Structure

```text
ai-internship-assignment/
│
├── restaurant_system.py
├── README.md
└── assignment.ipynb (optional)
```

---

## Author

**Your Name Here**

AI Internship Assignment – 1
