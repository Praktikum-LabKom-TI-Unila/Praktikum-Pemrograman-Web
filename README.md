# Praktikum Pemrograman Web

Repository ini berisi kumpulan praktikum pemrograman web yang mencakup HTML, CSS, JavaScript, PHP, dan AJAX.

## 📂 Struktur Folder

### **Modul 1 - HTML & CSS**
- `1.1` - Struktur Dasar HTML
- `1.2` - HTML dengan Gambar dan Link
- `1.3` - Pengenalan CSS
- `1.4` - CSS External dan Layout
- `1.5` - Form HTML dengan CSS Styling

### **Modul 2 - GIT & Version Control**
- `2.1` - Instalasi dan Konfigurasi Git
- `2.2` - Membuat Repository Lokal
- `2.3` - Commit dan History
- `2.4` - Remote Repository dengan GitHub
- `2.5` - Branching dan Merging
- `2.6` - Collaboration dan Conflict Resolution

### **Modul 3 - CSS Framework & Templating**
- `3.1` - Pengenalan Bootstrap
- `3.2` - Bootstrap Navigation & Layout
- `3.3` - Pengenalan Tailwind CSS
- `3.4` - Tailwind CSS Layout & Components
- `3.5` - Form Styling dengan Framework

### **Modul 4 - PHP & Manipulasi Form**
- `4.1` - PHP Dasar dan Sintaks 
- `4.2` - Form HTML dengan Method GET
- `4.3` - Form HTML dengan Method POST
- `4.4` - Validasi dan Sanitasi Form
- `4.5` - File Upload dengan PHP
- `4.6` - Session dan Cookie

### **Modul 5 - JavaScript Dasar**
- `5.1` - Fungsi JavaScript
- `5.2` - Manipulasi DOM Dasar
- `5.3` - Event Listener dan Interaktivitas
- `5.4` - Aplikasi Interaktif Sederhana

## 🚀 Cara Menggunakan

### Untuk File HTML (Modul 1, 3, 5, 6)
1. Buka file HTML langsung di browser

### Untuk File PHP (Modul 4 & 6.3)

**Tanpa XAMPP/WAMP - Menggunakan PHP Built-in Server:**

**Cara 1: Jalankan dari folder root**
```bash
# Dari folder PRAKTIKUM-PEMWEB
php -S localhost:8000

# Akses di browser:
# http://localhost:8000/4/4.1/hello.php
# http://localhost:8000/4/4.2/process-get.php
```

**Cara 2: Jalankan dari folder modul**
```bash
# Masuk ke folder modul tertentu
cd 4/4.1
php -S localhost:8000

# Akses di browser:
# http://localhost:8000/hello.php
```

**Catatan:**
- Tekan `Ctrl + C` untuk menghentikan server
- Ganti port jika bentrok: `php -S localhost:3000`
- Server ini hanya untuk development, bukan production

## 📝 Catatan

- Untuk modul PHP (folder 4 & 6.3), pastikan server lokal sudah berjalan
- Untuk upload file (4.5), pastikan folder `uploads/` memiliki permission yang sesuai

---

*Praktikum Pemrograman Web - 2025*
