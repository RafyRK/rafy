# 🕌 Aplikasi Web Absensi Remaja Masjid

Aplikasi web **Absensi Remaja Masjid** adalah antarmuka (interface) halaman kehadiran digital yang dirancang khusus untuk mencatat kehadiran anggota remaja masjid dalam berbagai kegiatan. Desain ini dibuat modern, bersih, intuitif, dan sepenuhnya responsif (*mobile-friendly*) agar mudah digunakan oleh generasi muda langsung melalui *smartphone* mereka.

## ✨ Fitur Utama

* **Desain Islami Modern:** Menggunakan perpaduan warna hijau islami (`#2e7d32`) yang segar dan estetika minimalis.
* **Komponen Interaktif:** Pilihan status kehadiran (Hadir, Izin, Sakit) berbentuk tombol kartu yang berubah warna saat dipilih, bukan radio button jadul.
* **Responsif:** Tampilan otomatis menyesuaikan ukuran layar, sangat nyaman dibuka di HP maupun Laptop.
* **Ringan & Cepat:** Hanya menggunakan HTML5, CSS3 murni, dan JavaScript vanilla tanpa *library* pihak ketiga yang memberatkan.
* **Tipografi Elegan:** Terintegrasi langsung dengan Google Fonts (Poppins) agar teks terlihat ramah dan kekinian.

## 🚀 Cara Penggunaan

1. **Unduh/Salin Kode:** Simpan kode HTML yang telah disediakan ke dalam file baru bernama `index.html`.
2. **Jalankan Aplikasi:** Klik dua kali (*double click*) file `index.html` tersebut untuk langsung membukanya di browser favorit Anda (Chrome, Edge, Safari, Firefox).
3. **Isi Absensi:** 
   * Masukkan **Nama Lengkap**.
   * Pilih jenis **Kegiatan** pada menu *dropdown*.
   * Pilih **Status Kehadiran**.
   * Tambahkan **Keterangan** jika diperlukan (misal: alasan izin/sakit).
   * Klik tombol **Kirim Kehadiran**.

## 🛠️ Struktur Kode

* **Struktur Form (`<form>`):** Menampung input data nama, kegiatan, status, dan keterangan tambahan.
* **Gaya Visual (`<style>`):** Mengatur tata letak menggunakan *Flexbox* dan *CSS Grid*, efek bayangan (*box-shadow*), serta animasi transisi halus saat tombol ditekan.
* **Logika JavaScript (`<script>`):** Menangani proses pengiriman data agar halaman tidak memuat ulang (*anti-reload*) saat tombol diklik, menampilkan notifikasi sukses, dan mengosongkan kembali form setelah selesai.

## ⚙️ Rencana Pengembangan (Next Updates)

Aplikasi ini dapat dikembangkan lebih lanjut sesuai kebutuhan DKM atau organisasi remaja masjid Anda:
* [ ] Integrasi otomatis simpan data ke **Google Sheets**.
* [ ] Integrasi tombol kirim laporan langsung ke **WhatsApp Pengurus**.
* [ ] Penambahan fitur rekapitulasi kehadiran bulanan.

---
Distribusi bebas untuk keperluan pengelolaan administrasi Masjid dan Dakwah.
