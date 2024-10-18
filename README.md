# ✨ Image Enhancement Application 🖼️

[![Python](https://img.shields.io/badge/Python-3.9-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/Version-1.0.0-green)](https://github.com/your-username/ImageEnhancementApp)

🎉 **Selamat datang di Aplikasi Perbaikan Kualitas Citra!** 🎉  
Aplikasi ini dikembangkan untuk meningkatkan kualitas citra yang terpengaruh oleh noise dengan menggunakan **Filter Median** dan **Filter Rata-rata**.

## 🚀 Fitur Utama
- 📂 **Membuka file gambar** dan menampilkannya dalam tampilan asli.
- 🖥️ **Menerapkan Filter Median** untuk mengurangi noise pada gambar.
- 🎨 **Menerapkan Filter Rata-rata** untuk perbaikan gambar yang halus.
- 💾 **Menyimpan gambar hasil** dengan format `.png`.
- 📊 **Menampilkan histogram** untuk membandingkan gambar asli dan yang telah diproses.

## 🎬 Demo Aplikasi
![Image Enhancement Demo](demo.gif)

## 🛠️ Cara Instalasi

1. Clone repository ini ke lokal Anda:
   ```bash
   git clone https://github.com/Charelas/Pengolahan-Citra-TI-21-KA-212310041.git
   
2. Masuk ke folder project:
   ```bash
   cd ImageEnhancementApp
   
3. Buat virtual environment dan aktifkan:
   ```bash
   python -m venv venv
   source venv/bin/activate # di Mac/Linux
   venv\Scripts\activate # di Windows
   
4. Install semua dependensi:
   ```bash
   pip install -r requirements.txt

## 💻 Cara Menggunakan 

1. Jalankan aplikasi:
   ```bash
   python ImageEnhancePro.py
   
2. Pilih gambar dari komputer Anda dengan klik File > Open.
3. Gunakan slider untuk mengatur ukuran kernel pada Filter Median dan Filter Rata-rata.
4. Klik tombol Apply untuk menerapkan filter yang diinginkan.
5. Kita bisa menyimpan hasil gambar dengan klik File > Save.

## 🔧 Teknologi yang Digunakan

* Python 3.9: Bahasa pemrograman utama
* CustomTkinter: Untuk tampilan GUI yang modern
* OpenCV: Untuk pengolahan citra
* PIL (Pillow): Untuk memanipulasi gambar
* Matplotlib: Untuk menampilkan histogram


<style>
  @keyframes typing {
    from { width: 0; }
    to { width: 100%; }
  }

  @keyframes blink {
    50% { border-color: transparent; }
  }

  .typing-text {
    font-family: monospace;
    white-space: nowrap;
    overflow: hidden;
    border-right: 2px solid;
    width: 0;
    animation: typing 5s steps(30, end), blink 0.75s step-end infinite;
  }
</style>

<div class="typing-text">🎉 Aplikasi Perbaikan Kualitas Citra Siap Digunakan! 🎉</div>



## 👨‍💻 Pengembang
Emanuel Charel Alessando Soge | GitHub
