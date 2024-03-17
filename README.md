# Yuyun Nailufar
## 2308107010066

# Konversi Bilangan

<stdio.h> berisi file header yang berfungsi untuk menginput dan mengoutputkan data
![Screenshot 2024-03-17 221554](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/d20d6a9d-88c6-4e9b-98b5-3a2d40ad63af)

int pilihan; digunakan sebagai variabel pilihan tipe integer untuk menyimpan menu pilihan sesuai dengan soal yang diberikan yaitu bilangan desimal, biner dan oktal.

![Screenshot 2024-03-17 221607](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/7c40efda-f220-441c-87cc-54eb33a68bd7)


memanfaatkan metode switch case sesuai dengan apa yang diperintahkan soal

![Screenshot 2024-03-17 221615](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/d4a1faeb-cbde-4370-8edf-690d95b6d1f5)


memasukkan beberapa input yang akan menjadi pilihan di konversi bilangan pada metode switch case

![Screenshot 2024-03-17 221624](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/94c8cbc4-2e5f-434a-889f-bfb504a94e51)




## case 1 konversi bilangan desimal ke bilangan biner

pertama program akan meminta user untuk memasukkan bilangan desimal. Bilangan desimal tersebut kemudian disimpan dalam variabel "desimal". Kemudian, kode program akan menganalisa variabel "biner" dengan nilai 0 untuk menyimpan hasil konversi bilangan biner dan variabel "i" dengan nilai 1 untuk digunakan sebagai pangkat 2. Program melakukan perulangan while selama nilai "desimal" lebih besar dari 0. Di dalam perulangan, program akan Menghitung nilai biner dengan menambahkan sisa pembagian "desimal" dengan 2 dikalikan dengan "i". Membagi "desimal" dengan 2 untuk mendapatkan nilai desimal berikutnya. Mengalikan "i" dengan 10 untuk menaikkan pangkat 2. Setelah perulangan selesai, program akan menampilkan nilai "biner" sebagai hasil konversi bilangan desimal ke biner.

![Screenshot 2024-03-17 221641](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/b0424994-cda2-47b9-8711-73007fe5bd8a)

## case 2 konversi bilangan biner ke bilangan desimal
Program meminta user untuk memasukkan bilangan biner yang disimpan dalam variabel "biner". Lalu, variabel akan menganalisa variabel "desimal" untuk menyimpan hasil konversi bilangan desimal. "j" untuk melacak pangkat 2 dalam sistem bilangan biner. Perulangan "while" dilakukan selama nilai "biner" lebih besar dari 0. Sisa pembagian "biner" dengan 10 ("biner % 10") akan menghasilkan digit desimal. Digit desimal ditambahkan ke variabel "desimal" dengan dikalikan "j". Nilai "j" menentukan nilai tempat digit desimal. "biner" dibagi dengan 10 ("biner /= 10") untuk mendapatkan nilai biner berikutnya. "j" dikalikan dengan 2 ("j *= 2") untuk menaikkan pangkat 2. Setelah perulangan selesai, nilai "desimal" berisi hasil konversi bilangan biner ke desimal.

![Screenshot 2024-03-17 222446](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/aa40d4c4-794a-40c2-922a-80fc3bed8408)

## case 3 konversi bilangan desimal ke bilangan oktal

Program meminta user untuk memasukkan bilangan desimal yang disimpan dalam variabel "desimal". lalu variabel akan menganalisa variabel "oktal" untuk menyimpan hasil konversi bilangan oktal. "k" untuk melacak pangkat 8 dalam sistem bilangan oktal. Perulangan "while" dilakukan selama nilai "desimal" lebih besar dari 0. Sisa pembagian "desimal" dengan 8 ("desimal % 8") menghasilkan digit oktal. Digit oktal ditambahkan ke variabel "oktal" dengan dikalikan "k". Nilai "k" menentukan nilai tempat digit oktal. "desimal" dibagi dengan 8 ("desimal /= 8") untuk mendapatkan nilai desimal berikutnya. "k" dikalikan dengan 10 ("k *= 10") untuk menaikkan pangkat 8. Setelah perulangan selesai, nilai "oktal" berisi hasil konversi bilangan desimal ke oktal.

![Screenshot 2024-03-17 222841](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/fc0a7bce-2204-447d-8c1b-66b4dd9e61c8)

## case 4 konversi bilangan oktal ke bilangan desimal

Program meminta user untuk memasukkan bilangan oktal yang disimpan dalam variabel "oktal". Lalu variabel akan menganalisa variabel "desimal" untuk menyimpan hasil konversi bilangan desimal. "l" untuk melacak pangkat 8 dalam sistem bilangan oktal. Perulangan "while" dilakukan selama nilai "oktal" lebih besar dari 0. Sisa pembagian "oktal" dengan 10 ("oktal % 10") menghasilkan digit desimal.
Digit desimal ditambahkan ke variabel "desimal" dengan dikalikan "l". Nilai "l" menentukan nilai tempat digit desimal. "oktal" dibagi dengan 10 ("oktal /= 10") untuk mendapatkan nilai oktal berikutnya. "l" dikalikan dengan 8 ("l *= 8") untuk menaikkan pangkat 8. Setelah perulangan selesai, nilai "desimal" berisi hasil konversi bilangan oktal ke desimal.

