# Dashboard Penjualan & Profitabilitas Retail 2023-2024

**Personal Practice Project** | Tableau Public | 2026

Dashboard interaktif untuk menganalisis performa penjualan dan profitabilitas bisnis retail berdasarkan kategori produk, wilayah, dan tren waktu.

---

## 📊 Live Dashboard

- **Dashboard Penjualan Retail**: [Lihat Dashboard](https://public.tableau.com/app/profile/vezan.hidayatullah/viz/Dashboard_Penjualan_Retail_Tableau/FIXDashboardPenjualanRetail2023-2024)
- **Dashboard Analisis Profitabilitas**: [Lihat Dashboard](https://public.tableau.com/app/profile/vezan.hidayatullah/viz/Dashboard_Penjualan_Retail_Tableau/FIXDashboardProfitabilitas)

---

## 📁 Tentang Project

Project ini merupakan latihan pribadi untuk mengasah kemampuan analisis data dan visualisasi menggunakan Tableau. Data yang digunakan adalah dataset penjualan retail dummy yang mencakup 300 transaksi dari tahun 2023–2024 dengan 5 kategori produk dan 4 wilayah di Indonesia.

---

## 📂 Struktur Repository

```
retail-sales-dashboard-tableau/
├── data/
│   └── Dataset_Penjualan_Retail.xlsx
│   └── Data Penjualan (Dataset_Penjualan_Retail).hyper
├── dashboard/
│   ├── Dashboard_Penjualan_Retail_Tableau2.twb
└── README.md
```

---

## 📋 Dataset

| Kolom | Deskripsi |
|---|---|
| ID Transaksi | ID unik setiap transaksi |
| Tanggal | Tanggal transaksi (2023–2024) |
| Nama Pelanggan | Nama pelanggan |
| Kategori | Elektronik, Furnitur, Makanan, Olahraga, Pakaian |
| Produk | Nama produk spesifik |
| Wilayah | Jawa, Sumatera, Kalimantan, Sulawesi |
| Kota | Kota tempat transaksi |
| Sales | Total penjualan (Rp) |
| Quantity | Jumlah item terjual |
| Diskon | Persentase diskon |
| Profit | Keuntungan (Rp) |

---

## 🎯 Fitur Dashboard

### Dashboard Penjualan Retail
- **Bar Chart** — Total Sales per Kategori Produk
- **Line Chart** — Tren Penjualan Bulanan (dengan garis rata-rata)
- **Pie Chart** — Distribusi Sales per Wilayah
- **Treemap** — Top Produk Berdasarkan Sales
- **Filter Interaktif** — Wilayah, Kategori, dan Rentang Tanggal
- **Action Filter** — Klik wilayah di pie chart untuk filter semua chart

### Dashboard Analisis Profitabilitas
- **Bar Chart** — Profit per Wilayah
- **Bar Chart** — Profit Margin % per Kategori (menggunakan Calculated Field)
- **Bar Chart** — Distribusi Status Profit (Tinggi/Sedang/Rendah)
- **Filter Interaktif** — Wilayah
- **Action Filter** — Klik wilayah untuk filter semua chart

---

## 🔍 Key Findings

**Penjualan:**
- **Elektronik** mendominasi total sales dengan Rp1,25 Miliar
- **Sulawesi** menjadi wilayah dengan kontribusi sales terbesar
- **Laptop** menjadi produk dengan sales tertinggi mencapai Rp635 Juta
- Penjualan mencapai puncak di bulan **Mei** pada tahun kedua

**Profitabilitas:**
- **Furnitur** memiliki profit margin tertinggi (24,55%) meski bukan kategori dengan sales terbesar
- **Elektronik** memiliki profit margin terendah (19,70%) meskipun dominan di sales
- **Sulawesi** menghasilkan profit terbesar (Rp149 Juta)
- **221 dari 300 transaksi** (73,7%) masuk kategori Profit Rendah (<Rp1 Juta)

---

## 🛠️ Tech Stack

- **Tableau Public** — Visualisasi & Dashboard
- **Microsoft Excel** — Dataset

---

## 💡 Teknik Tableau yang Digunakan

- Calculated Field (Profit Margin %, Status Profit dengan IF/ELSEIF)
- Action Filter (interaktivitas antar chart)
- Filter Dashboard (Dropdown, Checkbox, Date Slider)
- Reference Line (Average Line di Line Chart)
- Multiple Chart Types (Bar, Line, Pie, Treemap)

---

## 📸 Screenshot

### Dashboard Penjualan Retail 2023-2024
<img width="677" height="382" alt="image" src="https://github.com/user-attachments/assets/2c4073f3-f85e-42a7-8e6b-b1ea89a75519" />

### Dashboard Analisis Profitabilitas 2023-2024
<img width="682" height="383" alt="image" src="https://github.com/user-attachments/assets/dc61e6d7-b697-49c8-bd74-4edf786ee2fd" />

---

## 👤 Author

**Vezan Hidayatullah**









# Retail Sales Dashboard

**Personal Practice Project** | Tableau Public | 2026

Dashboard analisis penjualan retail yang menampilkan performa penjualan dan profitabilitas produk.

### Fitur Dashboard
- **Dashboard Penjualan Retail**: Overview total sales, quantity, dan performa per wilayah
- **Dashboard Profitabilitas**: Analisis profit dan margin per kategori produk
- Filter interaktif berdasarkan wilayah, kategori produk, dan periode waktu

### Tech Stack
- **Tableau Public** (Visualisasi & Dashboard)
- Microsoft Excel (Data Preparation)

### Links
- **Dashboard Penjualan Retail**: [Lihat Dashboard](https://public.tableau.com/app/profile/vezan.hidayatullah/viz/Dashboard_Penjualan_Retail_Tableau/FIXDashboardPenjualanRetail2023-2024)
- **Dashboard Profitabilitas**: [Lihat Dashboard](https://public.tableau.com/app/profile/vezan.hidayatullah/viz/Dashboard_Penjualan_Retail_Tableau/FIXDashboardProfitabilitas)

### Screenshot







---

### Tentang Project
Project latihan pribadi untuk mengasah kemampuan Tableau dalam mengolah dan memvisualisasikan data penjualan retail dummy.
