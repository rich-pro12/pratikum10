# Pratikum10
## Richie Pranata 
## 312410451
## TI.24.A.5

# 📘 Praktikum 10 – PHP Object Oriented Programming (OOP)
## 🔎 Tujuan Praktikum

### Praktikum ini bertujuan untuk:

Memahami konsep dasar Object Oriented Programming (OOP) pada PHP.

Memahami penggunaan class, object, property, dan method.

Menerapkan konsep modularisasi menggunakan class library.

Membuat program PHP yang lebih terstruktur dan mudah dikembangkan.

## 🛠️ Tools yang Digunakan

PHP

Web Server (XAMPP)

Text Editor (Visual Studio Code)

Browser (Chrome / Firefox)

## 📂 Struktur Folder
lab10_php_oop/
│── mobil.php
│── form.php
│── form_input.php
│── config.php
│── database.php

## ✨ Langkah-langkah Praktikum
### 1️⃣ Membuat Class dan Object (File: mobil.php)

Pada tahap ini dibuat sebuah class Mobil yang memiliki:

Property: warna, merk, dan harga

Method: gantiWarna() dan tampilWarna()

Class ini kemudian diinstansiasi menjadi dua object ($a dan $b).
Setiap object memiliki perilaku yang berbeda meskipun berasal dari class yang sama.
Hal ini menunjukkan konsep dasar OOP yaitu class sebagai cetakan dan object sebagai objek nyata.

### 2️⃣ Membuat Class Library Form (File: form.php)

File form.php berisi class Form yang berfungsi sebagai class library untuk membuat form input secara dinamis.

Class ini memiliki fungsi:

Menyimpan field input dalam array

Menampilkan form HTML

Menambahkan field input menggunakan method addField()

File ini tidak bisa dijalankan langsung, karena hanya berisi deklarasi class.

### 3️⃣ Implementasi Class Library Form (File: form_input.php)

Pada file ini dilakukan pemanggilan class Form menggunakan include.

Langkah yang dilakukan:

Membuat object dari class Form

Menambahkan field input (NIM, Nama, Alamat)

Menampilkan form ke halaman web

Dengan cara ini, kode menjadi lebih modular, rapi, dan mudah digunakan kembali.

### 4️⃣ Konfigurasi Database (File: config.php)

File config.php digunakan untuk menyimpan konfigurasi database seperti:

Host

Username

Password

Nama database

Pemisahan konfigurasi ini bertujuan agar:

Kode lebih aman

Mudah diubah tanpa mengedit banyak file

### 5️⃣ Class Library Database (File: database.php)

File ini berisi class Database yang digunakan untuk:

Menghubungkan aplikasi ke database

Menjalankan query SQL

Melakukan operasi CRUD (Create, Read, Update, Delete)

Class ini menerapkan konsep OOP dan modularisasi sehingga koneksi database bisa digunakan di banyak file tanpa menulis ulang kode.

### 📌 Kesimpulan

Dari praktikum ini dapat disimpulkan bahwa:

OOP membuat program lebih terstruktur dan mudah dipahami

Class library membantu menerapkan konsep modularisasi

Kode menjadi lebih efisien, reusable, dan mudah dikembangkan

Pemisahan file meningkatkan kerapihan dan manajemen kode
