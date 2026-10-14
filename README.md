
# Generator Deskripsi Rapor

Aplikasi web sederhana untuk membantu guru membuat deskripsi capaian akademik siswa secara otomatis menggunakan ChatGPT.

## Fitur

- **Akses cepat ke ChatGPT** melalui satu tombol.
- **Prompt interaktif** yang memandu guru memasukkan data secara bertahap.
- **Input data siswa** berupa nama, nilai Penilaian Harian 1 (S1), Penilaian Harian 2 (S2), dan rata-rata nilai harian (H).
- **Deskripsi personal** berdasarkan capaian setiap siswa.
- **Bahasa formal dan ringkas** yang sesuai untuk kebutuhan rapor sekolah.
- **Variasi deskripsi** agar kalimat antarsiswa tidak terkesan menggunakan template.
- **Tanpa backend** dan tanpa database.
- **Tampilan responsif** untuk desktop maupun perangkat seluler.

## Cara Kerja

1. Guru membuka halaman aplikasi.
2. Guru mengeklik tombol **Buat Deskripsi Rapor**.
3. ChatGPT terbuka dengan prompt yang sudah disiapkan.
4. ChatGPT menanyakan kelas, mata pelajaran, nama siswa, dan data nilai secara bertahap.
5. Setelah semua data lengkap, ChatGPT menyusun deskripsi capaian setiap siswa.
6. Guru menyalin hasilnya untuk digunakan dalam pengisian rapor.

## Format Data

Data siswa dapat dimasukkan menggunakan format berikut:

    Nomor|Nama Siswa|Nilai

Data nilai dimasukkan secara terpisah sesuai urutan siswa:

- **S1:** Nilai Penilaian Harian 1 (PH1).
- **S2:** Nilai Penilaian Harian 2 (PH2).
- **H:** Rata-rata nilai harian.

Pastikan urutan siswa konsisten pada setiap kelompok data.

## Aturan Pembuatan Deskripsi

Deskripsi yang dihasilkan mengikuti ketentuan berikut:

1. Setiap deskripsi diawali dengan kata "Ananda".
2. Deskripsi berfokus pada materi Bab 1.
3. Angka nilai tidak dicantumkan dalam deskripsi.
4. Kalimat dibuat singkat, formal, dan mudah dipahami.
5. Struktur kalimat divariasikan agar tidak monoton.
6. Capaian dijelaskan secara objektif dan proporsional.
7. Siswa yang masih memerlukan penguatan materi dideskripsikan secara positif.
8. Tidak menambahkan klaim tentang sikap, perilaku, atau karakter tanpa data pendukung.

## Struktur Proyek

    .
    ├── index.html
    └── README.md

Seluruh tampilan, CSS, JavaScript, dan prompt berada dalam satu file `index.html`.

## Teknologi

- HTML5
- CSS3
- JavaScript
- ChatGPT URL Query

Tidak diperlukan framework, instalasi dependensi, backend, maupun database.

## Cara Menjalankan

1. Simpan kode aplikasi sebagai `index.html`.
2. Buka file tersebut menggunakan browser.
3. Klik tombol **Buat Deskripsi Holistik**.
4. Pastikan koneksi internet tersedia untuk menggunakan ChatGPT.

## Deployment

Aplikasi dapat dihosting secara gratis melalui layanan hosting statis, seperti:

- [Vercel](https://vercel.com/)
- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)

Cukup unggah `index.html` beserta `README.md` ke repositori atau layanan hosting yang digunakan.

## Catatan

- Aplikasi ini merupakan antarmuka untuk membuka ChatGPT dengan prompt yang telah disiapkan, bukan model AI mandiri.
- Penggunaan ChatGPT memerlukan akses ke layanan ChatGPT dan dapat bergantung pada akun serta batas penggunaan pengguna.
- Hasil deskripsi perlu diperiksa oleh guru untuk memastikan kesesuaian dengan materi pembelajaran dan kondisi siswa.
- Jangan memasukkan informasi pribadi siswa yang tidak diperlukan.
- Nilai yang diberikan tetap menjadi tanggung jawab guru untuk diverifikasi sebelum digunakan dalam rapor.

## Lisensi

Bebas digunakan dan dimodifikasi untuk kebutuhan pendidikan. Jika proyek dikembangkan lebih lanjut atau didistribusikan kembali, sesuaikan ketentuan lisensi dengan kebutuhan pengembang.
