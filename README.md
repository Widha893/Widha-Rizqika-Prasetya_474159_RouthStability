# Widha-Rizqika-Prasetya_474159_RouthStability

Program di atas adalah program Python yang digunakan untuk menghitung kestabilan sistem dengan menggunakan kriteria kestabilan Routh. Program ini memanfaatkan modul NumPy untuk melakukan operasi pada matriks.

Program ini terdiri dari beberapa fungsi, yaitu:

1. calculate_polynomial(coefficients, s): Fungsi ini digunakan untuk menghitung nilai dari polinomial untuk suatu nilai s yang diberikan. Fungsi ini menerima dua parameter, yaitu koefisien polinomial (coefficients) dan nilai s. Fungsi ini mengembalikan nilai dari polinomial untuk nilai s yang diberikan.
2. create_routh_table(coefficients, K): Fungsi ini digunakan untuk membuat tabel Routh untuk suatu polinomial dan nilai K tertentu. Fungsi ini menerima dua parameter, yaitu koefisien polinomial (coefficients) dan nilai K. Fungsi ini mengembalikan tabel Routh dalam bentuk array NumPy.
3. is_system_stable(routh_table): Fungsi ini digunakan untuk menentukan apakah sistem tersebut stabil atau tidak berdasarkan tabel Routh yang diberikan. Fungsi ini menerima satu parameter, yaitu tabel Routh. Fungsi ini mengembalikan nilai True jika sistem tersebut stabil, dan False jika sistem tersebut tidak stabil. 

Pada program utama, terdapat beberapa langkah yang dilakukan:

1. Pertama, kita tentukan koefisien polinomial (coefficients) dan nilai K awal.
2. Kemudian, kita hitung nilai polinomial untuk suatu nilai s tertentu dengan menggunakan fungsi calculate_polynomial().
3. Selanjutnya, kita buat tabel Routh untuk koefisien polinomial dan nilai K tertentu dengan menggunakan fungsi create_routh_table(). Hasil tabel Routh akan ditampilkan pada layar.
Setelah itu, kita tentukan apakah sistem tersebut stabil atau tidak dengan menggunakan fungsi is_system_stable(). Hasilnya akan ditampilkan pada layar.
4. Selanjutnya, kita minta pengguna memasukkan nilai K baru. Setelah itu, kita buat tabel Routh baru dengan menggunakan fungsi create_routh_table() dengan nilai K baru. Hasil tabel Routh yang baru akan ditampilkan pada layar.
5. Akhirnya, kita tentukan apakah sistem tersebut stabil atau tidak untuk nilai K baru dengan menggunakan fungsi is_system_stable(). Hasilnya akan ditampilkan pada layar.