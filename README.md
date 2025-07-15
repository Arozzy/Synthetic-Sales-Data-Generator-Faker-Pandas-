This Jupyter Notebook uses the Faker library to generate a synthetic dataset of 2,000 sales transactions, ideal for testing dashboards, running analytics, or teaching machine learning workflows without using real customer data.

| Column Name            | Description                                 |
| ---------------------- | ------------------------------------------- |
| `Order ID`             | Unique identifier for each transaction      |
| `Order Date`           | Random date from this year                  |
| `Product`              | Product category (Laptop, Smartphone, etc.) |
| `Sales Channel`        | Channel type: Online, Retail, or Wholesale  |
| `Quantity`             | Number of units sold                        |
| `Unit Price`           | Price per unit based on product type        |
| `Competitor Price`     | Competitor’s comparable product price       |
| `Revenue`              | Total sales value (`Unit Price * Quantity`) |
| `Cost`                 | Randomly 10–30% of revenue                  |
| `Cost Centre`          | Assigned department (Sales, R\&D, etc.)     |
| `Sales Representative` | Fake employee responsible for the sale      |
| `Ad Spend`             | Advertising budget spent on the transaction |
| `Region`               | Region in the UK (e.g., London, Glasgow)    |
| `Discount (%)`         | Percentage discount applied (0–15%)         |

