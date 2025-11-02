#Menampilkan N Bilangan Acak < 0.5
Latihan 1 
Bilangan Acak Deskripsi Program Program ini menampilkan n bilangan acak yang nilainya lebih kecil dari 0.5. Nilai n ditentukan oleh user saat runtime. Alur Algoritma
Import Library
Import fungsi random dari module random
Input dari User
Program meminta user memasukkan nilai N Nilai N disimpan dalam variabel n
Inisialisasi Variabel
Membuat variabel count dengan nilai awal 0 Variabel ini digunakan untuk menghitung jumlah bilangan yang sudah ditampilkan
Perulangan While
Selama count < n, lakukan:
Generate bilangan acak menggunakan random() Cek apakah bilangan tersebut < 0.5 Jika ya:
Tambah nilai count sebesar 1 Tampilkan bilangan dengan format: data ke: {count} => {angka}
Jika tidak, ulangi generate bilangan baru
Output Akhir
Tampilkan pesan "Selesai"
![alt image](https://github.com/MugiMPambdi/labpy03/blob/e37d89d32cccc5f974346b6a9e4a45c9e3385b2b/Foto/Ss1.png)

#Perhitungan Laba Perbulan
Latihan 2
Perhitungan Laba Usaha 📝 Deskripsi Program Program menghitung total keuntungan seorang pengusaha selama 8 bulan dengan modal awal 100 juta rupiah, dengan persentase laba yang berbeda-beda setiap bulannya. 🔄 Alur Algoritma
Inisialisasi Variabel
modal_awal = 100.000.000 (100 juta rupiah) total_laba = 0
Perulangan For (8 Bulan)
Loop dari bulan 1 sampai bulan 8
Logika Perhitungan Laba per Bulan
Bulan 1-2: Laba 0% (belum dapat laba) Bulan 3-4: Laba 1% dari modal Bulan 5-7: Laba 5% dari modal (naik 4%) Bulan 8: Laba 2% dari modal (turun 3% dari bulan sebelumnya)
Perhitungan
Untuk setiap bulan:
Hitung laba_bulan_ini = modal_awal × (laba_persen / 100) Tambahkan ke total_laba Tampilkan laba bulan tersebut
Output Akhir
Tampilkan total laba selama 8 bulan
![alt image]https://github.com/MugiMPambdi/labpy03/blob/93e2485b8a9ef77c07e57602a0bf2966aeaf5653/Foto/Ss2.png

#saldo habis
Latihan 3 - Simulasi ATM 
Deskripsi Program Program simulasi mesin ATM sederhana yang memungkinkan pengguna untuk menarik uang dari saldo awal Rp 1.000.000 hingga saldo habis atau memilih untuk keluar. Alur Algoritma
Inisialisasi Variabel
saldo = 1.000.000 (saldo awal)
Perulangan While

Selama saldo > 0, lakukan:

Tampilan Menu

Tampilkan saldo saat ini Tampilkan menu:

Tarik Uang

Keluar

Minta user memilih menu
Proses Pilihan Menu Jika pilihan = 1 (Tarik Uang):
Minta input jumlah penarikan Cek apakah jumlah ≤ saldo
Jika ya: kurangi saldo, tampilkan "Penarikan berhasil!" Jika tidak: tampilkan "Saldo tidak cukup!"

Jika pilihan = 2 (Keluar):
Tampilkan pesan terima kasih Keluar dari program (break)
Jika pilihan tidak valid:
Tampilkan pesan error
Pengecekan Saldo Habis
Jika saldo = 0, tampilkan pesan saldo habis dan program berhenti
![alt image]https://github.com/MugiMPambdi/labpy03/blob/aa30c4841f88d9c2df823fda4221981732c44567/Foto/Ss3.png

