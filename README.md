# 🧠 SKYLEARN

**SKYLEARN** adalah proyek komprehensif untuk analisis dan pemrosesan citra satelit sekolah di Indonesia menggunakan pendekatan *Machine Learning* dan *Deep Learning*.  
Proyek ini dibagi menjadi beberapa modul yang saling terhubung — mulai dari scraping data, ekstraksi fitur citra satelit, hingga analisis clustering, klasifikasi, dan deployment model.

---

## 📦 Daftar Repository Modul

| Modul | Deskripsi | Link Repo |
|-------|------------|-----------|
| 🏫 **Scraping Data Sekolah** | Mengambil data sekolah (nama, lokasi, koordinat, dsb.) dari sumber daring untuk digunakan sebagai referensi utama. | [🔗 scraping-data-sekolah](https://github.com/username/scraping-data-sekolah) |
| 🛰️ **Scraping Citra Satelit** | Mengambil citra satelit sekolah berdasarkan koordinat dari data sekolah menggunakan API peta (Google/Mapbox). | [🔗 scraping-citra-satelit](https://github.com/username/scraping-citra-satelit) |
| 🧩 **Clustering Citra Satelit** | Melakukan ekstraksi fitur, reduksi dimensi (PCA), dan clustering (K-Means, DBSCAN) untuk menemukan pola visual antar sekolah. | [🔗 clustering-citra-satelit](https://github.com/username/clustering-citra-satelit) |
| 🔍 **Klasifikasi (On Going)** | Pengembangan model klasifikasi berbasis CNN untuk mendeteksi kategori sekolah berdasarkan citra satelit. | 🚧 *sedang dikembangkan...* |
| ☁️ **Deployment (On Going)** | Integrasi model ke dalam aplikasi web interaktif berbasis Flask/FastAPI untuk inference real-time. | 🚧 *sedang dikembangkan...* |

---

## 🧩 Arsitektur Umum

```
Data Sekolah → Scraping Citra → Feature Extraction → Clustering → Klasifikasi → Deployment
```


---

## 📅 Roadmap Singkat

Lihat detail rencana pengembangan di [📘 docs/roadmap.md](docs/roadmap.md)

---

## 👩‍💻 Tim Pengembang

- **Sabrina Aziz Aulia** – Lead Researcher & Developer  
  Fokus: Deep Learning, Computer Vision, dan Time Series Forecasting

---

## 🧠 Lisensi

Proyek ini dirilis di bawah lisensi **MIT**.