Berikut contoh **README.md** yang cocok untuk proyek kamu (frontend turnamen Taekwondo).
Kamu bisa menyesuaikan nama repo, link backend, dan cara instalasi sesuai kebutuhan 👇

---

```markdown
# Taekwondo Tournament Frontend

Frontend aplikasi manajemen turnamen Taekwondo.  
Proyek ini menampilkan daftar peserta, bagan pertandingan, dan integrasi dengan API backend.

---

## 🚀 Fitur

- Autentikasi pengguna (login/logout)
- Menampilkan daftar peserta dan detailnya
- Bagan pertandingan dengan pencarian berdasarkan **nama** atau **nomor partai**
- Integrasi dengan backend menggunakan REST API
- Responsive untuk desktop dan mobile

---

## 🛠️ Teknologi

- HTML, CSS, JavaScript (Vanilla)
- [Bootstrap](https://getbootstrap.com/) untuk UI
- [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API) untuk komunikasi dengan backend

---

## 📂 Struktur Folder

```

Frontend/
├── index.html
├── bagan.html
├── css/
├── js/
└── assets/

````

> Pastikan file `bagan.html` menggunakan variabel `BASE_URL` yang mengarah ke backend.

---

## ⚙️ Konfigurasi

Buat file **.env** di root frontend (opsional jika kamu ingin memisahkan konfigurasi):

```env
BASE_URL=https://taekwondo-backend.vercel.app
````

Jika tidak, pastikan di script `bagan.html` nilai `API_URL` sudah diarahkan ke endpoint backend.

---

## ▶️ Menjalankan secara lokal

1. Clone repository:

   ```bash
   git clone https://github.com/alwirihad/TaekwondoApp-Frontend.git
   cd TaekwondoApp-Frontend
   ```

2. Jalankan dengan Live Server (atau extension serupa di VSCode).
   Pastikan backend sudah berjalan.

---

## 🌐 Deploy

Frontend ini bisa dideploy ke:

* [Vercel](https://vercel.com/) (direkomendasikan)
* GitHub Pages
* Netlify

Langkah umum untuk Vercel:

1. Push kode ke GitHub.
2. Hubungkan repo ke Vercel.
3. Pilih framework = **Other**.
4. Deploy (tidak perlu build step jika hanya HTML/CSS/JS).

---

## 🔗 API Backend

Proyek ini menggunakan API dari repo [TaekwondoApp-Backend](https://github.com/alwirihad/TaekwondoApp-Backend).

Pastikan environment backend sudah terpasang dengan benar:

```env
PORT=5000
SUPABASE_URL=...
SUPABASE_KEY=...
JWT_SECRET=...
```

---

## 👤 Author

* **Alwi Rihad** – [GitHub](https://github.com/alwirihad)

```
