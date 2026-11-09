# Simulasi Tabungan Divisi Funding — KSPPS Syirkah Kebaikan Indonesia

Simulator tabungan untuk enam produk Divisi Funding:

| Produk | Status | Di website publik |
|---|---|---|
| Tabungan Pendidikan Anak | Disetujui | Bisa diatur (setoran Rp100.000–Rp5 jt/bulan, 3–12 tahun) |
| Tabungan Qurban | Disetujui | Bisa diatur (setoran min. Rp220.000/bulan, 3–11 bulan otomatis) |
| Tabungan Nikah | Disetujui | Bisa diatur (setoran awal min. Rp10 jt, bulanan min. Rp1 jt; wajib surat keterangan menikah dari KUA) |
| Tabungan Hari Pensiun | Draf | Contoh tetap, terkunci |
| Tabungan DP Rumah (Rumany & Rumsy) | Draf | Contoh tetap, terkunci |
| Deposito Proyek | Draf | Contoh tetap, terkunci |

Rumus dan angka mengikuti file **CR – Funding** dari Credit Risk:
margin bulan t = tarif × (setoran bulan t + saldo bulan t−1). Pada Pendidikan Anak,
tingkat 2% dan 3% dihitung sebagai 2× dan 3× margin dasar 1%. Pada Qurban, lama menabung
adalah bulan pertama saldo mencapai nilai akhir Rp220.000 × 11 bulan (Rp2.567.720), minimal 3 bulan.

Seluruh halaman ada di satu file `index.html`, tanpa dependensi selain font Plus Jakarta Sans dari Google Fonts.

Angka pada halaman ini adalah simulasi. Nilai final mengikuti akad.
