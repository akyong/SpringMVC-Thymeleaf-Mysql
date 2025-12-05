# Spring Boot Employee CRUD API

Proyek ini adalah aplikasi RESTful API sederhana untuk pengelolaan data Karyawan (Employee). Dibangun menggunakan **Spring Boot**, **Spring Data JPA**, **MySQL**, dan **Maven**.

Aplikasi ini mendukung operasi CRUD (Create, Read, Update, Delete) lengkap, termasuk fitur **Partial Update (PATCH)** menggunakan Jackson `ObjectMapper`.

## 🛠 Teknologi

*   **Java SDK**: Versi 25
*   **Framework**: Spring Boot
*   **Database**: MySQL
*   **ORM**: Spring Data JPA & Hibernate
*   **JSON Processing**: Jackson Databind
*   **Build Tool**: Maven

## 📋 Prasyarat

Sebelum menjalankan aplikasi, pastikan Anda telah menginstal:
1.  JDK 25 (atau versi yang kompatibel).
2.  MySQL Server.
3.  Maven (opsional, karena wrapper `mvnw` sudah disertakan).

## ⚙️ Konfigurasi Database

1.  Buat database kosong di MySQL Anda, misalnya dengan nama `employee_directory`.
2.  Buka file `src/main/resources/application.properties`.
3.  Sesuaikan konfigurasi berikut dengan kredensial database Anda:
