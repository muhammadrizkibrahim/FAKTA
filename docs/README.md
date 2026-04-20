<div align="center">

# FAKTA
### Fenomena Aktual Terkini

**Agregator & scraper berita berbasis web untuk wilayah Kepulauan Riau**  
Dikembangkan dari [okkymabruri/news-watch](https://github.com/okkymabruri/news-watch)

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://streamlit.io)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

</div>

---

## Tentang Proyek

**FAKTA** adalah pengembangan lanjutan dari proyek [news-watch](https://github.com/okkymabruri/news-watch) oleh okkymabruri, dengan penambahan antarmuka web interaktif menggunakan **Streamlit** dan fokus scraping berita yang diarahkan ke wilayah **Kepulauan Riau**.

Proyek ini memudahkan pemantauan berita terkini dari berbagai media nasional dan lokal secara terpusat, lengkap dengan visualisasi data dan ekspor hasil scraping.

## Fitur

- **Antarmuka web** berbasis Streamlit — mudah digunakan tanpa perlu setup tambahan
- **Scraping berita** dari media nasional dan lokal secara otomatis
- **Filter wilayah** — fokus pada berita yang relevan dengan Kepulauan Riau
- **Pencarian kata kunci** — masukkan topik yang ingin dipantau
- **Visualisasi data** — wordcloud dan grafik tren berita
- **Ekspor CSV** — simpan hasil scraping untuk analisis lebih lanjut

## Tech Stack

| Kategori | Library / Tool |
|----------|---------------|
| Bahasa | Python 3.10+ |
| Web App | Streamlit |
| Scraping | Requests, BeautifulSoup4 |
| Data | Pandas |
| Visualisasi | Matplotlib, Wordcloud |
| Utilitas | Regex, DateTime |

## Sumber Berita

### Media Nasional
- Antaranews
- Kompas
- Detik
- *(dan lainnya)*

### Media Lokal Kepri
- Batamnews
- Tribun Batam
- *(dan lainnya)*

> Semua sumber difilter untuk menampilkan berita yang relevan dengan wilayah **Kepulauan Riau**.

## Instalasi & Menjalankan

```bash
# Clone repositori
git clone https://github.com/<username>/fakta.git
cd fakta

# Buat virtual environment (opsional tapi disarankan)
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependensi
pip install -r requirements.txt

# Jalankan aplikasi
streamlit run app.py
```

Buka browser di `http://localhost:8501`.

## Struktur Proyek

```
fakta/
├── app.py              # Entry point Streamlit
├── scraper/
│   ├── __init__.py
│   └── sources.py      # Logika scraping per sumber
├── utils/
│   └── filter.py       # Filter wilayah Kepri
├── requirements.txt
└── README.md
```

> *Sesuaikan struktur di atas dengan kondisi aktual repositori Anda.*

## Kredit

Proyek ini merupakan pengembangan dari **[okkymabruri/news-watch](https://github.com/okkymabruri/news-watch)**. Terima kasih kepada okkymabruri atas fondasi scraper berita yang digunakan sebagai dasar proyek ini.

## Kontak

**Muhammad Rizki**  
✉️ [muhammadrizky15.mr@gmail.com](mailto:muhammadrizky15.mr@gmail.com)
