# NumPy & Pandas Data Analysis Practice

This repository contains a hands-on Python notebook exploring the fundamentals of array operations in **NumPy**, basic data manipulation with **Pandas**, and an end-to-end mini case study analyzing e-commerce transactions.

---

## 📌 Overview

The notebook is divided into two primary parts:

### 1. NumPy Fundamentals vs. Native Python
* **Environment Setup:** Checking installed library versions and inspecting module attributes.
* **List vs. Array Behavior:** Comparing list repetition (`list * n`) with vectorized arithmetic (`array * n`).
* **Memory Optimization:** Benchmarking memory usage between Python lists and NumPy arrays using `sys.getsizeof()`, `.size * .itemsize`, and `.__sizeof__()`.
* **Memory Allocation & Mutability:** Exploring variable references, pointers, and shared memory addresses with `id()`.
* **Iteration:** Comparing standard loops across python lists vs. arrays.

### 2. E-Commerce Analytics Case Study
Using a dataset of 10 transaction records with attributes (`transaction_id`, `customer_id`, `product_id`, `quantity`, `unit_price`, `discount_percent`, `shipping_cost`, and `returned`):
* Calculating gross revenue, discount amounts, revenue after shipping, and lost revenue from returns.
* Aggregating total company revenue, average transaction value, and identifying the highest-value sale.
* Analyzing customer metrics (total spend per customer and top 3 spending customers).
* Analyzing product metrics (revenue per product, product return rates, and percentage contribution of each transaction to total revenue).

---

## 📊 Key Analysis Findings

Key metrics generated from the analysis in the notebook include:

* **Total Gross Revenue:** $56,800
* **Average Transaction Value:** $5,680
* **Highest-Value Transaction:** $15,600
* **Revenue Lost to Returned Orders:** $15,050
* **Top 3 Customers by Spending:**
  1. Customer `504` — $15,600
  2. Customer `501` — $13,050
  3. Customer `505` — $12,800
* **Product Return Rates:**
  * Product `102`: 50%
  * Product `103`: 50%
  * Products `101`, `104`, `105`: 0%

---

## 🛠️ Requirements & How to Run

### Requirements
To run this notebook locally, ensure you have Python installed along with the required packages:

```bash
pip install numpy pandas
```

### Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
   ```
2. Open the notebook using Jupyter Notebook, JupyterLab, or VS Code:
   ```bash
   jupyter notebook numpy_tasks.ipynb
   ```

---

## 💡 Key Takeaways

* **Vectorization:** Performing mathematical operations directly on NumPy arrays/Pandas series is more efficient and readable than iterating over standard Python lists.
* **Memory Structure:** NumPy arrays consume less memory than Python lists for numeric data. `.__sizeof__()` accounts for structural metadata, whereas `.size * .itemsize` measures raw element storage.
* **Reference Assignment:** Assigning an array variable to a new variable (`arr_b = arr_a`) copies the memory reference rather than the data itself.