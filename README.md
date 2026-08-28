# Ahadya Travel Trip

![Ahadya Travel Trip](public/logo.png)

Ahadya Travel Trip adalah sebuah platform layanan tour & travel modern yang dibangun untuk memudahkan pelanggan dalam memesan paket perjalanan (Open Trip, Private Trip) serta Jasa Transportasi & Akomodasi (JTA). Website ini saya kembangkan khusus untuk klien dengan berfokus pada desain antarmuka yang elegan, performa tinggi, serta sistem pengelolaan data (Admin Dashboard) yang lengkap dan aman.

🌐 **Live Website:** [ahadyatraveltrip.my.id](https://ahadyatraveltrip.my.id)

---

## 🚀 Fitur Utama

### 1. Customer Interface (Sisi Pelanggan)
- **Desain Modern & Responsif:** Tampilan UI/UX yang memanjakan mata, cepat, dan dioptimalkan untuk perangkat *mobile* maupun *desktop*.
- **Katalog Layanan Lengkap:** Menampilkan berbagai opsi perjalanan seperti *Open Trip*, *Private Trip*, hingga penyewaan villa/transportasi.
- **Sistem Pemesanan Terintegrasi:** Pelanggan dapat melihat detail paket (jadwal, harga, fasilitas, *itinerary*) dan melakukan *booking* secara langsung.
- **AI Customer Service (CS Bot):** Dilengkapi dengan asisten virtual cerdas berteknologi AI (terintegrasi dengan Groq API / Llama 3) untuk menjawab pertanyaan pelanggan secara *real-time* 24/7.
- **Galeri & Testimoni:** Halaman khusus untuk menampilkan dokumentasi perjalanan dan ulasan asli dari pelanggan sebelumnya.

### 2. Admin Dashboard (Sistem Manajemen)
Sebuah panel admin yang diproteksi dengan autentikasi keamanan (JWT + Middleware) untuk memberikan kendali penuh kepada pemilik usaha:
- **Statistik & Tren Pendapatan:** Grafik interaktif untuk memonitor total pesanan dan tren pendapatan (*revenue*) selama 7 hari terakhir.
- **Manajemen Pesanan:** Memantau pesanan masuk, mencatat status pembayaran (DP/Lunas), dan mengelola data pelanggan.
- **Manajemen Layanan & Kategori:** Admin dapat menambah, mengubah, atau menghapus paket *trip* beserta harganya secara dinamis.
- **Manajemen Galeri & Testimoni:** Mengunggah foto dokumentasi terbaru dan mengelola *review* pelanggan untuk ditampilkan di halaman depan.
- **Sistem Webhook Notifikasi:** Terintegrasi dengan Google Apps Script untuk pengiriman notifikasi otomatis (*WhatsApp/Email* - *opsional menyesuaikan kebutuhan klien*).

---

## 🛠️ Teknologi yang Digunakan (Tech Stack)

Proyek ini dibangun menggunakan teknologi *Full-Stack* modern berbasis ekosistem JavaScript/TypeScript:

- **Framework Utama:** [Next.js (App Router)](https://nextjs.org/) - React Framework untuk *Server-Side Rendering* (SSR) dan optimasi SEO.
- **Bahasa Pemrograman:** [TypeScript](https://www.typescriptlang.org/) - Memberikan keamanan pengetikan (*type safety*) pada kode.
- **Desain & Styling:** [Tailwind CSS](https://tailwindcss.com/) - *Utility-first* CSS framework untuk *styling* yang cepat dan responsif.
- **Database:** [PostgreSQL](https://www.postgresql.org/) (di-host menggunakan [Supabase](https://supabase.com/)).
- **ORM:** [Prisma](https://www.prisma.io/) - Untuk pemodelan dan manajemen interaksi ke *database*.
- **AI Integration:** [Groq API](https://groq.com/) - Menyediakan respons AI yang super cepat untuk fitur CS Bot.
- **Deployment & Hosting:** [Vercel](https://vercel.com/) - Platform *deployment* otomatis untuk skalabilitas tinggi.

---

## 👨‍💻 Tentang Pengembang (Developer)

Website ini dirancang dan dikembangkan dari awal hingga *deployment* oleh saya sebagai solusi digital yang *scalable* untuk bisnis *travel*.

Jika Anda tertarik dengan *source code*, arsitektur, atau ingin berkolaborasi untuk pembuatan website serupa, jangan ragu untuk menghubungi saya!

---
*© 2026 Ahadya Travel Trip. All rights reserved.*
