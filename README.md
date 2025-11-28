# 🌍 Earth Tuner - Live World Radio 3D

![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-live-success)
![Technology](https://img.shields.io/badge/Three.js-3D-black)

**Earth Tuner** adalah eksperimen web interaktif yang memungkinkan Anda menjelajahi dan mendengarkan stasiun radio langsung dari seluruh dunia melalui visualisasi Globe 3D yang imersif.

🔗 **Live Demo:** [Klik di sini untuk mencoba](https://earth-tuner.vercel.app/) atau [Klik di sini untuk mencoba](https://earthtuner.netlify.app/)

---

## ✨ Fitur Utama

* 🌐 **Globe 3D Interaktif:** Putar, zoom, dan jelajahi bumi dalam 3D (menggunakan Three.js).
* 📻 **400+ Stasiun Radio:** Terhubung langsung ke API Radio Browser untuk data realtime.
* 🎵 **Live Streaming:** Pemutar audio HTML5 bawaan dengan dukungan format stream modern.
* 📱 **Responsif:** Berjalan mulus di Desktop dan Mobile.
* 🎨 **UI Sci-Fi Modern:** Antarmuka dengan efek kaca (glassmorphism) dan nuansa futuristik.

---

## 🛠️ Teknologi

Project ini dibangun sebagai **Static Site** (HTML/JS murni) tanpa build tools yang rumit:

* **HTML5 & CSS3**
* **Tailwind CSS** (via CDN)
* **Three.js** (Library 3D utama via ES Modules)
* **Radio Browser API** (Sumber data stasiun radio)

---

## 🚀 Cara Menjalankan (Lokal)

Karena penggunaan ES Modules (`import ...`), file ini **tidak bisa** dibuka langsung dengan double-click `index.html`. Anda memerlukan server lokal.

1.  **Clone Repository:**
    ```bash
    git clone [https://github.com/azfaribn/earth-tuner.git](https://github.com/azfaribn/earth-tuner.git)
    cd earth-tuner
    ```

2.  **Jalankan Server Lokal:**
    * Jika menggunakan **VS Code**: Install ekstensi **Live Server**, buka `index.html`, klik kanan -> "Open with Live Server".
    * Jika menggunakan **Python**:
        ```bash
        python -m http.server
        ```
    * Buka browser di `http://localhost:8000`.

---

## ☁️ Cara Deploy ke Vercel

1.  Upload file `index.html` ke repository GitHub Anda.
2.  Buka [Vercel](https://vercel.com).
3.  **Add New Project** -> Import repository GitHub tadi.
4.  Pada bagian **Framework Preset**, pilih **Other**.
5.  Pastikan **Build Command** dan **Output Directory** dikosongkan.
6.  Klik **Deploy**.

---

## 📝 Lisensi

Project ini dilisensikan di bawah **MIT License**.
Dibuat dengan ❤️ oleh **[Azfaribn]**.
