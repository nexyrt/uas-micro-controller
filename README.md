# Uas-Micro-Controller
Repositori GitHub ini berisi tugas ujian akhir untuk mata kuliah **Micro Controller**. Tugas ini dirancang untuk menguji dan menilai pemahaman kami tentang pemrograman **Micro Controller**,  *hardware interfacing*, dan *embedded systems development*.
| Nama              |  NIM          |
| ----------------- | ------------- |
| Rizky Hamdani     | 2009106089    |
| Indro Dwi Saputro | 2009106089    |

## Rangkaian dan Penjelasan

### Overview
![alt text](https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2020/07/ESP32-PIR-Motion-Sensor-Send-Message-Notificatio-Telegram.png?w=890&quality=100&strip=all&ssl=1)

Berikut adalah gambaran umum tentang bagaimana proyek ini bekerja : 
- Kami akan membuat bot Telegram untuk ESP32 bekerja.
- ESP32 terhubung ke *PIR Motion Sensor*.
- Ketika sensor mendeteksi gerakan, ESP32 mengirim pesan peringatan ke akun telegram.
- Kami akan diberitahu di akun telegram yang sudah terhubung ke bot setiap kali ada gerakan yang terdeteksi.

### Steps / Langkah-langkah
1. **Membuat telegram Bot**
2. **Dapatkan ID Pengguna Telegram Anda**
3. **Mempersiapkan Arduino IDE**
   - Diperlukan sebuah *Universal " target="_blank">Brian Lough</a> yang menyediakan antarmuka yang mudah untuk API Bot Telegram.
   - Anda juga harus menginstal *<a href="Telegram Bot Library*, untuk berinteraksi dengan bot Telegram. Kita akan menggunakan library dari <a href="https://github.com/witnessmenow/Universal-Arduino-Telegram-Bothttps://github.com/bblanchon/ArduinoJson" target="_blank">Arduino Json</a> library*. Ikuti langkah selanjutnya untuk menginstal *library*.
      - Pergi ke Skech > Include Library > Manage Libraries.
      - Cari "ArduinoJson".
      - Instal *library*.
Kami menggunakan pustaka ArduinoJson versi 6.5.12.
4. **Siapkan Komponen <br> Untuk proyek ini, Anda memerlukan bagian-bagian berikut ini:**
   - ESP32 Board
   - PIR motion sensor (HC-SR501)
   - Jumper wires
   - Breadboard
5. **Rangkaian** <br>
   Untuk proyek ini, Anda perlu menyambungkan *PIR Motion Sensor* ke *ESP32 Board*. Ikuti gambar rangkaian berikut ini.
![alt text](https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2020/07/ESP32-PIR-Motion-Sensor-Wiring-Diagram.png?resize=1024%2C649&quality=100&strip=all&ssl=1)
7.  
