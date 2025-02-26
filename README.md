# 📌 Ramadan Tracker - README

## 📖 Deskripsi Singkat
Ramadan Tracker adalah sistem pelacakan amalan harian selama bulan Ramadan berbasis percakapan. Pengguna dapat menginput progres ibadah secara natural, dan sistem akan memperbarui tabel amalan harian, menampilkan progress tilawah dalam bentuk progress bar, serta memberikan insight dan motivasi.

## ⚙️ Cara Setup
1. Copy prompt di file prompt dan jalankan di ChatGPT.
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
 
