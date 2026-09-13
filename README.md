# Simple Data Automation with Python

## 📌 Project Overview

**Simple Data Automation** adalah project Python sederhana untuk mengotomatisasi proses pengolahan data penjualan.

Program membaca data penjualan, menghitung omzet, membuat ringkasan penjualan, mencari produk terlaris, kemudian menghasilkan beberapa file laporan secara otomatis.

Project ini dibuat sebagai bagian dari portfolio **Data Processing & Automation**.

---

## 🎯 Project Objective

Tujuan project ini adalah membuat proses pengolahan data yang sebelumnya dilakukan secara manual menjadi lebih otomatis menggunakan Python.

Program dapat:

* Mengolah data penjualan
* Menghitung omzet
* Menghitung total transaksi
* Menghitung total produk terjual
* Menentukan produk terlaris
* Membuat laporan otomatis
* Menyimpan hasil analisis ke file CSV

---

## ⚙️ Features

### 1. Automatic Data Processing

Program menggunakan **Pandas** untuk membuat dan mengolah data penjualan.

Data terdiri dari:

* Produk
* Jumlah
* Harga

Kemudian program menghitung:

```text
Omzet = Jumlah × Harga
```

---

### 2. Automatic Sales Calculation

Program menghitung secara otomatis:

* Total transaksi
* Total produk terjual
* Total omzet

Contoh hasil:

```text
Total Transaksi : 5
Total Produk    : 21 unit
Total Omzet     : Rp 10,200,000
```

---

### 3. Best-Selling Product Detection

Program mengelompokkan jumlah penjualan berdasarkan produk dan secara otomatis mencari produk dengan jumlah penjualan terbesar.

Contoh:

```text
Produk Terlaris : Kursi Besi
Jumlah Terjual  : 12 unit
```

---

### 4. Automatic Report Generation

Program menghasilkan file:

```text
report.txt
```

File tersebut berisi ringkasan hasil analisis penjualan.

---

### 5. Automatic CSV Output

Program juga menghasilkan:

```text
sales_data.csv
```

File ini berisi data penjualan yang sudah dilengkapi dengan kolom omzet.

Selain itu, program menghasilkan:

```text
sales_summary.csv
```

yang berisi ringkasan hasil analisis.

---

## 🔄 Automation Workflow

Proses automation:

```text
Sales Data
    ↓
Python + Pandas
    ↓
Data Processing
    ↓
Calculate Sales
    ↓
Find Best-Selling Product
    ↓
Generate Reports
    ↓
CSV + TXT Output
```

Dengan workflow tersebut, proses perhitungan dan pembuatan laporan dapat dilakukan secara otomatis.

---

## 🗂️ Project Structure

```text
simple-data-automation/
│
├── automation.py
├── sales_data.csv
├── sales_summary.csv
└── report.txt
```

### File Description

| File                | Description                                |
| ------------------- | ------------------------------------------ |
| `automation.py`     | Program utama Python                       |
| `sales_data.csv`    | Data penjualan dan hasil perhitungan omzet |
| `sales_summary.csv` | Ringkasan hasil analisis                   |
| `report.txt`        | Laporan penjualan dalam format teks        |

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Google Colab
* CSV
* TXT
* Data Processing
* Basic Automation

---

## 🧮 Main Python Concepts

Project ini menggunakan beberapa konsep Python:

### Pandas DataFrame

Digunakan untuk membuat dan mengolah data.

```python
df = pd.DataFrame(data)
```

### Perhitungan Kolom

```python
df["Omzet"] = df["Jumlah"] * df["Harga"]
```

### Grouping Data

```python
df.groupby("Produk")["Jumlah"].sum()
```

### Mencari Nilai Terbesar

```python
.idxmax()
```

### Membuat File

```python
with open("report.txt", "w") as file:
    file.write(laporan)
```

### Export CSV

```python
df.to_csv("sales_data.csv", index=False)
```

---

## 📊 Example Result

Berdasarkan sample data yang digunakan:

| Metric                |        Result |
| --------------------- | ------------: |
| Total Transactions    |             5 |
| Total Products Sold   |      21 units |
| Total Revenue         | Rp 10,200,000 |
| Best-Selling Product  |    Kursi Besi |
| Best-Selling Quantity |      12 units |

---

## 💡 Skills Demonstrated

Project ini menunjukkan kemampuan dasar dalam:

* Python Programming
* Pandas
* Data Processing
* Data Analysis
* CSV Processing
* Report Generation
* Basic Automation
* Problem Solving
* Data Management

---

## 🚀 Future Improvements

Project ini masih merupakan automation sederhana dan dapat dikembangkan menjadi sistem yang lebih lengkap.

Pengembangan berikutnya dapat mencakup:

* Membaca data langsung dari file CSV eksternal
* Menggunakan input data baru secara otomatis
* Membuat grafik penjualan
* Menghasilkan laporan Excel
* Menghasilkan laporan PDF
* Menambahkan dashboard
* Mengirim laporan otomatis melalui email
* Menghubungkan Python dengan Google Sheets
* Menjadwalkan proses automation

---

## 📌 Project Status

**Completed — Portfolio Project**

Project ini dibuat sebagai bagian dari pembelajaran dan pengembangan portfolio di bidang **Data Processing, Python, dan Automation**.

---

## 👤 Author

**Saripudin**

Aspiring Data & Automation Professional

**Skills:**
Python • Data Processing • Google Sheets • Automation

**Open to Remote Opportunities**
