# Sistem Maklumbalas dan Aduan HR

**Dibina oleh RUBIX TECHNOLOGY**

Sistem web yang memudahkan pekerja untuk menghantar maklumbalas dan aduan kepada jabatan HR dengan antara muka yang mesra pengguna dan panel admin untuk pengurusan.

## Ciri-ciri Utama

### Portal Pengguna (index.html)
- ✅ Borang dwi-fungsi (Maklumbalas & Aduan)
- ✅ Antara muka responsif dengan Tailwind CSS
- ✅ Penyerahkan data ke Google Sheets melalui Google Apps Script
- ✅ Maklumbalas masa nyata untuk pengguna
- ✅ Sokongan Bahasa Malaysia

### Panel Admin (admin.html)
- 🔐 Sistem login berasaskan email
- 📊 Dashboard dengan statistik ringkasan
- 🔍 Fungsi carian dan penapisan data
- 👁️ Paparan detail dalam modal popup
- 📈 Analisis sentimen automatik (Positif/Negatif)
- 🔄 Data masa nyata dari Google Sheets

## Teknologi yang Digunakan

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Tailwind CSS, Font Awesome Icons
- **Backend**: Google Apps Script
- **Database**: Google Sheets
- **Font**: Inter (Google Fonts)

## Struktur Fail

```
asiahhisamHR/
├── index.html      # Portal utama untuk pengguna
├── admin.html      # Panel admin untuk HR
└── README.md       # Dokumentasi sistem
```

## Cara Penggunaan

### Untuk Pengguna
1. Buka `index.html` dalam pelayar web
2. Pilih tab "Maklum Balas" atau "Aduan"
3. Isi tajuk dan mesej
4. Klik butang hantar

### Untuk Admin HR
1. Buka `admin.html` dalam pelayar web
2. Log masuk dengan email yang dibenarkan
3. Lihat dashboard dengan statistik
4. Gunakan carian dan penapisan untuk mencari data
5. Klik pada sebarang item untuk melihat butiran penuh

## Keperluan Sistem

- Pelayar web moden (Chrome, Firefox, Safari, Edge)
- Sambungan internet aktif
- Google Apps Script yang dikonfigurasi dengan betul

## Konfigurasi

Sistem ini memerlukan Google Apps Script yang telah dikonfigurasi untuk:
- Menerima data dari borang
- Menyimpan data dalam Google Sheets
- Mengesahkan admin berdasarkan email
- Menyediakan API untuk panel admin

URL Google Apps Script perlu dikemaskini dalam kedua-dua fail HTML:
```javascript
const GOOGLE_SCRIPT_URL = 'YOUR_GOOGLE_SCRIPT_URL_HERE';
```

## Keselamatan

- Autentikasi admin melalui email dan token sesi
- Validasi data pada sisi klien dan pelayan
- Sesi automatik tamat tempoh untuk keselamatan

## Sokongan

Untuk sebarang pertanyaan atau masalah teknikal, hubungi **RUBIX TECHNOLOGY**.

---

*Sistem ini direka khusus untuk memudahkan komunikasi antara pekerja dan jabatan HR dengan cara yang cekap dan selamat.*