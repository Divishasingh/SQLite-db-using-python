# SQLite-db-using-python 
# 📊 Task 7: Sales Summary from SQLite using Python

 The task focuses on extracting sales insights from a tiny SQLite database using SQL within Python, and visualizing the results using Matplotlib.

---

## 📌 Objective

Use SQL inside Python to pull simple sales information (like total quantity sold, total revenue), and display it using print statements and a simple bar chart.

---

## 🧰 Tools & Libraries Used

- **Python** (`sqlite3`, `pandas`, `matplotlib`)
- **SQLite** (embedded in Python)
- **Jupyter Notebook**

---

## 📁 Files in This Repository

| File Name         | Description                                          |
|------------------|------------------------------------------------------|
| `task.ipynb`      | Jupyter Notebook with the complete Python solution  |
| `sales_data.db`   | SQLite database containing the sales data           |
| `sales_chart.png` | Bar chart showing revenue by product (optional but recommended) |
| `README.md`       | This documentation file                             |

---

## 🧾 Task Deliverables

- Connect to a SQLite database (`sales_data.db`)
- Run SQL queries to compute:
  - Total quantity sold by product
  - Total revenue by product
- Load the data into Pandas
- Print summarized data
- Create a basic bar chart (product vs revenue)

---

## ✅ Sample Output

Bar chart:  
**Revenue by Product**  
![Revenue by Product](sales_chart.png)

---

## 🧠 Learning Outcomes

By completing this task, I:

- Learned how to write and execute SQL queries inside Python
- Practiced importing SQL data into Pandas
- Performed simple data summaries
- Created my first sales bar chart using Matplotlib

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/divishasingh/sales-summary-sqlite.git
   cd sales-summary-sqlite
   ```

2. Open `task.ipynb` using Jupyter Notebook or VS Code.

3. Run the notebook to:
   - Connect to the database
   - Execute the SQL queries
   - Generate and save the bar chart

