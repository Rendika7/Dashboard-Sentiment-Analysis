# Sentiment Analysis Dashboard ✨

## Setup environment
run in cmd and follow the order
```
python -m venv sentiment
sentiment/Scripts/activate
pip install -r requirements.txt
```

## Run steamlit app
```
streamlit run dashboard.py
```

This is Link to My *[Streamlit Dashboard]()*

## for CSV file Upload requirements

for CSV files, compliance with the columns is required, namely there must be a "Fakultas", "Prodi", "JAWABAN" column.Remember that the case is sensitive. below is an example...

| Fakultas              | Prodi                                | JAWABAN                                                  |
|-----------------------|--------------------------------------|----------------------------------------------------------|
| Teknik Sipil          | Teknik Sipil                         | Peningkatan fasilitas laboratorium akan membantu riset.   |
| Ilmu Komputer         | Sistem Informasi                      | Perlu penambahan buku referensi terbaru di perpustakaan.  |
| Ekonomi               | Manajemen                             | Perlu pembukaan lebih banyak workshop dan seminar.        |
| Kedokteran            | Kedokteran Gigi                       | Perlu peningkatan teknologi di ruang praktikum.           |
| Sastra                 | Sastra Inggris                        | Diperlukan klub sastra untuk pengembangan kreativitas.    |
