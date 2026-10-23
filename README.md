# Pertemuan 10 - String dan Pengolahan Teks

Nama: Aulia Citra Aljazeera Jan's
NIM: 2225250012
Kelas: 3F

## Tujuan
Mengolah dan menormalisasi data teks menggunakan string Python, termasuk membersihkan spasi, menyeragamkan huruf, memisahkan dan menggabungkan kata, serta membuat inisial.

## Isi Repositori
- latihan/01_dasar_string.py
- latihan/02_indeks_slicing.py
- latihan/03_method_string.py
- latihan/04_bersihkan_teks.py
- latihan/05_split_join.py
- latihan/06_pencarian_kata.py
- tugas/normalisasi_data_mahasiswa.py

## Cara Menjalankan
1. Buka folder proyek di VS Code.
2. Pilih interpreter Python 3.
3. Buka file Python yang ingin dijalankan.
4. Klik kanan pada kode, lalu pilih Run Python File in Terminal.
5. Untuk program tugas, masukkan nama dan kode kelas di terminal, lalu tekan Enter setelah setiap input.

Alternatif melalui terminal dari folder utama proyek:
python tugas/normalisasi_data_mahasiswa.py

## Algoritma
1. Menerima input nama lengkap dan kode kelas.
2. Membersihkan spasi awal dan akhir nama dengan strip().
3. Memisahkan nama dengan split(), lalu menggabungkannya dengan satu spasi menggunakan join().
4. Mengubah nama menjadi title case dengan title().
5. Mengambil huruf pertama setiap kata untuk membentuk inisial.
6. Membersihkan kode kelas, mengubahnya menjadi huruf besar, dan menggabungkan kata dengan tanda hubung.
7. Menghitung jumlah kata pada nama menggunakan len() dan split().
8. Menampilkan nama bersih, kode kelas, jumlah kata, dan inisial.

## Hasil Pengujian
| Input nama | Input kode | Hasil yang diharapkan | Hasil aktual | Status |
|---|---|---|---|---|
| aan hendrayana | pmat a 2026 | Aan Hendrayana; PMAT-A-2026; 2; AH | Aan Hendrayana; PMAT-A-2026; 2; AH | Lulus |
| fATHIYYAH mUTHMAINNAH | kelas b | Fathiyyah Muthmainnah; KELAS-B; 2; FM | Fathiyyah Muthmainnah; KELAS-B; 2; FM | Lulus |
| BUDI | pmtk 01 | Budi; PMTK-01; 1; B | Budi; PMTK-01; 1; B | Lulus |
| siti nur aisyah | kelas c | Siti Nur Aisyah; KELAS-C; 3; SNA | Siti Nur Aisyah; KELAS-C; 3; SNA | Lulus |

Urutan hasil pada tabel: nama bersih; kode kelas; jumlah kata; inisial.
Pengujian nama Siti dengan satu spasi di awal dan akhir berhasil. Input siti nur aisyah menghasilkan nama bersih Siti Nur Aisyah, kode kelas KELAS-C, jumlah kata 3, dan inisial SNA.

## Refleksi
Dari latihan ini, saya mempelajari bahwa perbedaan huruf besar, huruf kecil, dan spasi dapat membuat format data tidak konsisten. strip() membersihkan spasi awal dan akhir, sedangkan split() dan join() merapikan spasi di tengah. title() digunakan untuk format nama dan upper() untuk format kode kelas.

## Sumber dan Bantuan
- Bahan Ajar Pertemuan 10: String dan Pengolahan Teks dalam Python.
- ChatGPT digunakan untuk membantu memahami langkah praktik, menjelaskan kode, dan menyusun dokumentasi.