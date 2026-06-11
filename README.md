# 🛒 Olist E-Commerce Sales Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> Analisis dataset e-commerce publik Olist Brazil menggunakan Python untuk data cleaning & EDA, 
> lalu divisualisasikan ke dalam interactive dashboard Power BI.

---

## 📌 Problem Statement

Platform e-commerce menghadapi tantangan dalam memantau performa penjualan, memahami perilaku pelanggan, dan mengidentifikasi faktor yang mempengaruhi kepuasan pelanggan. Project ini bertujuan menjawab pertanyaan bisnis berikut:

- Bagaimana tren revenue bulanan dari 2016 hingga 2018?
- Kategori produk apa yang menghasilkan revenue tertinggi?
- Seberapa besar dampak keterlambatan pengiriman terhadap kepuasan pelanggan?
- Bagaimana distribusi review score pelanggan?

---

## 📊 Dashboard Preview

<img width="1305" height="716" alt="image" src="https://github.com/user-attachments/assets/ec257ec3-c776-470f-b8a6-a69b4f674ebc" />


---

## 🔍 Key Insights & Recommendations

| Insight | Data | Rekomendasi |
|---|---|---|
| Keterlambatan pengiriman menurunkan kepuasan | Review score turun dari 4.21 → 2.55 (↓40%) | Identifikasi seller & region dengan keterlambatan tertinggi, evaluasi estimasi delivery time |
| Health & Beauty adalah kategori revenue #1 | Revenue > R$1.27M, jauh di atas kategori lain | Fokuskan budget promosi & rekrut lebih banyak seller di kategori ini |
| Peak penjualan terjadi November 2017 | Revenue ~R$1.05M, tertinggi sepanjang periode | Siapkan stok & kapasitas logistik sebelum November (Black Friday Brazil) |
| Pertumbuhan revenue sangat pesat | 2016: R$51K → 2018: R$7.67M (~15x dalam 2 tahun) | Investasi infrastruktur logistik sebelum demand tumbuh lebih besar |

---

## 📁 Dataset

- **Sumber:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Periode:** September 2016 – Oktober 2018
- **Ukuran:** 9 file CSV, 99,441 orders, 52 kolom

| File | Deskripsi |
|---|---|
| olist_orders_dataset.csv | Data pesanan utama |
| olist_customers_dataset.csv | Data pelanggan |
| olist_order_items_dataset.csv | Item per pesanan |
| olist_order_payments_dataset.csv | Metode & nilai pembayaran |
| olist_order_reviews_dataset.csv | Review pelanggan |
| olist_products_dataset.csv | Data produk |
| olist_sellers_dataset.csv | Data seller |

---

## 🛠️ Tools & Tech Stack

| Tools | Kegunaan |
|---|---|
| Python (Pandas, Matplotlib, Seaborn) | Data cleaning & Exploratory Data Analysis |
| Google Colab | Environment notebook |
| Power BI + DAX | Interactive dashboard & visualisasi |

---

## 🔄 Metodologi

```
Raw Data (9 CSV)
      ↓
Data Cleaning (Python)
- Konversi tipe data datetime
- Handle missing values
- Feature engineering (delivery_days, is_late, year_month)
      ↓
Exploratory Data Analysis (Python)
- Revenue trend analysis
- Category performance
- Delivery time analysis
- Review score analysis
      ↓
Export Clean Data (CSV)
      ↓
Interactive Dashboard (Power BI)
- 4 KPI Cards
- Monthly Revenue Trend
- Top 10 Categories by Revenue
- On-time Delivery Rate
- Review Score Distribution
```

---

## 📈 Summary Statistik

| Metrik | Nilai |
|---|---|
| Total Orders | 99,441 |
| Total Revenue | R$ 14,270,000 |
| Total Customers | 96,096 |
| Total Sellers | 3,095 |
| Avg Review Score | 4.02 / 5.00 |
| On-time Delivery Rate | 92.13% |
| Avg Delivery Time | 12 hari |
| Periode Data | Sep 2016 – Okt 2018 |

---

## 📂 Struktur Repository

```
olist-ecommerce-dashboard/
├── notebook/
│   └── olist_analysis.ipynb       # Notebook Python lengkap
├── dashboard_screenshot.png        # Screenshot Power BI dashboard
└── README.md                       # Dokumentasi project
```

---

## 👤 Author

**Muhammad Alvino**  
Fresh Graduate · Teknik Informatika · Telkom University  
📧 aalvinoo@student.telkomuniversity.ac.id  
🔗 [LinkedIn](www.linkedin.com/in/muhammad-alvino-45a845211) · [GitHub](https://github.com/ALVNOO)
