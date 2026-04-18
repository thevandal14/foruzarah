# 🎁 Interactive Digital Gift (Web Surprise)

Sebuah proyek website interaktif yang dirancang khusus sebagai kado kejutan digital. Pengguna akan disambut dengan teka-teki logika, animasi partikel yang memukau, pemutar musik, hingga surat rahasia berenkripsi.

## 🤖 Credit & The Art of "Vibe Coding"

Proyek ini adalah hasil harmoni antara fondasi *open-source* dan eksplorasi *Artificial Intelligence*:

- **25% Fondasi Dasar:** Struktur awal dari proyek ini (terutama pada halaman bunga) terinspirasi dan dikembangkan dari repositori milik [septiandwica/kado](https://github.com/septiandwica/kado). Terima kasih atas inspirasinya!
- **75% Ekspansi & Vibe Coding:** Seluruh perombakan besar dan penambahan fitur lanjutan—termasuk 10 level *mini-games*, *timer* penghancur (countdown), sistem *Canvas Particle* tata surya, *Glassmorphism UI*, dan dekripsi surat rahasia—dilakukan melalui pendekatan **Vibe Coding menggunakan Gemini AI**. Alih-alih menulis setiap baris kode secara manual, pengembangan ini dilakukan dengan mendeskripsikan "vibe", logika, dan estetika yang diinginkan secara bahasa natural, lalu membiarkan AI menerjemahkan imajinasi tersebut menjadi barisan kode JavaScript, HTML, dan CSS yang fungsional.

## ✨ Fitur Utama

- **⏳ Self-Destruct Countdown:** Dilengkapi dengan *timer* mundur 1x24 jam (menggunakan LocalStorage). Setelah batas waktu habis, akses menuju hadiah akan terkunci secara permanen.
- **🎮 10-Level Mini Games Lock:** Hadiah utama dikunci oleh 10 level permainan logika, mulai dari kuis astronomi, logika matematika CPNS, tes silogisme, hingga *Memory Match* (Mencocokkan Kartu).
- **🌸 Interactive CSS Flowers:** Animasi bunga mekar yang dianimasikan murni menggunakan CSS murni.
- **🌌 Canvas Particle Magic:** Efek partikel kosmik menggunakan HTML5 Canvas yang secara dinamis berkumpul membentuk berbagai wujud (Kue, Hati, Teks) dengan hukum fisika *spring & wobble*.
- **🎵 Glassmorphism Music Player:** Menu pemutar lagu terintegrasi bergaya kaca transparan yang melayang elegan.
- **💌 Secret Typewriter Letter:** Halaman surat bergaris dengan efek mesin ketik otomatis. Dilengkapi *Easter Egg* (Tombol 🪄 Ganti Font) untuk mendekripsi tulisan abstrak menjadi pesan yang bisa dibaca, sekaligus mengunci rapat beberapa paragraf yang memang ditujukan untuk menjadi rahasia abadi.

## 📂 Struktur Direktori

```text
📦 digital-gift-project
 ┣ 📂 css
 ┃ ┣ 📜 style.css       # Styling untuk halaman utama (index)
 ┃ ┗ 📜 main.css        # Styling untuk struktur bunga
 ┣ 📂 img
 ┃ ┗ 🖼️ flowers.png     # Favicon dan aset gambar
 ┣ 📂 music
 ┃ ┣ 🎵 default.mp3     # Musik background utama
 ┃ ┣ 🎵 1.mp3           # Playlist lagu 1
 ┃ ┣ 🎵 2.mp3           # Playlist lagu 2
 ┃ ┗ 🎵 3.mp3           # Playlist lagu 3
 ┣ 📜 index.html        # Halaman muka (Countdown & 10 Level Games)
 ┣ 📜 flower.html       # Halaman animasi bunga mekar
 ┣ 📜 partikel.html     # Halaman animasi partikel Canvas kosmik
 ┗ 📜 surat.html        # Halaman surat digital dengan dekripsi font