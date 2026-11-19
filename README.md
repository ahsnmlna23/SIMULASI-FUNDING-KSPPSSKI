# Simulasi Tabungan Divisi Funding — KSPPS Syirkah Kebaikan Indonesia

Versi 19 Nov 2026. Simulator tabungan Divisi Funding dengan **nisbah bagi hasil 30 : 70** (nasabah : KSPPS) untuk semua tabungan.

| Produk | Status | Di website publik |
|---|---|---|
| Tabungan Pendidikan Anak | Disetujui | Setoran Rp100.000–Rp5 jt/bulan, 1–12 tahun. Bagi hasil 6,95% (1–5 th) / 7,20% (6–8 th) / 7,45% (9–12 th) per tahun |
| Tabungan Qurban | Disetujui | Setoran Rp220.000–Rp2 jt/bulan, 3–11 bulan. Bagi hasil 6,10% per tahun |
| Tabungan Nikah | Disetujui | Setoran awal min. Rp10 jt, bulanan min. Rp1 jt, 1–10 tahun. Bagi hasil 8,40% per tahun; wajib surat keterangan menikah dari KUA |
| Tabungan Hari Pensiun | Draf | Terkunci. Bagi hasil 4,88% / 5,18% / 5,49% per tahun |
| Tabungan DP Rumah (Rumany & Rumsy) | Draf | Contoh tetap, terkunci |
| Deposito Proyek | Draf | Contoh tetap, terkunci |

Cara hitung (sama dengan workbook **CREDIT RISK – FUNDING TABUNGAN**):

- Bagian nasabah 30% × pendapatan dana = bagi hasil per tahun (Pendidikan Anak 1–5 tahun: 30% × 23,17% = 6,95%).
- Bagi hasil per bulan = bagi hasil per tahun ÷ 12 (6,95% ÷ 12 = 0,579%).
- Pendidikan Anak: bagi hasil mulai bulan ke-2, dihitung dari saldo bulan sebelumnya.
- Qurban, Nikah, Pensiun: bagi hasil mulai bulan ke-2, dihitung dari setoran bulan itu + saldo bulan sebelumnya.

Seluruh halaman ada di satu file `index.html`, tanpa dependensi selain font Plus Jakarta Sans dari Google Fonts.

Angka pada halaman ini adalah simulasi. Nilai final mengikuti akad.
