# Hackaton
## Project Idea: 
Name: Tree analyzer

Concept: Sebuah ai bot yang bisa mengidentifikasi jenis pohon yang ditanam oleh user dan bisa mengenali, mengestimasi jumlah CO2 yang bisa diserap, dan memberikan tips atau informasi lainya terkait menanam pohon sebagai solusi untuk penghambat perubahan iklim yang disebabkan oleh peningkatan emisi gas rumah kaca. 

Akan dimasukan ke website jika waktunya sempat.

Impact: Membantu user untuk mengestimasi berapa CO2 yang bisa diserap oleh pohon yang ditanam agar bisa mengurangi/menghambat perubahan iklim. 

Pustaka: 
pipenv install ...
- discord.py
- numpy
- keras
- requests
- tensorflow
- Pillow

Referensi: https://github.com/danoefebriano022-del/Project-Lamps.git

Article: 
- https://lestari.kompas.com/read/2023/12/20/140000086/10-pohon-dengan-kemampuan-serap-karbon-dioksida-tertinggi
- https://goodstats.id/article/10-pohon-dengan-penyerapan-karbon-tertinggi-IKyz0

## Tujuan Pengujian
Pengujian dilakukan untuk memastikan bahwa proyek:
- Bisa mengidentifikasi jenis pohon dengan benar
- Bisa memberikan estimasi penyerapan CO₂ berdasarkan jenis pohon yang diidentifikasi
- Memberikan informasi dan tips yang relevan mengenai penanaman pohon
- Memiliki antarmuka yang mudah digunakan
- Berjalan dengan baik tanpa kesalahan yang mengganggu pengguna

---

# Testing Checklist

## 1. Fungsionalitas

### Hasil yang Diharapkan
Seluruh fitur utama dapat berjalan sesuai spesifikasi

### Checklist
- [ ] Verifikasi gambar pohon dapat diproses dengan benar
- [ ] Verifikasi AI dapat mengenali jenis pohon
- [ ] Verifikasi estimasi penyerapan CO₂ ditampilkan dengan benar
- [ ] Verifikasi informasi dan tips penanaman muncul sesuai jenis pohon
- [ ] Verifikasi sistem dapat menangani gambar yang tidak valid
- [ ] Verifikasi pesan kesalahan muncul apabila gambar tidak dapat dikenali
- [ ] Verifikasi hasil prediksi ditampilkan kepada pengguna tanpa error

### Prioritas
**Tinggi**

---

## 2. Antarmuka Pengguna (UI)

### Hasil yang Diharapkan
Bot discord dapat merespons dengan cepat dan tetap stabil

### Checklist
- [ ] Pengguna dapat mengunggah gambar dengan mudah
- [ ] Hasil identifikasi ditampilkan dengan jelas
- [ ] Informasi penyerapan CO₂ mudah dibaca

### Prioritas
**Sedang**

---

## 3. Kinerja (Performance)

### Hasil yang Diharapkan
Aplikasi dapat merespons dengan cepat dan stabil.

### Checklist
- [ ] Waktu prediksi gambar sesuai target(5-10 detik)
- [ ] Penggunaan memori tidak berlebihan
- [ ] Tidak terjadi crash selama penggunaan normal
- [ ] Model AI dapat memproses gambar dengan stabil

### Prioritas
**Tinggi**

---

## Ringkasan Hasil Pengujian

| Kategori | Status | Catatan |
|-----------|---------|---------|
| Fungsionalitas | ⬜ | |
| Antarmuka Pengguna | ⬜ | |
| Kinerja | ⬜ | |

## Kesimpulan

Tuliskan hasil akhir pengujian:
- Apakah seluruh fitur Tree Analyzer berjalan dengan baik? Saat ini fitur Tree Analyzer masih hanya bisa menidentifikasi jenis pohon dari gambar yang di input dan belum memberi user jawaban dari estimasi jumlah CO2 yang bisa di produksi. 
- Apakah terdapat kesalahan atau bug yang perlu diperbaiki? Memakai versi tensorflow yang salah. Untuk memperbaikinya aku mengganti versi tensorflow yang bisa memperbaiki errornya. 
- Apakah tingkat akurasi model sudah memenuhi target? Sejauh ini bot bisa mengembalikan nama pohon dengan benar dengan akurasi yang tinggi.
- Apakah proyek siap untuk dipresentasikan atau dirilis? Projek belum siap dirilis karena ada beberapa fitur yang belum ditambahkan. 
