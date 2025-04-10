# 📊 RFM-Analysis-for-Customer-Segmentation-Python-


## 📌 Overview  
This project performs **RFM (Recency, Frequency, Monetary)** analysis on a transactional dataset to segment customers based on their purchasing behavior. RFM analysis helps businesses identify their most valuable customers and design effective, data-driven marketing strategies.

---

## 📁 Dataset Columns  
- **Invoice**: Unique identifier for each transaction  
- **StockCode**: Product identifier  
- **Description**: Name of the product  
- **Quantity**: Number of units purchased  
- **InvoiceDate**: Date and time of the transaction  
- **Price**: Price per unit  
- **Customer ID**: Unique identifier for each customer  
- **Country**: Country of the customer

---

## 🔢 RFM Calculation

The RFM analysis is based on three core metrics:

1. **Recency (R)**: Days since the customer's last purchase  
2. **Frequency (F)**: Number of transactions made by the customer  
3. **Monetary (M)**: Total amount spent by the customer

### 📐 Scoring Formula  
```python
RFM Score = (0.2 * Recency Score) + (0.25 * Frequency Score) + (0.5 * Monetary Score)
```

---

## ⚙️ Installation & Usage

### 📦 Requirements
- Python 3.x  
- pandas  
- numpy  
- matplotlib  
- seaborn

### 🚀 Run the Project

1. **Clone the repository**  
```bash
git clone https://github.com/xalizade/RFM-Analysis-for-Customer-Segmentation-Python.git
cd RFM-Analysis-for-Customer-Segmentation-Python
```

2. **Install dependencies**  
```bash
pip install -r requirements.txt
```

3. **Run the script**  
```bash
python final_project1.py
```

---

## 📤 Output

- Processed RFM table with customer scores  
- Customer segmentation based on RFM scores  
- Visualizations showing RFM score distribution

---

## 👥 Customer Segments

| Segment                | Description                                      |
|------------------------|--------------------------------------------------|
| **Best Customers**     | Highest RFM scores, frequent and high spenders   |
| **Loyal Customers**    | Repeat buyers with significant spending          |
| **Potential Loyalists**| New or moderately engaged customers              |
| **At Risk**            | Previously active, now inactive                  |
| **Lost Customers**     | Haven’t purchased in a long time                 |

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo, submit a pull request, or open an issue for suggestions and improvements.

---

