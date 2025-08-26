# Send-email-dengan-formspree
Mengirim email untuk kebutuhan landing page section contact dengan pihak ke 3 formspree

# 📩 Form Kontak Landing Page (Formspree)

Formulir HTML sederhana untuk landing page perusahaan.  
User bisa mengisi **Nama, Email, dan Pesan** → otomatis terkirim ke email marketing perusahaan melalui **Formspree**.

---

## 🚀 Cara Penggunaan

1. **Daftar di Formspree**
   - Buka [https://formspree.io](https://formspree.io) dan buat akun gratis.
   - Buat proyek baru → dapatkan **endpoint form** (contoh: `https://formspree.io/f/abcd1234`).

2. **Edit File HTML**
   - Buka file `index.html`.
   - Cari baris:
     ```html
     <form id="contactForm" action="https://formspree.io/f/SESUAIKAN_ENDPOINT" method="POST">
     ```
   - Ganti `SESUAIKAN_ENDPOINT` dengan endpoint dari Formspree.
   - Cari baris berikut:
     ```html
     <input type="hidden" name="_to" value="marketing@perusahaan.com">
     ```
   - Ganti `marketing@perusahaan.com` dengan email marketing perusahaan Anda.

3. **Upload ke Landing Page**
   - Upload file `index.html` ke hosting / server perusahaan.
   - Coba isi form → cek apakah email masuk ke inbox.

---

## 🖥️ Diagram Alur

