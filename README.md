
# Family 100 Game

**Family 100** adalah sebuah game berbasis web yang terinspirasi dari acara kuis populer di Indonesia. Game ini dirancang untuk dimainkan oleh dua tim, dengan tujuan menjawab pertanyaan dan mengumpulkan poin terbanyak.

## Fitur

1.  **Permainan Tim**: Dua tim bersaing untuk mendapatkan poin berdasarkan jawaban dari pertanyaan yang disediakan.
2.  **Tampilan Skor**: Skor kedua tim ditampilkan secara real-time.
3.  **Tampilan Jawaban**: Jawaban yang benar akan ditampilkan setelah dipilih.
4.  **Strike**: Jika tim salah menjawab tiga kali, giliran akan berpindah ke tim lawan.
5.  **Ganti Pertanyaan**: Setelah semua jawaban dari sebuah pertanyaan terungkap, tim dapat melanjutkan ke pertanyaan berikutnya.
6.  **Game Over**: Saat semua pertanyaan selesai, game akan berakhir dan tim pemenang akan diumumkan.
7.  **Reset Game**: Pemain dapat mereset game untuk memulai ulang dari awal.

## Cara Bermain

1.  **Persiapan**: Setiap tim memiliki skor awal 0, dan permainan dimulai dengan pertanyaan pertama yang ditampilkan.
2.  **Jawaban**: Pemain harus mengklik jawaban yang benar dari daftar yang tersembunyi.
3.  **Ganti Tim**: Jika ingin mengganti giliran tim, klik tombol "Ganti Tim".
4.  **Strike**: Jika tim memberikan jawaban yang salah, klik tombol "Strike". Setelah 3 strike, giliran akan berpindah ke tim lawan.
5.  **Soal Berikutnya**: Setelah semua jawaban untuk satu pertanyaan terungkap, klik "Soal Berikutnya" untuk lanjut ke pertanyaan berikutnya.
6.  **Game Over**: Setelah semua pertanyaan selesai, game over akan ditampilkan dan pemenang diumumkan.
7.  **Reset Game**: Untuk memulai permainan baru, klik tombol "Reset Game".

## Struktur File

-   **HTML (index.html)**: Struktur halaman game, yang memuat skor tim, pertanyaan, jawaban, dan kontrol permainan.
-   **CSS (Embedded in HTML)**: Mengatur tampilan visual game, termasuk tata letak, warna, dan gaya elemen.
-   **JavaScript (Embedded in HTML)**: Logika permainan, seperti pengelolaan skor, giliran tim, dan validasi jawaban.

## Daftar Pertanyaan

Berikut ini beberapa pertanyaan yang telah disediakan di dalam game:

1.  **Sebutkan buah yang berwarna merah!**
    
    -   Apel: 35 poin
    -   Semangka: 25 poin
    -   Strawberry: 20 poin
    -   Naga: 15 poin
    -   Delima: 5 poin
2.  **Sebutkan hewan yang bisa terbang!**
    
    -   Burung: 40 poin
    -   Kupu-kupu: 25 poin
    -   Lebah: 15 poin
    -   Kelelawar: 12 poin
    -   Capung: 8 poin
3.  **Sebutkan profesi yang bekerja di rumah sakit!**
    
    -   Dokter: 35 poin
    -   Perawat: 30 poin
    -   Apoteker: 15 poin
    -   Satpam: 12 poin
    -   Cleaning Service: 8 poin

Pengguna dapat menambahkan pertanyaan baru dengan mengikuti format yang sama di bagian array `questions` dalam JavaScript.

## Cara Menjalankan

1.  Download atau salin kode HTML yang ada di atas.
2.  Buka file HTML di browser untuk memulai permainan.
3.  Anda dapat mengedit pertanyaan dan jawabannya sesuai keinginan dengan menambahkan data baru ke array `questions`.

Selamat bermain! 
