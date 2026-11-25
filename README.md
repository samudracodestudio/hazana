# HAZANA 1.0 — Unified National Zakat Data Hub (GitHub Pages)

Dashboard statis berbasis arsitektur JSON terkurasi untuk memantau ekosistem pengelolaan zakat Indonesia tanpa memerlukan server lokal.

## Cakupan Data Terverifikasi
- **852 entitas OPZ** (`550` BAZNAS · `219` LAZ berizin aktif SIMZAT Kemenag · `83` LAZ non-SIMZAT/LPZN)
- **203 Anggota Forum Zakat (FOZ)** (`140` terdaftar aktif di SIMZAT · `63` non-SIMZAT/UPZ/BAZNAS)
- **219 titik peta pusat LAZ SIMZAT** (`62` Nasional · `50` Provinsi · `107` Kab/Kota) + **`394` kantor perwakilan daerah**
- **343 arsip Annual Report & Laporan Keuangan** (`15.524` halaman terindeks), termasuk **Pilot Ekstraksi Multi-Klasifikasi Dompet Dhuafa (1993–2024: 31 tahun teraudit & 91 riwayat kepemimpinan)**
- **Agregat Nasional LPZN 2025**: `754` pelapor (`Rp 11.421.551.458.572` penghimpunan tercatat)

## Pembaruan Data
Jalankan di folder induk `HAZANA 1.0`:
```bash
./publish_github.sh
```
Workflow `.github/workflows/pages.yml` akan otomatis mem-publish perubahan ke GitHub Pages setiap kali branch `main` di-push.
