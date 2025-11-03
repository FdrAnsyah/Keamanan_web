# Keamanan Web - Vulnerable Flask Application Lab

Ini adalah sebuah Aplikasi yang memiliki kerentanan yang sengaja dibuat untuk tujuan pembelajaran. Aplikasi ini mengandung beberapa kerentanan web umum untuk diidentikasi oleh mahasiswa dan di eksploitasi di local server.


## Quick Start

### Opsi 1: Run menggunakan Flask
1. Clone repository:
   ```bash
   git clone https://github.com/FdrAnsyah/Keamanan_web
   ```

2. Pindah directory ke lab_1:
   ```bash
   cd lab_1
   ```

3. Install flask:
   ```bash
   pip install -r requirements.txt
   ```

4. Inisiasi database:
   ```bash
   python db_init.py
   ```

5. Run menggunakan flask:
   ```bash
   flask run
   ```
6. Buka browser dan ketik:
   ```bash
   `http://127.0.0.1:5000`
   ```

### Opsi 2: Run menggunakan Docker
1. Clone repository:
   ```bash
   git clone https://github.com/FdrAnsyah/Keamanan_web
   ```

2. Pindah directory ke lab_1:
   ```bash
   cd lab_1
   ```


3. Run menggunakan Docker container:
   ```bash
   docker-compose up --build
   ```

4. Buka browser dan ketik:
   ```bash
   http://127.0.0.1:5000
   ```

## Default Credentials

Aplikasi ini memiliki akun user yang sudah dibuat sebelumnya:

- Username: `alice`, Password: `password123` (Regular user)
- Username: `bob`, Password: `mypassword` (Regular user)
- Username: `admin`, Password: `adminpass` (Admin user)

## Lab Instructions

Gunakan aplikasi ini untuk belajar mengidentifikasi dan eksploitasi kerentanan web umum menggunakan tools seperti:
- SQLMap untuk SQL injection
- Burp Suite or OWASP ZAP untuk test umum
- Manual testing techniques
