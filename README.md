# Smart Billing and Discount Calculator

A simple Python command-line application that calculates a customer's total purchase amount, applies a discount based on the purchase value, and displays the final bill.

## Features

- Accepts the customer's name
- Accepts the price of a product and quantity purchased
- Calculates the total purchase amount
- Applies discounts automatically:
  - 20% when the total is Rs. 5,000 or more
  - 15% when the total is Rs. 3,000–4,999.99
  - 10% when the total is Rs. 1,000–2,999.99
  - No discount when the total is below Rs. 1,000
- Displays a formatted customer bill

## Requirements

- Python 3

No external Python packages are required.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/abhikumarray1-afk/Smart-billing-and-discount-calculator-.git
cd Smart-billing-and-discount-calculator-
```

### 2. Run the program

```bash
python Code
```

> On some systems, use `python3 Code` instead.

## Example

```text
===== SMART BILL AND DISCOUNT CALCULATOR =====
Enter customer name: Rahul
Enter price of product: 1200
Enter quantity: 3

========== CUSTOMER BILL ==========
Customer Name: Rahul
Price per item: Rs. 1200.0
Quantity: 3
Total Amount: Rs. 3600.0
Discount: Rs. 540.0
Final Bill: Rs. 3060.0
===================================
Thank you for shopping!
```

## How It Works

1. The program reads the customer name, item price, and quantity.
2. It calculates the total with `price × quantity`.
3. It selects a discount based on the total amount.
4. It subtracts the discount from the total to produce the final bill.
5. It prints the complete bill in the terminal.

## Discount Table

| Total Purchase Amount | Discount |
|---|---:|
| Below Rs. 1,000 | 0% |
| Rs. 1,000 – Rs. 2,999.99 | 10% |
| Rs. 3,000 – Rs. 4,999.99 | 15% |
| Rs. 5,000 and above | 20% |

## Project Structure

```text
.
├── Code
└── README.md
```

## Author

[abhikumarray1-afk](https://github.com/abhikumarray1-afk)

## License

No license has been specified for this project.
