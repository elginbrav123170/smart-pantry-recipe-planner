# Smart Pantry & Recipe Planner

Proyek Besar Praktikum Algoritma dan Struktur Data, Kelompok KOCAK.

## Cara menjalankan

```
python -m venv .venv
.venv\Scripts\activate        # Windows
source .venv/bin/activate     # Mac/Linux
pip install -r requirements.txt
streamlit run app.py
```

API key Gemini: salin `.streamlit/secrets.toml.example` menjadi `.streamlit/secrets.toml`, lalu isi key-nya. File itu tidak ikut di-commit.

## Pembagian file

| File | Pemilik |
|---|---|
| app.py, api.py, ui_cari.py, ui_hasil.py | Brilly |
| cache.py, matching.py, sorting.py, history.py, tests/ | Raffiel |
| charts.py, export.py, ai_chef.py, data_contoh.py | Elgin |
