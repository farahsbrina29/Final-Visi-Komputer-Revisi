# Visi-Komputer--Tugas-Final Revisi
# Deteksi Pembuluh Darah pada Penyakit Central Retinal Artery Occlusion (CRAO) dan Background Diabetic Retinopathy (BDR) Menggunakan Citra Fundus

## Deskripsi Proyek
Proyek ini bertujuan untuk mendeteksi dan memperjelas pembuluh darah pada citra fundus retina pada dua kondisi penyakit mata, yaitu Central Retinal Artery Occlusion (CRAO) dan Background Diabetic Retinopathy (BDR). Teknik pengolahan citra yang digunakan meliputi ekstraksi kanal hijau, peningkatan kontras menggunakan CLAHE (Contrast Limited Adaptive Histogram Equalization) dan contrast stretching, serta deteksi tepi menggunakan algoritma Canny edge detection. Proyek ini bertujuan membantu diagnosis dengan memperjelas struktur pembuluh darah dan ciri khas seperti foveal cherry-red spot pada CRAO dan mikroaneurisma serta eksudat pada BDR.

## Fitur Utama
- Analisis kanal yang terbaik untuk citra
- Ekstraksi kanal hijau dari citra RGB fundus untuk mendapatkan kontras optimal pembuluh darah.
- Perbandingan Histogram Equalization dan CLAHE
- Peningkatan kontras lokal menggunakan CLAHE untuk menyesuaikan pencahayaan tidak merata.
- Peningkatan contrast stretching untuk memperjelas batas dan kontur pembuluh darah.
- Deteksi tepi menggunakan Canny edge detection untuk mendapatkan kontur pembuluh darah secara akurat.
- Overlay hasil deteksi tepi pada citra grayscale sebagai visualisasi yang memperjelas area yang terpengaruh.
- Analisis kuantitatif intensitas rata-rata dan persentase piksel tepi untuk evaluasi hasil.

## Cara Penggunaan
1. Siapkan citra fundus retina berformat RGB.
2. Membandingkan kanal RGB yang terbaik untuk citra
3. Jalankan ekstraksi kanal hijau untuk mendapatkan citra grayscale.
4. Terapkan CLAHE untuk meningkatkan kontras lokal.
5. Lakukan contrast stretching untuk memperjelas struktur.
6. Gunakan Canny edge detection untuk mendeteksi tepi pembuluh darah.
7. Buat overlay hasil edge detection pada citra grayscale untuk visualisasi.

## Teknologi yang Digunakan
- Bahasa Pemrograman: Python
- Library: OpenCV, NumPy, Matplotlib (atau library visualisasi lain)
- Algoritma: CLAHE, Canny Edge Detection
