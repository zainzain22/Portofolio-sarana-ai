# 🤖 IoT Face Detection System with ESP32-CAM, Edge Impulse, and Blynk

## 📌 Deskripsi Singkat
Proyek ini merupakan bagian dari skripsi mahasiswa **Teknik Instrumentasi Universitas Brawijaya**. Sistem ini mengintegrasikan **kamera ESP32-CAM**, **CNN model dari Edge Impulse**, dan **Blynk** untuk membangun sistem keamanan berbasis pengenalan wajah yang dapat dikontrol dan dipantau melalui aplikasi IoT secara real-time.

---

## 🎯 Tujuan Proyek
- Mendeteksi wajah menggunakan model CNN pada perangkat edge (ESP32).
- Mengaktifkan solenoid lock jika wajah dikenali.
- Menampilkan status deteksi dan kontrol perangkat melalui aplikasi **Blynk**.

---

## 🔧 Komponen Perangkat Keras

| Komponen          | Fungsi                                 |
|-------------------|----------------------------------------|
| ESP32-CAM         | Kamera + mikrokontroler utama          |
| Buzzer            | Memberikan peringatan suara            |
| LED               | Indikator visual hasil deteksi         |
| Solenoid Lock     | Mengunci / membuka berdasarkan hasil   |
| Breadboard & Kabel| Perakitan rangkaian                    |

---

## 🧠 Teknologi yang Digunakan

| Teknologi         | Deskripsi                             |
|-------------------|----------------------------------------|
| **Edge Impulse**  | Pelatihan CNN model untuk deteksi wajah |
| **Arduino IDE**   | Pemrograman mikrokontroler             |
| **Blynk IoT App** | Kontrol & pemantauan status perangkat  |
| **C++ (Arduino)** | Bahasa utama untuk ESP32               |

---

## 📱 Integrasi Blynk

Sistem ini terhubung ke aplikasi Blynk, memungkinkan:
- Monitoring status deteksi wajah
- Menampilkan log pembukaan kunci
- Kontrol manual solenoid (jika diperlukan)
- Notifikasi real-time saat deteksi wajah terjadi

---

## ⚙️ Cara Kerja Sistem

1. ESP32-CAM menangkap wajah pengguna secara real-time.
2. Model CNN dari Edge Impulse mendeteksi apakah wajah dikenali.
3. Jika dikenali:
   - LED hijau menyala
   - Buzzer berbunyi singkat
   - Solenoid terbuka
   - Status dikirim ke aplikasi Blynk
4. Jika tidak dikenali:
   - LED merah menyala
   - Kunci tetap terkunci
   - Status ditampilkan di Blynk

---

## 📁 Dokumentasi
(https://drive.google.com/drive/folders/1p9R5Aujwbfeif7EdRT6GwuX69QDBakJw?usp=sharing)

---

## 🧪 Hasil Implementasi

✅ Deteksi wajah akurat dengan inference langsung di ESP32  
✅ Koneksi ke Blynk stabil dan responsif  
✅ Semua perangkat (buzzer, LED, solenoid) bekerja sesuai hasil prediksi model  
✅ Sistem dapat berjalan offline maupun online (Blynk untuk monitoring)

---

## 🎓 Kontribusi

Proyek ini dibuat untuk tugas akhir mahasiswa Teknik Instrumentasi Universitas Brawijaya. Cocok untuk:
- Sistem keamanan rumah pintar
- Kontrol akses berbasis AI
- Implementasi Edge AI untuk IoT

---

