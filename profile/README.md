<h1 align="center">💻 IoT Rescue System</h1>
<p align="center">
  <img src="https://github.com/GPS-Tracking/.github/blob/main/GPS%20Tracking%20-%20Logo.png" alt="Logo" width="220" height="200">
</p>

<h3 align="center">Gemastik IoT Maps Tracking</h3>

<p align="center">
  <b>Sistem aplikasi berbasis IoT untuk membantu tim penyelamat dalam sweeping area bencana.<br>
  Proyek ini dikembangkan khusus untuk Lomba GEMASTIK XVII 2024.</b>
</p>

---

## 🚀 Pendahuluan

Selamat datang di proyek <b>IoT Rescue System</b>! Proyek ini merupakan kontribusi kami dalam ajang <b>GEMASTIK XVII 2024</b>. Sistem ini memanfaatkan teknologi Internet of Things (IoT), Machine Learning, serta web dashboard interaktif untuk membantu tim penyelamat memonitor posisi, mendeteksi kondisi darurat, dan mengoptimalkan jalur evakuasi di area bencana secara real-time.

### 👤 Anggota Tim

| Nama                              |
|------------------------------------|
| Ghiyats Ibnu Syahied              |
| Muhammad Hauzan Dini Fakhri       |
| Naufal Maulana Al-Ghifari Irawan  |

---

## 🎯 Tema

- Aplikasi & Sistem Berbasis Web
- Internet of Things & Smart Rescue
- Monitoring Area Bencana Real-Time

---

## 📋 Fitur Proyek

- **Maps View**: Menampilkan posisi GPS perangkat secara real-time.
- **Monitoring Dashboard**: Dashboard lengkap untuk tracking & monitoring perangkat rescue (web).
- **Path Optimization**: Menemukan jalur tercepat ke lokasi SOS menggunakan algoritma A*.
- **Notifikasi Otomatis**: Pemberitahuan sistem untuk kondisi darurat atau peristiwa penting.
- **Integrasi Machine Learning**: Analisis status & prediksi berbasis AI (pada dashboard).
- **Komunikasi MQTT**: Data dikirim dari perangkat IoT ke server secara efisien.

---

## 🏗️ Struktur Repositori

Organisasi ini terdiri dari beberapa repositori utama:

