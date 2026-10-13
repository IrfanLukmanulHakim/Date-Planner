# 💌 Love Letter & Date Planner

Aplikasi web romantis interaktif berbasis pixel-art untuk membuat janji temu / kencan manis!

---

## 📱 Cara Menambahkan Nomor WhatsApp Kamu

Agar tombol **"Bagikan ke WhatsApp"** langsung membuka chat WhatsApp ke nomor HP kamu secara otomatis:

### **Langkah-Langkah:**
1. Buka file **`love.js`**.
2. Cari pada **Baris 10**:
   ```javascript
   const MY_WHATSAPP_NUMBER = ''; // <- UBAH DI SINI (Contoh: '6281234567890')
   ```
3. Tuliskan nomor WhatsApp kamu di dalam tanda petik `' '` dengan format angka kode negara **62** (tanpa angka 0 di depan, tanpa tanda `+`, `-`, atau spasi).

   - **Contoh Penulisan yang Benar:**
     ```javascript
     const MY_WHATSAPP_NUMBER = '628123456789';
     ```

   - **Contoh Penulisan yang Salah:**
     - ❌ `'+6281234567890'` (Jangan pakai tanda +)
     - ❌ `'081234567890'` (Jangan pakai angka 0 di depan, ganti dengan 62)
     - ❌ `'62812-3456-7890'` (Jangan pakai tanda hubung)

4. Simpan file (`Ctrl + S`).

---

## 🎟️ Fungsi Tombol Tiket:
- **Bagikan ke WhatsApp**: Langsung membuka aplikasi WhatsApp dengan pesan rincian janji kencan tanpa mengunduh file gambar.
- **Simpan Tiket PNG**: Mengunduh gambar tiket kencan beresolusi tinggi ke galeri/perangkat kamu.
