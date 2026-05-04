# Rubrik Penilaian — Tugas Diagram Bode
**Mata Kuliah:** Sistem Kontrol  
**Topik:** Diagram Bode  
**Total Nilai:** 100 poin

---

## Soal 1 — Sistem Orde Pertama (20 poin)

**Deskripsi:** Analisis dan plot diagram Bode sistem orde satu.

| Kriteria | Sangat Baik (100%) | Baik (75%) | Cukup (50%) | Kurang (25%) | Tidak Ada (0%) |
|----------|--------------------|------------|-------------|--------------|----------------|
| **Identifikasi parameter** (4 poin) | Gain K dan konstanta waktu τ benar semua | Satu parameter salah | Kedua parameter salah tapi rumus benar | Rumus salah, ada upaya | Tidak dikerjakan |
| **Frekuensi corner** (4 poin) | ωc = 1/τ benar & dijelaskan | Nilai benar tanpa penjelasan | Metode benar, nilai salah | Hanya menebak | Tidak ada |
| **Aproksimasi asimtot** (6 poin) | Asimtot rendah & tinggi benar, slope −20 dB/dec dijelaskan | Asimtot benar, slope tidak dijelaskan | Satu asimtot benar | Ada upaya tapi salah | Tidak ada |
| **Plot Python & HTML** (6 poin) | Plot akurat, label sumbu lengkap, grid ada | Plot benar, label kurang lengkap | Plot hampir benar, ada kesalahan minor | Plot ada tapi salah | Tidak ada plot |

---

## Soal 2 — Sistem Orde Kedua (25 poin)

**Deskripsi:** Analisis sistem orde dua dengan variasi rasio redaman ζ.

| Kriteria | Sangat Baik (100%) | Baik (75%) | Cukup (50%) | Kurang (25%) | Tidak Ada (0%) |
|----------|--------------------|------------|-------------|--------------|----------------|
| **Identifikasi ωₙ dan ζ** (5 poin) | Keduanya benar dari fungsi alih | Satu benar | Metode benar, substitusi salah | Ada upaya | Tidak ada |
| **Pengaruh ζ terhadap puncak resonansi** (7 poin) | Menjelaskan Mp = 1/(2ζ√(1−ζ²)), frekuensi resonansi ωr, disertai bukti plot | Rumus benar tanpa pembuktian visual | Menjelaskan tren kualitatif saja | Penjelasan terbalik atau salah | Tidak ada |
| **Plot untuk 3 nilai ζ** (8 poin) | Tiga kurva benar, diberi label, warna berbeda, legenda | Dua kurva benar | Satu kurva benar | Ada plot tapi semua salah | Tidak ada |
| **Analisis perbandingan** (5 poin) | Membandingkan respons underdamped, critically damped, overdamped dengan tepat | Dua kondisi dibahas | Satu kondisi dibahas | Ada narasi tapi tidak relevan | Tidak ada |

---

## Soal 3 — Sistem dengan Pole dan Zero Majemuk (20 poin)

**Deskripsi:** Menggambar diagram Bode sistem dengan multiple poles dan zeros.

| Kriteria | Sangat Baik (100%) | Baik (75%) | Cukup (50%) | Kurang (25%) | Tidak Ada (0%) |
|----------|--------------------|------------|-------------|--------------|----------------|
| **Dekomposisi fungsi alih** (5 poin) | Memfaktorkan H(s) dengan benar, mengidentifikasi semua pole/zero | Faktorisasi benar, identifikasi kurang | Faktorisasi salah satu pole/zero | Ada upaya dekomposisi | Tidak ada |
| **Kontribusi tiap faktor** (7 poin) | Menggambar kontribusi tiap pole/zero secara terpisah | Menggambar 3 dari 4 kontribusi | Menggambar 2 kontribusi | Menggambar 1 kontribusi | Tidak ada |
| **Superposisi (gabungan)** (5 poin) | Penjumlahan dB dan derajat benar, plot akurat | Plot hampir benar, satu kesalahan | Error di titik tengah frekuensi | Error signifikan | Tidak ada |
| **Verifikasi dengan Python** (3 poin) | Kode jalan, hasil sesuai sketsa, ada komentar | Kode jalan tanpa komentar | Kode ada tapi error kecil | Kode ada tapi tidak jalan | Tidak ada |