| Repository | Deskripsi | Status |
|------------|-----------|--------|
| [Frontend](https://github.com/Gemastik-IoT-Maps-tracking/Frontend) | Website dashboard utama & integrasi Machine Learning | Public |
| [Backend](https://github.com/Gemastik-IoT-Maps-tracking/Backend) | API server & pengelola database untuk frontend | Public |
| [Arduino](https://github.com/Gemastik-IoT-Maps-tracking/Arduino) | Kode perangkat IoT berbasis Arduino | Private |
| [ML](https://github.com/Gemastik-IoT-Maps-tracking/ML) | Komponen machine learning & visualisasi | Private |
| [Hive MQTT](https://github.com/Gemastik-IoT-Maps-tracking/hive-Mqtt) | Integrasi MQTT untuk komunikasi IoT | Private |
| [Assets](https://github.com/Gemastik-IoT-Maps-tracking/Assets) | Asset gambar & dokumentasi visual | Public |

---

## ✨ Tampilan Dashboard

<p align="center">
  <img src="https://github.com/Gemastik-IoT-Maps-tracking/Assets/blob/main/Frontend/Halaman%20Home%20Frontend.png" alt="Dashboard Home" width="600"/><br>
  <i>Dashboard Home</i>
</p>
<p align="center">
  <img src="https://github.com/Gemastik-IoT-Maps-tracking/Assets/blob/main/Frontend/Halaman%20SOS%20Frontend.png" alt="SOS Page" width="600"/><br>
  <i>Halaman SOS</i>
</p>
<p align="center">
  <img src="https://github.com/Gemastik-IoT-Maps-tracking/Assets/blob/main/Frontend/Halaman%20Data%20Frontend.png" alt="Data Page" width="600"/><br>
  <i>Halaman Data</i>
</p>

---

## ⚡️ Cara Instalasi Cepat

### Frontend (Dashboard & AI)
```bash
# Instalasi AI
pip install -r requirements.txt

# Instalasi website
npm install

# Menjalankan AI
py api.py

# Menjalankan frontend
npm run dev
```
Lihat dokumentasi lengkap di masing-masing repo.

### Backend (API & Database)
```bash
# Import database
# 1. Buat database baru (misal: instalasi-backend)
# 2. Import struktur tabel

# Instalasi backend
composer install

# Menjalankan backend
composer start
```

---

## 📞 Kontak

Untuk informasi lebih lanjut, silakan hubungi salah satu anggota tim atau buka [Issues](https://github.com/Gemastik-IoT-Maps-tracking/.github/issues).

---

<p align="center">
  <i>Dikembangkan khusus untuk Lomba GEMASTIK XVII 2024 <br>
  Didukung oleh Universitas Gunadarma</i>
</p>

---

# 💻 IoT Rescue System (English Section)

<p align="center">
  <img src="https://github.com/GPS-Tracking/.github/blob/main/GPS%20Tracking%20-%20Logo.png" alt="Logo" width="220" height="200">
</p>

<h3 align="center">Gemastik IoT Maps Tracking</h3>

<p align="center">
  <b>An IoT-based application system to assist rescue teams in disaster area sweeping.<br>
  This project is developed for the GEMASTIK XVII 2024 competition.</b>
</p>

---

## 🚀 Introduction

Welcome to the <b>IoT Rescue System</b> project! This is our official entry for <b>GEMASTIK XVII 2024</b>. The system utilizes Internet of Things (IoT), Machine Learning, and an interactive web dashboard to help rescue teams monitor positions, detect emergencies, and optimize evacuation routes in disaster areas in real-time.

### 👤 Team Members

| Name                             |
|----------------------------------|
| Ghiyats Ibnu Syahied             |
| Muhammad Hauzan Dini Fakhri      |
| Naufal Maulana Al-Ghifari Irawan |

---

## 🎯 Theme

- Application & Web-Based System
- Internet of Things & Smart Rescue
- Real-time Disaster Area Monitoring

---

## 📋 Project Features

- **Maps View**: Real-time GPS position tracking of devices.
- **Monitoring Dashboard**: Comprehensive dashboard for tracking & monitoring rescue devices (web).
- **Path Optimization**: Finds the fastest route to SOS points using the A* algorithm.
- **Automatic Notification**: System notifications for emergencies or important events.
- **Machine Learning Integration**: AI-based analysis & prediction on dashboard.
- **MQTT Communication**: Efficient data transfer from IoT devices to server.

---

## 🏗️ Repository Structure

This organization includes several main repositories:

| Repository | Description | Status |
|------------|-------------|--------|
| [Frontend](https://github.com/Gemastik-IoT-Maps-tracking/Frontend) | Main dashboard website & AI (Machine Learning) integration | Public |
| [Backend](https://github.com/Gemastik-IoT-Maps-tracking/Backend) | API server & database handler for frontend | Public |
| [Arduino](https://github.com/Gemastik-IoT-Maps-tracking/Arduino) | Code for Arduino-based IoT devices | Private |
| [ML](https://github.com/Gemastik-IoT-Maps-tracking/ML) | Machine learning components & visualization | Private |
| [Hive MQTT](https://github.com/Gemastik-IoT-Maps-tracking/hive-Mqtt) | MQTT integration for IoT communication | Private |
| [Assets](https://github.com/Gemastik-IoT-Maps-tracking/Assets) | Image assets & visual documentation | Public |

---

## ✨ Dashboard Preview

<p align="center">
  <img src="https://github.com/Gemastik-IoT-Maps-tracking/Assets/blob/main/Frontend/Halaman%20Home%20Frontend.png" alt="Dashboard Home" width="600"/><br>
  <i>Dashboard Home</i>
</p>
<p align="center">
  <img src="https://github.com/Gemastik-IoT-Maps-tracking/Assets/blob/main/Frontend/Halaman%20SOS%20Frontend.png" alt="SOS Page" width="600"/><br>
  <i>SOS Page</i>
</p>
<p align="center">
  <img src="https://github.com/Gemastik-IoT-Maps-tracking/Assets/blob/main/Frontend/Halaman%20Data%20Frontend.png" alt="Data Page" width="600"/><br>
  <i>Data Page</i>
</p>

---

## ⚡️ Quickstart

### Frontend (Dashboard & AI)
```bash
# AI Installation
pip install -r requirements.txt

# Website Installation
npm install

# Run AI
py api.py

# Run frontend
npm run dev
```
See complete documentation in each repository.

### Backend (API & Database)
```bash
# Database import
# 1. Create a new database (e.g.: instalasi-backend)
# 2. Import table structure

# Backend installation
composer install

# Run backend
composer start
```

---

## 📞 Contact

For more information, feel free to contact any team member or open an [Issue](https://github.com/Gemastik-IoT-Maps-tracking/.github/issues).

---

<p align="center">
  <i>Developed for GEMASTIK XVII 2024 <br>
  Supported by Universitas Gunadarma</i>
</p>
