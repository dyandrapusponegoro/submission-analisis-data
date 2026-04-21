# 🌫️ Beijing Air Quality Analysis Dashboard

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=flat-square&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.38.0-red?style=flat-square&logo=streamlit)
![Pandas](https://img.shields.io/badge/Pandas-2.2.2-green?style=flat-square&logo=pandas)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)

## 📋 Deskripsi Proyek
Proyek ini merupakan analisis mendalam terhadap kualitas udara di Beijing 
menggunakan dataset dari 12 stasiun pemantauan selama periode 2013–2017. 
Analisis mencakup eksplorasi pola polusi PM2.5, pengaruh kondisi cuaca, 
serta pengelompokan stasiun berdasarkan profil polusinya. Hasil analisis 
disajikan dalam bentuk dashboard interaktif menggunakan Streamlit.

---

## 🔗 Link Penting
| Deskripsi | Link |
|-----------|------|
| 📓 Notebook Analisis | [notebook.ipynb](./notebook.ipynb) |
| 📦 Dataset Sumber | [GitHub marceloreis/HTI](https://github.com/marceloreis/HTI) |

---

## 📂 Struktur Direktori
```bash
submission/
├── dashboard/
│   ├── dashboard.py
│   └── main_data.csv
├── notebook.ipynb
├── requirements.txt
└── README.md
```

---

## 🚀 Panduan Menjalankan Aplikasi

### Clone Repositori
Langkah pertama, unduh proyek ini ke komputer lokal Anda 
menggunakan perintah berikut:
```
git clone https://github.com/[username]/submission-analisis-data.git
```

### Instalasi Library
Instal semua dependensi yang dibutuhkan menggunakan pip
```
pip install -r requirements.txt
```

### Menjalankan Dashboard
Jalankan perintah berikut pada terminal di dalam direktori proyek:
```
streamlit run dashboard/dashboard.py
```
atau
```
python -m streamlit run dashboard/dashboard.py
```
Aplikasi akan secara otomatis terbuka di browser default Anda.

---

## 👤 Author

| | |
|--|--|
| **Nama** | Diandra Puspo Negoro |
| **Email** | dyandrapusponegoro@gmail.com |
| **ID Dicoding** | pediiiasure |