---

## Soal 4 — Gain Margin dan Phase Margin (20 poin)

**Deskripsi:** Menentukan margin kestabilan dari diagram Bode.

| Kriteria | Sangat Baik (100%) | Baik (75%) | Cukup (50%) | Kurang (25%) | Tidak Ada (0%) |
|----------|--------------------|------------|-------------|--------------|----------------|
| **Definisi GM dan PM** (4 poin) | Mendefinisikan GM dan PM dengan benar, disertai ilustrasi | Definisi benar tanpa ilustrasi | Satu definisi benar | Definisi terbalik | Tidak ada |
| **Pembacaan nilai dari plot** (6 poin) | GM dan PM terbaca dengan benar dari plot, frekuensi kritis ditandai | Satu nilai benar | Metode benar, nilai salah karena baca plot | Ada upaya pembacaan | Tidak ada |
| **Kesimpulan kestabilan** (6 poin) | Menyimpulkan stabil/tidak stabil dengan kriteria GM>0 dB dan PM>0°, menjelaskan selisih keamanan | Kesimpulan benar tanpa penjelasan margin | Kesimpulan benar tapi alasan salah | Kesimpulan terbalik | Tidak ada |
| **Penggunaan fungsi `margin()`** (4 poin) | Menggunakan `control.margin()` dengan benar, hasil konsisten manual | Fungsi benar, sedikit perbedaan | Fungsi salah tapi output ada | Ada kode tapi error | Tidak ada |

---

## Soal 5 — Desain Kompensator (15 poin)

**Deskripsi:** Mendesain kompensator lead/lag untuk memenuhi spesifikasi.

| Kriteria | Sangat Baik (100%) | Baik (75%) | Cukup (50%) | Kurang (25%) | Tidak Ada (0%) |
|----------|--------------------|------------|-------------|--------------|----------------|
| **Identifikasi kebutuhan kompensasi** (3 poin) | Mengidentifikasi defisit PM dan GM, memilih tipe kompensator dengan alasan | Identifikasi benar, alasan kurang | Mengidentifikasi masalah tapi salah solusi | Ada analisis awal | Tidak ada |
| **Perhitungan parameter kompensator** (6 poin) | Parameter α, τ dihitung benar, prosedur sistematis | Satu parameter benar | Prosedur benar, aritmatika salah | Ada rumus tapi tidak dihitung | Tidak ada |
| **Verifikasi spesifikasi terpenuhi** (4 poin) | Plot sebelum & sesudah, menunjukkan PM dan GM terpenuhi | Plot ada, PM terpenuhi tapi GM tidak | Salah satu spesifikasi terpenuhi | Ada plot tanpa analisis | Tidak ada |
| **Diskusi trade-off** (2 poin) | Mendiskusikan trade-off bandwidth vs. margin | Sedikit diskusi | Menyebutkan tanpa menjelaskan | Tidak relevan | Tidak ada |

---

## Rekap Nilai

| Soal | Topik | Bobot |
|------|-------|-------|
| Soal 1 | Sistem Orde Pertama | 20 poin |
| Soal 2 | Sistem Orde Kedua | 25 poin |
| Soal 3 | Pole & Zero Majemuk | 20 poin |
| Soal 4 | Gain Margin & Phase Margin | 20 poin |
| Soal 5 | Desain Kompensator | 15 poin |
| **Total** | | **100 poin** |

---

## Ketentuan Pengurangan Nilai

| Kondisi | Pengurangan |
|---------|-------------|
| Terlambat 1–3 hari | −10% |
| Terlambat 4–7 hari | −25% |
| Terlambat > 7 hari | Tidak diterima |
| Plot tanpa label sumbu | −2 per plot |
| Kode tidak dapat dijalankan | −5 per soal terkait |
| Copy-paste tanpa modifikasi (plagiat) | 0 untuk seluruh tugas |

---

## Konversi Nilai Akhir

| Rentang Nilai | Huruf | Deskripsi |
|---------------|-------|-----------|
| 85–100 | A | Sangat Baik |
| 75–84 | AB | Baik Sekali |
| 65–74 | B | Baik |
| 55–64 | BC | Cukup Baik |
| 45–54 | C | Cukup |
| 35–44 | D | Kurang |
| < 35 | E | Gagal |
