# Kamus KBBI (StarDict) untuk Xteink X4 Pro

Kamus Besar Bahasa Indonesia (KBBI) offline dalam format **StarDict** (`.ifo`, `.idx`, `.dict.dz`) yang telah dioptimalkan dan diuji berjalan lancar di perangkat e-reader **Xteink X4 Pro**.

## Pembaruan Terbaru (KBBI Edisi VI)
* **Basis Data Terbaru:** Menggunakan dataset **KBBI Edisi VI** dengan total **194.692 lema**.
* **Tampilan Bersih:** Seluruh tag HTML telah dibersihkan menjadi teks polos yang rapi dan mudah dibaca di layar E-Ink.
* **Kompresi Random Access (`dictzip`):** Dikompilasi menggunakan header `dictzip` standar agar ringan saat diindeks dan tidak membebani kapasitas RAM perangkat.

---

## Struktur Repositori

| Folder | Edisi Kamus | Jumlah Lema | Keterangan |
| :--- | :--- | :--- | :--- |
| `/kbbi-vi` | **KBBI Edisi VI** *(Direkomendasikan)* | ~194.692 | Versi terbaru dan terlengkap dengan format teks bersih. |
| `/kbbi-v` | KBBI Edisi V *(Arsip)* | ~112.000 | Versi rilis awal dengan ukuran berkas indeks lebih kecil. |

---

## Cara Instalasi di Xteink X4 Pro

1. Unduh paket rilis terbaru (`kbbi_vi_stardict.zip`) pada halaman **Releases**, atau unduh seluruh isi folder `/kbbi-vi`.
2. Pastikan Anda hanya menyalin **3 berkas inti** berikut (jangan menyertakan berkas lain):
   * `kbbi_vi.ifo`
   * `kbbi_vi.idx`
   * `kbbi_vi.dict.dz`
3. Hubungkan kartu microSD Xteink X4 Pro ke komputer/ponsel, lalu tempelkan ketiga berkas tersebut **langsung** di dalam folder `dictionaries` (bukan di dalam sub-folder baru).
4. Pasang kembali microSD ke perangkat **Xteink X4 Pro**.
5. Buka menu pengaturan kamus di perangkat, lalu pilih **Prepare / Import** dan tunggu hingga proses indeks selesai.
6. Buka buku e-book Anda dan ketuk kata apa pun untuk menampilkan definisi KBBI VI secara offline.

---

## Catatan Teknis & Troubleshooting
* **Pesan *Unsupported Format* atau *Corrupt*:** Pastikan ekstensi berkas tidak berubah saat diunduh (misalnya menjadi `.dict.dz.gz`) dan tidak ada berkas sisa seperti `.txt` atau `.json` di dalam folder `dictionaries`.
* **Kompatibilitas Perangkat Lain:** Karena menggunakan spesifikasi standar StarDict v2.4.2 (`sametypesequence=m`), kamus ini juga kompatibel dengan aplikasi pembaca lain seperti **KOReader**, **Moon+ Reader**, **GoldenDict**, dan perangkat e-reader berbasis Android/Linux lainnya.

---

## Atribusi & Lisensi
* Seluruh isi lema dan definisi merupakan hak cipta milik **Badan Pengembangan dan Pembinaan Bahasa, Kementerian Pendidikan Dasar dan Menengah Republik Indonesia**.
* Paket konversi format StarDict ini dibagikan secara gratis khusus untuk **keperluan edukasi, literasi, dan penggunaan pribadi (non-komersial)**.
