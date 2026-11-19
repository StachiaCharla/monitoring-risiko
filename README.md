# monitoring-risiko

Prototipe website monitoring risiko proyek prioritas.

## Cara menggunakan
1. Buka website melalui GitHub Pages, atau unduh `index.html` lalu buka di browser (Chrome, Safari, Edge).
2. Unggah berkas pada bagian **Unggah Data**: Calculation EWS, Risk Register (RR), Database Dashboard (Excel), dan/atau laporan MONEVA (PDF).
3. Untuk mencoba tanpa data asli, klik **Muat Data Contoh (Dummy)**.

## Fitur
- **Isi Otomatis**: membaca RR dan PDF MONEVA, lalu menyusun isian ALERT, EWS, dan sheet Database Dashboard dalam satu berkas Excel
- Early Warning System (NPV, Cost, Schedule, Current Risk) dengan indikator warna sesuai Index EWS
- Halaman proyek: klik baris EWS untuk melihat ringkasan proyek, Project Economic, Loss & Gain, Waterfall NPV, tren, Risk Movement, mitigasi, dan timeline
- Loss & Gain per penyebab (Potential/Actual) dari Scenario Analysis MONEVA
- Telusur Risiko (drill-down): Zona → Proyek → Kategori Risiko → Risk Event
- Penilaian Profesional (Impact & Probability, penyesuaian Current Risk, mitigasi) dengan analisis otomatis
- Tren NPV dan Risk Exposure (grafik terpisah), Risk Movement dalam satu grafik, Mitigation Plan dan Loss Event, Timeline FID dan pelaporan terakhir
- Pemeriksaan Data otomatis dan Daftar Istilah
- Filter interaktif (klik untuk memfilter seluruh tampilan)
- Riwayat Laporan yang tersimpan di peramban perangkat pengguna

## Keamanan data
Seluruh pengolahan dilakukan di browser pengguna. Berkas yang diunggah **tidak dikirim** ke server mana pun, termasuk GitHub. Repository ini hanya berisi website dan data contoh (dummy).
