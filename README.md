# SIAP LAPOR

Aplikasi pelaporan kerusakan perangkat dan layanan internal, ditulis ulang dari versi PHP lama ke Laravel.

## Kegunaan

- Pelaporan kerusakan perangkat oleh pengguna.
- Verifikasi dan tindak lanjut oleh teknisi.
- Riwayat, rekap, dan ekspor laporan.
- Notifikasi real-time untuk perubahan status.

## Tech stack

| Lapis | Teknologi |
|---|---|
| Backend | Laravel 11 (PHP 8.2) |
| Auth | Laravel Fortify |
| Realtime | Laravel Reverb + Echo |
| Ekspor | dompdf, OpenSpout |
| Tambahan | QR code, Three.js untuk tampilan 3D |
| Data | MySQL, Redis |

## Alur singkat

1. Pengguna membuat laporan kerusakan.
2. Laporan masuk ke antrean teknisi.
3. Status diperbarui dan pelapor menerima notifikasi.
4. Rekap diekspor untuk arsip.

## Ringkasan

| | |
|---|---|
| Mulai dikembangkan | September 2026 |
| Status | Migrasi selesai, aktif dipakai |

> Kode sumber tidak dipublikasikan. Repo ini hanya menjelaskan kegunaan, stack, dan alur kerja. Tidak ada data pengguna, data pasien, atau kredensial di sini.
