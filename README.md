# api_booking_online
Ini adalah API untuk aplikasi booking online tiket

# Requirement
1. Django versi 5.0


# 1️⃣ FITUR
## 🔐 A. User & Authentication

1. Registrasi & login user
    - Role:
    1. Admin
    2. Operator Bus
    3. Customer

2. Manajemen profil user
    - Reset password
    - Token auth (JWT / Session)

## 🚌 B. Manajemen Bus

CRUD data bus

Kapasitas kursi

Tipe bus (Ekonomi, Bisnis, Executive)

Status bus (aktif / maintenance)

🛣️ C. Rute & Jadwal

Manajemen kota asal & tujuan

Jadwal keberangkatan

Harga tiket per rute

Estimasi durasi perjalanan

🪑 D. Manajemen Kursi

Layout kursi (A1, A2, B1, dst)

Status kursi:

Available

Reserved

Booked

Lock kursi sementara (anti double booking)

🎫 E. Booking Tiket

Pilih rute & jadwal

Pilih kursi

Booking multi-penumpang

Status booking:

Pending

Paid

Cancelled

Expired

Generate kode booking

💳 F. Pembayaran

Metode pembayaran (Transfer, E-Wallet, VA)

Status pembayaran

Expired payment

Integrasi payment gateway (Midtrans / Xendit)

📄 G. Tiket & Check-in

Generate e-ticket (QR Code)

Check-in penumpang

Scan QR oleh operator

📊 H. Dashboard & Laporan

Statistik penjualan

Laporan harian / bulanan

Occupancy rate bus

Riwayat booking

🔔 I. Notifikasi

Email / WhatsApp notifikasi

Booking berhasil

Pembayaran sukses

Reminder keberangkatan
