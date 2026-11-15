# kbbi-stardict-xteink
Offline Indonesian Dictionary (KBBI) in StarDict format  optimized &amp; ready for Xteink X4 Pro and KOReader.

# Kamus Besar Bahasa Indonesia (KBBI) - StarDict Format
**Lightweight & Compatible for Xteink X4 Pro (CrossPoint/CrossInk) & KOReader**

---

Kamus Besar Bahasa Indonesia (KBBI) offline dalam format StarDict (`.ifo`, `.idx`, `.dict.dz`). File ini telah dioptimasi, diperbaiki struktur indeksnya, dan dikompresi ulang agar ringan serta kompatibel sepenuhnya dengan perangkat e-reader berkapasitas RAM terbatas seperti Xteink X4 Pro.

# Isi File
* `kbbi_fixed.ifo` — Metadata dan konfigurasi kamus
* `kbbi_fixed.idx` — Indeks kata kunci yang telah dirampingkan (~1.3 MB)
* `kbbi_fixed.dict.dz` — Database definisi terkompresi beserta pemenggalan suku kata (~2.6 MB)

# Cara Pemasangan di Xteink X4 Pro
1. Unduh seluruh file di repository ini (klik tombol hijau Code → Download ZIP, lalu ekstrak).
2. Buka aplikasi pendamping Xteink atau akses kartu SD perangkat.
3. Masuk ke folder `dictionaries`, lalu buat folder baru (misalnya: `kbbi`).
4. Masukkan file (`kbbi_fixed.ifo`, `kbbi_fixed.idx`, dan `kbbi_fixed.dict.dz`) ke dalam folder tersebut. *(Jangan masukkan file lain atau mengekstrak `.dict.dz` secara manual).*
5. Di perangkat Xteink, masuk ke menu **Current dictionary** → pilih **KBBI** → tekan **Tap to prepare**.
6. Setelah status berubah menjadi **Ready**, ketuk satu kali lagi hingga muncul keterangan **Selected**.

---


### 💡 Catatan / Notes
* **Credits:** Sumber basis data dari `kbbi3_dekos`, dikonversi ulang dan dioptimasi menggunakan PyGlossary & `dictzip`.