![Screenshot 2024-03-17 223333](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/66aef1a9-2a2e-4e18-86c7-e723cd3b10e4)

default digunakan untuk menangkap semua input yang tidak tercakup dalam pernyataan yang ada pada case sebelumnya. Dalam kode ini, jika pengguna memasukkan input yang bukan 1, 2, 3, atau 4, maka pernyataan default akan dieksekusi. Di dalam pernyataan default, program akan mencetak pesan "tidak valid!" ke layar. Hal ini bertujuan untuk memberi tahu pengguna bahwa input mereka tidak valid dan program tidak dapat memprosesnya. Setelah mencetak pesan "tidak valid!", program akan mengembalikan nilai 0. Nilai 0 menandakan bahwa program telah selesai dengan sukses.

![Screenshot 2024-03-17 223615](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/2f79b344-36df-4bda-99de-9f502b77c788)

# tahun kabisat

#include <stdio.h> menyediakan file header stdio.h yang berisi definisi fungsi-fungsi standar untuk operasi input dan output, seperti printf() dan scanf(). #include <stdlib.h> menyediakan file header stdlib.h. yang berisi definisi fungsi-fungsi standar untuk operasi memori dan konversi data.  int main() sebagai fungsi utama dalam program C. int tahun; yaitu variabel tahun sebagai tipe data int. Tipe data int digunakan untuk menyimpan bilangan bulat.

![Screenshot 2024-03-17 224039](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/9e4a3ca3-6930-4b2f-9d71-a0c8bba0efe5)

//input tahun adalah komentar yang digunakan untuk menjelaskan kode. Komentar ini menjelaskan bahwa kode berikut digunakan untuk meminta input tahun dari user. printf("Masukkan tahun: "); Baris ini menggunakan fungsi printf() untuk mencetak string "Masukkan tahun: " ke layar. Fungsi printf() digunakan untuk menampilkan data ke layar. scanf("%d", &tahun); "%d" sebagai specifier integer dan &tahun sebagai tempat untu menyimpan alamat variabel dalam memori.

![Screenshot 2024-03-17 224131](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/bde2099c-bcce-4d60-b6c4-503058dbb75a)

Perulangan while diguakan untuk terus meminta pengguna memasukkan tahun jika tahun yang dimasukkan tidak valid. Perulangan while akan terus dijalankan selama kondisi di dalam kurung () bernilai benar. tahun < 1000

kode tersebut memeriksa apakah tahun yang dimasukkan kurang dari 1000. Jika ya, maka tahun tersebut tidak valid. tahun > 9999 kode tersebut memeriksa apakah tahun yang dimasukkan lebih dari 9999. Jika ya, maka tahun tersebut tidak valid. printf("Tahun yang dimasukkan tidak valid. Masukkan kembali tahun (4 angka): "); printf() sebagai pencetak output "Tahun yang dimasukkan tidak valid. Masukkan kembali tahun (4 angka): " ke layar. scanf("%d", &tahun); fungsi scanf() untuk membaca input tahun dari pengguna dan menyimpannya dalam variabel tahun.

![Screenshot 2024-03-17 224438](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/8f63114d-6949-41ea-a4fb-b3970f59d657)

int variabel kabisat sebagai tipe data int. Variabel kabisat digunakan untuk menyimpan informasi apakah tahun kabisat (1) atau bukan (0). if (tahun % 4 == 0)  if untuk mengecek apakah tahun yang dimasukkan habis dibagi 4. Jika ya, maka tahun tersebut adalah tahun kabisat. kabisat = 1; untuk menetapkan nilai variabel kabisat menjadi 1 jika tahun yang dimasukkan habis dibagi 4. if (tahun % 100 == 0 && tahun % 400 != 0) pernyataan if bertingkat untuk mengecek apakah tahun yang dimasukkan habis dibagi 100 dan tidak habis dibagi 400. kabisat = 0; untuk menetapkan nilai variabel kabisat menjadi 0 jika tahun yang dimasukkan habis dibagi 100 dan tidak habis dibagi 400.

![Screenshot 2024-03-17 224735](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/612f69ef-7304-4f02-938b-5105fa68e38b)

menggunakan pernyataan if untuk mengecek nilai variabel kabisat. Jika nilai variabel kabisat 1 (tahun kabisat), maka kode di dalam blok if akan dijalankan. printf("Tahun %d adalah tahun kabisat\n", tahun); menggunakan fungsi printf() untuk mencetak string "Tahun %d adalah tahun kabisat\n" ke layar. String tersebut berisi nilai variabel tahun. Else digunakan untuk menjalankan kode di dalam blok else jika nilai variabel kabisat bukan 1 (bukan tahun kabisat). printf("Tahun %d bukan tahun kabisat\n", tahun); menggunakan fungsi printf() untuk mencetak string "Tahun %d bukan tahun kabisat\n" ke layar. String tersebut berisi nilai variabel tahun. return 0; digunakan untuk mengakhiri program dan mengembalikan nilai 0 yang menandakan bahwa program telah selesai dengan sukses.

![Screenshot 2024-03-17 224946](https://github.com/Yuyunnailufarr/2308107010066/assets/163745927/c17a0086-669b-4867-bdb4-678c47d03a89)



