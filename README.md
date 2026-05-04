# 📊 Modul Simulasi Diagram Bode — Sistem Kontrol

Modul pembelajaran interaktif **Diagram Bode** untuk mahasiswa Sarjana Teknik Elektro. Mencakup teori, simulasi Python, tugas terstruktur, dan visualisasi interaktif berbasis web.

---

## 🚀 Buka di Google Colab

| File | Colab |
|------|-------|
| Modul Pembelajaran | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/username/Modul_Bode_Diagram/blob/main/bode_diagram_modul.ipynb) |
| Tugas Mahasiswa | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/username/Modul_Bode_Diagram/blob/main/tugas_bode_diagram.ipynb) |

> **Ganti `username`** dengan username GitHub Anda setelah meng-upload repo.

---

## 📁 Struktur File

```
Modul_Bode_Diagram/
├── README.md                   ← Halaman ini
├── bode_diagram_modul.ipynb    ← Modul pembelajaran lengkap
├── tugas_bode_diagram.ipynb    ← Lembar tugas mahasiswa
├── rubrik_penilaian.md         ← Rubrik & kriteria penilaian
└── bode_interactive.html       ← Simulator interaktif (browser)
```

---

## 🎯 Tujuan Pembelajaran

Setelah menyelesaikan modul ini, mahasiswa mampu:

1. Menjelaskan konsep diagram Bode (plot magnitude & fase)
2. Menggambar diagram Bode dari fungsi alih sistem orde 1 dan orde 2
3. Menggunakan aproksimasi asimtot untuk sketsa cepat
4. Mengidentifikasi frekuensi corner, gain margin, dan phase margin
5. Menganalisis kestabilan sistem menggunakan diagram Bode

---

## 🛠️ Cara Penggunaan

### Opsi 1 — Google Colab (Direkomendasikan, tanpa instalasi)
Klik badge **Open in Colab** di atas.

### Opsi 2 — Jalankan Lokal
```bash
# Install dependensi
pip install numpy scipy matplotlib ipywidgets control

# Aktifkan widget Jupyter
jupyter nbextension enable --py widgetsnbextension

# Jalankan notebook
jupyter notebook bode_diagram_modul.ipynb
```

### Opsi 3 — Simulator HTML
Buka file `bode_interactive.html` langsung di browser (tidak perlu instalasi apapun).

---

## 📋 Topik yang Dicakup

| Topik | Notebook |
|-------|----------|
| Fungsi alih & representasi | Modul |
| Plot magnitude (dB) | Modul |
| Plot fase (derajat) | Modul |
| Aproksimasi asimtot | Modul |
| Sistem orde 1 | Modul + Tugas |
| Sistem orde 2 | Modul + Tugas |
| Pole & zero majemuk | Modul + Tugas |
| Gain margin & phase margin | Modul + Tugas |
| Analisis kestabilan | Tugas |

---

## 📦 Dependensi Python

```
numpy >= 1.21
scipy >= 1.7
matplotlib >= 3.4
ipywidgets >= 7.6
control >= 0.9
```

---

## 👨‍🏫 Untuk Dosen

- File `rubrik_penilaian.md` berisi rubrik lengkap dengan bobot nilai per soal.
- Semua soal tugas dilengkapi jawaban referensi di notebook dosen (tersedia terpisah).
- Simulator HTML dapat digunakan saat presentasi kelas tanpa koneksi internet.

---

## 📄 Lisensi

MIT License — bebas digunakan dan dimodifikasi untuk keperluan pendidikan.
