<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<p align="center">
  <a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

---

# 🗂 Sistem Informasi Project Monitoring Sederhana

Aplikasi Laravel sederhana untuk mengelola dan memantau data proyek, seperti:
- Nama proyek
- Project leader
- Tanggal mulai dan akhir
- Nama klien
- Progress proyek
- Upload foto proyek

---

## 👩‍💻 Dibuat Oleh
**Poppy**  
D3 Teknik Informatika  
Politeknik Hasnur  

---

## 📌 Fitur Aplikasi
✅ CRUD data proyek  
✅ Upload foto proyek  
✅ Tampilan tabel monitoring  
✅ Desain bersih dengan Tailwind CSS  
🚫 Tidak menggunakan login (sesuai ketentuan)

---

## 🛠 Teknologi
- Laravel 10
- MySQL
- Tailwind CSS
- Laravel File Storage

---

## 📸 Screenshot Tampilan

> Pastikan kamu sudah upload gambar ke folder `screenshots/`

### 📋 Daftar Project
![Daftar Project](screenshots/daftar_project.png)

### ➕ Tambah Project
![Tambah Project](screenshots/tambah_project.png)

### ✏️ Edit Project
![Edit Project](screenshots/edit_project.png)

---

## 🚀 Cara Menjalankan Project
```bash
git clone https://github.com/NurRizkaZahra/project-monitoring-sederhana.git
cd project-monitoring-sederhana
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
