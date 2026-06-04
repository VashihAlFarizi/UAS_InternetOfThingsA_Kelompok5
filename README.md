# UAS_InternetOfThingsA_Kelompok5

## **Nama Kelompok:**

Kelompok 5

## **Anggota:**

1. Vashih Al Farizi (2309106076)
2. Ari Fullah (2309206085)
3. Muhamad Raihan Akhsani Taqwim (2309106050)
4. Fatir Januarta (2309106057)

---

## **Judul**

Sistem Monitoring Ketinggian Air Bendungan Menggunakan Sensor Ulterasonik dan Sensor Hujan

---

## **Deskripsi**

Sistem Monitoring Ketinggian Air Bendungan Menggunakan Sensor Ultrasonik dan Sensor Hujan” adalah sistem yang menggunakan sensor ultrasonik untuk mengukur ketinggian air dan sensor hujan untuk mendeteksi intensitas curah hujan. Data dari kedua sensor diproses oleh ESP32 untuk menentukan status kondisi bendungan, yaitu aman, waspada, atau bahaya.
Informasi kondisi bendungan ditampilkan secara realtime melalui aplikasi Kodular, dikirim ke platform Antares untuk penyimpanan dan pemantauan data IoT, serta diteruskan ke Telegram sebagai notifikasi peringatan dini. Selain itu, sistem juga dilengkapi LED dan buzzer sebagai indikator lokal untuk memberikan peringatan secara langsung kepada petugas.
Sebagai pengembangan dari sistem monitoring, digunakan motor servo yang berfungsi sebagai simulasi aktuator pintu bendungan. Servo dapat bergerak pada beberapa posisi bukaan, yaitu tertutup, setengah terbuka, dan terbuka, sesuai dengan kondisi yang ditentukan atau melalui kendali manual dari aplikasi. Pada mode otomatis, posisi servo menyesuaikan status kondisi bendungan yang dihasilkan dari pengolahan data sensor. Sedangkan pada mode manual, petugas dapat mengendalikan posisi bukaan pintu bendungan melalui aplikasi Kodular.

---

## **Komponen yang Digunakan** ##
- ESP 32
- Breadboard
- LED Hijau, Kuning, Merah
- HC-SR04 Sensor Ultrasonic
- Raindrop sensor
- Buzzer
- Servo
- Kabel jumper
- Sumber daya kabel type c

---

## **Board Schematic** ##
<img width="953" height="663" alt="image" src="https://github.com/user-attachments/assets/b4eeb1cb-2d4b-4ce6-878b-1db3aa0d32db" />




---

