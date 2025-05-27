# Code Walkthrough - login.php (Cafe App)

## Tujuan
Melakukan review kode login Cafe App bersama tim teknis.

## Tim Reviewer
- Developer Cafe App
- QA Engineer
- Supervisor/Dosen

## Fokus Review
- Validasi dan keamanan input login
- Kejelasan dan efisiensi logika login
- Penanganan session dan redirection

## Catatan
- Input belum menggunakan `htmlspecialchars()` atau `prepared statement`, rawan SQL Injection.
- Login berhasil → sesi disimpan dan redirect ke `index.php`.
- Perlu pembatasan percobaan login untuk keamanan tambahan.