# Personal Portfolio - Frontend

Repositori ini berisi kode sumber untuk bagian *frontend* dari situs web portofolio pribadi saya. Proyek ini dibangun menggunakan **React** dan **Vite**, dikombinasikan dengan **Tailwind CSS** untuk desain antarmuka yang responsif dan modern, serta terhubung melalui REST API ke *backend* Laravel.

🌐 **Live Demo:** [portofoliofajar.my.id](https://portofoliofajar.my.id)


## 🛠️ Cara Menjalankan Secara Lokal

Untuk menjalankan proyek *frontend* ini di komputer lokal Anda, ikuti langkah-langkah berikut:

1.  **Clone repositori ini:**
    ```bash
    git clone [https://github.com/fajarash/portofolio-fajar.git](https://github.com/fajarash/portofolio-fajar.git)
    cd portofolio-fajar/frontend
    ```

2.  **Install dependencies (ketergantungan):**
    ```bash
    npm install
    ```

3.  **Konfigurasi Environment:**
    Salin file `.env.example` menjadi `.env` (jika ada) atau periksa file konfigurasi API Anda (misal `src/api/config.js`), lalu pastikan URL mengarah ke *backend* lokal Anda saat pengembangan:
    ```javascript
    // Contoh URL pengembangan
    export const API_BASE_URL = '[http://127.0.0.1:8000/api](http://127.0.0.1:8000/api)';
    ```

4.  **Jalankan server lokal (Development):**
    ```bash
    npm run dev
    ```
    Buka `http://localhost:5173` di peramban Anda untuk melihat hasilnya.

## 📦 Build untuk Production (Deployment)

Sebelum mengunggah ke *hosting*, pastikan URL API telah diubah ke alamat *backend* produksi Anda (misalnya `https://api.portofoliofajar.my.id/api`).

Jalankan perintah berikut untuk membuat file statis yang siap diunggah ke *Document Root* (`public_html`):
```bash
npm run build

👤 Tentang Saya
Hai, saya Fajar As Shidik. Saya adalah seorang Software Engineer dan lulusan Sarjana Komputer (S1 Informatika). Saya memiliki ketertarikan yang kuat pada Full-Stack Web Development, merancang sistem arsitektur API yang solid, dan membangun antarmuka pengguna yang interaktif. Saya menguasai ekosistem Laravel (PHP) untuk sisi server dan React untuk sisi klien.

📧 Email: fajarasshidik123@gmail.com

🐙 GitHub: @fajarash

💼 Portofolio: portofoliofajar.my.id

© 2026 Fajar As Shidik.

