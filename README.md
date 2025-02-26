# 📌 Ramadan Tracker - README

## 📖 Deskripsi Singkat
Ramadan Tracker adalah sistem pelacakan amalan harian selama bulan Ramadan berbasis percakapan. Pengguna dapat menginput progres ibadah secara natural, dan sistem akan memperbarui tabel amalan harian, menampilkan progress tilawah dalam bentuk progress bar, serta memberikan insight dan motivasi.

## ⚙️ Cara Setup
1. Jalankan prompt Ramadan Tracker di ChatGPT.
2. Sistem akan menanyakan **kapan 1 Ramadan dimulai**.
3. Setelah user menjawab, sistem akan menghitung hari Ramadan yang sedang berjalan.
4. Tabel awal akan ditampilkan dalam keadaan kosong untuk **5 hari pertama Ramadan**.
5. Default tampilan adalah **5 hari terakhir**, namun dapat diubah ke tampilan keseluruhan atau rentang kustom.

## 🏆 Cara Penggunaan
1. **Input Data**:
   - *"Udah shalat Maghrib dan ba’diyahnya."* → **Shalat wajib (1/5) & shalat rawatib (2/12)**
   - *"Udah baca Quran sampai Al-Baqarah ayat 100."* → **Tilawah (QS. 2:100), progress tilawah diperbarui**
   - *"Udah sedekah hari ini."* → **Sedekah (✅)**

2. **Visualisasi & Tracking**:
   - **Tabel amalan harian menampilkan 5 hari terakhir**.
   - **Hari yang belum ada input tampil kosong, yang terlewat ditandai ❌ atau 0**.
   - **Progress tilawah dalam bentuk progress bar (%) dan juz (1-30)**.
   - **Summary harian berisi insight & motivasi**.

3. **Opsi Tampilan untuk Shalat Wajib & Rawatib**:
   - **Default**: Persentase (%)
   - Bisa diubah ke **x/5 & x/12** atau **color grade (🔴🟡🟢)**

4. **Pengingat & Motivasi**:
   - Jika belum ada input setelah **Maghrib**, sistem akan mengingatkan secara friendly.
   - Summary harian memberikan motivasi tambahan.

5. **Kustomisasi Tampilan**:
   - Default **5 hari terakhir**, bisa diubah ke **seluruh Ramadan (1-30 hari) atau rentang tertentu**.
   - Opsi tampilan dapat disesuaikan sesuai preferensi pengguna.

## 📊 Contoh Output Tabel (Dummy Data)

📊 **Tabel Amalan Harian (Dummy Data)**

```
Hari	Sahur	Puasa	Shalat Wajib	Rawatib	Tarawih	Tahajud	Dzikir Pagi	Dzikir Petang	Kajian	Sedekah	Tilawah
1	✅	✅	🟡 2/5	🟡 6/12	➖	➖	➖	➖	➖	✅	✅
2	✅	✅	🟢 5/5	➖	✅	➖	✅	✅	➖	✅	✅
3	✅	✅	🟢 5/5	🟡 4/12	✅	➖	✅	✅	✅	✅	✅
4	✅	✅	🟢 5/5	🟢 12/12	✅	➖	✅	✅	➖	✅	✅
5	✅	✅	🟡 4/5	🟡 6/12	✅	➖	➖	➖	✅	✅	✅
6	✅	✅	🟢 5/5	➖	✅	✅	✅	✅	➖	✅	✅
7	✅	✅	🟢 5/5	🟡 8/12	✅	✅	✅	✅	✅	✅	✅
8	✅	✅	🟢 5/5	🟢 12/12	✅	✅	✅	✅	✅	✅	✅
9	✅	✅	🟡 4/5	🟡 6/12	✅	✅	✅	✅	✅	✅	✅
10	✅	✅	🟢 5/5	➖	✅	✅	✅	✅	➖	✅	✅
```

📈 **Progress Tilawah (Dummy Data)**
🔹 **Terakhir dibaca: QS. An-Nas:6**
🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩 (Juz 30/30) 🎉 **Khatam!**

📜 **MasyaAllah, Ramadan penuh berkah! 🌿✨**

Dummy data ini bisa kamu pakai sebagai gambaran. Kalau ada yang mau diubah atau diperbaiki, tinggal bilang aja! 😃

🚀 **Mulai sekarang! Jawab pertanyaan berikut untuk memulai tracking:**
➡️ **Kapan 1 Ramadan dimulai?**

Setelah menjawab, sistem akan langsung membuat tabel awal & mulai tracking Ramadan! 🎯

