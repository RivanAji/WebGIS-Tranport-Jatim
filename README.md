# WebGIS Transportasi Jatim V.2

WebGIS Transportasi Jatim versi 2 — aplikasi peta web untuk visualisasi jaringan dan infrastruktur transportasi Provinsi Jawa Timur.

**Copyright:** © Hilmyfar and Rivan (2025)

## Ringkasan
- Peta interaktif berbasis Leaflet yang menampilkan koridor TransJatim, halte, infrastruktur, jaringan jalan, dan layer transportasi lainnya.
- Basemap default: Esri Topographic (`World_Topo_Map`).

## Cara Menjalankan
1. Buka file `index.html` di browser (double-click atau drag ke browser). Untuk pengembangan lokal sebaiknya gunakan server HTTP (mis. `python -m http.server`) agar pemanggilan file GeoJSON/scrip berjalan konsisten.

  Contoh (macOS / zsh) menjalankan server di folder project:

  ```bash
  python3 -m http.server 8000
  # lalu buka http://localhost:8000 di browser
  ```

2. Gunakan panel samping untuk menyalakan/mematikan layer.

## Catatan
- Data GeoJSON disertakan di folder `data/` dan dimuat via `<script>` pada `index.html`.
- Pastikan koneksi internet aktif untuk memuat tile service (Esri, Google) dan CDN Leaflet.

## Lisensi & Attribution
- Semua tile map dan sumber pihak ketiga memerlukan atribusi sesuai provider (Esri, OpenStreetMap, Google, CARTO, dsb.).
- Konten peta (data) dan kode di-reuse oleh pemilik: Hilmyfar dan Rivan (2025).

---
Terakhir diperbarui: 2025
