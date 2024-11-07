# Sentiment Analysis with Caikit and Hugging Face

Repositori ini menampilkan layanan analisis sentimen yang menggunakan kerangka kerja runtime Caikit yang dikombinasikan dengan model Hugging Face. Ini membuat server gRPC untuk mengelola permintaan analisis sentimen, yang memungkinkan pengguna untuk menganalisis input teks dan menentukan apakah input tersebut positif, negatif, atau netral.

## Overview

Proyek ini menggunakan kerangka kerja modular Caikit untuk mengoperasikan model analisis sentimen Hugging Face dalam lingkungan server gRPC. Contoh skrip klien menunjukkan cara mengirim input teks ke server dan menerima hasil klasifikasi sentimen.

## Features

- **gRPC Server**: Mengoperasikan server untuk menangani permintaan analisis sentimen melalui gRPC.
- **Caikit Runtime Integration**: Menyederhanakan operasi model menggunakan kerangka kerja runtime Caikit.
- **Hugging Face Models**: Memanfaatkan model klasifikasi sentimen yang sudah terlatih dari Hugging Face.

## Installation

1. **Clone the Repository**  
   Kloning repositori ini ke mesin lokal kita:
   ```bash
   git clone https://github.com/intanrahmadhani/sentiment_analysist.git
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
3. **Environment Setup**
   Pastikan konfigurasi yang diperlukan (misalnya, jalur model atau pengenal) diatur dengan benar di lingkungan atau file konfigurasi kita.
