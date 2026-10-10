# Finova - Personal Finance & Cash Flow Dashboard

Finova adalah aplikasi web sederhana berbasis *client-side* yang dirancang untuk membantu pengguna mengelola keuangan pribadi, memantau arus kas harian, menyusun anggaran bulanan, serta melacak target tabungan secara praktis dan aman.

---

## 📋 Fitur Utama

- **Pencatatan Transaksi (CRUD):** Tambah, lihat, edit, dan hapus transaksi pengeluaran atau pemasukan dengan mudah.
- **Visualisasi Arus Kas:** Grafik interaktif menggunakan **Chart.js** untuk melihat tren pengeluaran dan alokasi anggaran.
- **Budgeting & Target Tabungan:** Atur batas anggaran bulanan dan pantau progres alokasi dana tabungan.
- **Penyimpanan Lokal (100% Privat):** Seluruh data tersimpan otomatis di *LocalStorage* browser. Tidak ada data yang dikirim ke server luar atau *database* pihak ketiga.
- **Ekspor & Impor Data:** Fitur cadangan data dalam format **JSON** dan **CSV** agar data keuangan tetap aman dan fleksibel dipindahkan.
- **Desain Modern & Responsif:** Tampilan UI/UX bersih dengan skema warna yang nyaman berbasis **Tailwind CSS**.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5 & Vanilla JavaScript (ES6+)**
- **Tailwind CSS** (via CDN)
- **Chart.js** (Visualisasi Grafik)
- **Lucide Icons** (Ikon UI)

---

## 🚀 Cara Menjalankan Proyek

Proyek ini murni berbasis *client-side* tanpa perlu setup server backend atau instalasi `npm`.

### Menjalankan Secara Lokal

1. **Clone Repositori**
   ```bash
   git clone https://github.com/USERNAME_KAMU/finova.git
   cd finova
   ```

2. **Jalankan Aplikasi**
   - Buka file `index.html` menggunakan **Live Server** di VS Code.
   - Atau jalankan HTTP server lokal sederhana via terminal:
     ```bash
     npx serve .
     ```
   - Buka URL `http://localhost:3000` di browser kamu.

---

## 🤖 Peran AI Agent dalam Pengembangan

Aplikasi ini dikembangkan dengan bantuan **IBM Bob IDE** sebagai *AI Coding Agent*. Peran AI Agent meliputi:
- Menerjemahkan spesifikasi fitur menjadi struktur kode Vanilla JS yang rapi dan modular.
- Menulis logika perhitungan arus kas, batas anggaran, serta fungsi impor/ekspor file JSON & CSV.
- Mengintegrasikan library Chart.js dan Lucide Icons agar berjalan stabil tanpa error *dependency*.
- Mengatur tata letak antarmuka pengguna berbasis Tailwind CSS.

---

## 📜 Lisensi

Proyek ini dibuat untuk keperluan *Capstone Project* / Pembelajaran. Bebas digunakan dan dikembangkan kembali di bawah lisensi [MIT](LICENSE).
