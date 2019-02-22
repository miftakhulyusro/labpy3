# latihan03


Tugas 03 Penjelasan alur algoritma program latihan1.py, latihan2.py


1. Latihan Pertama

Menampilkan bilangan acak yang lebih kecil dari 0,5 serta menggunakan syntac perulangan dan random

1. Buka aplikasi Pycharm
2. Buka New Scratch File
3. ketik syntac Print('Bilangan Acak Yang Lebih Kecil Dari 0,5')
Kita gunakan sebagai Judul dari program yang akan kita buat

![gambar pycharm1](https://user-images.githubusercontent.com/46748866/53256422-6e31eb80-36fa-11e9-9406-0a2427a13daf.png)


4. Ketik Syntax :
import random
n = int(input("masukan Nilai N:"))

a. Import random
berfungsi meng-acak hasil dari perulangan yang akan kita buat

b. n = int(input("masukan Nilai N:"))
sedangkan untuk syntac ini kita gunakan untuk memasukan Variabel pada nilai N


5. Ketik Syntax :
a=0
for c in range(n) :

a. a=0
sebagai Variabel yang mana nanti gunakan untuk mengurutkan data

b. for c in range(n)
sebagai perintah perulangan data dari variabel (N)

6. ketik Syntax :
a+= 1
b = random.uniform(.0,.5)
print('data ke:',a,'==>',b)
print("selesai")

a. a+= 1 :
sebagai bentuk perintah untuk mengurutkan data yang kita buat sebelumnya

b. b = random.uniform(.0,.5) :
digunakan sebagai variabel peng-acakan pada nilai (b)

c. print('data ke:',a,'==>',b) :
digunakan untuk memunculkan hasil data (a) pengurutan dan (b) pengacakan

d. print("selesai") :
memunculkan pernyataan bahwa hasil telah di temukan dan selesai

Dan jalankan syntax yang sudah di buat dengan menu RUN yang terdapat pada aplikasi Pycharm

![gambar1](https://user-images.githubusercontent.com/46748866/53256640-ed272400-36fa-11e9-9f50-58324b02e9df.png)


2. Latihan Kedua
Mencari bilangan dan menampilkan bilangan terbesar dari (n) sebuah data yang diinputkan.
Dan Memasukkan angka 0 untuk berhenti.

1. Ketikan Syntax :
print('====== Menentukan Bilangan Terbesar ======')
max=0
while True:
a=int(input('Masukkan bilangan = '))
if max < a
max = a
if a==0:
break
print('Bilangan terbesarnya adalah = ',max)

a. print('====== Menentukan Bilangan Terbesar ======') :
Digunakan untuk memberikan judul dari program yang akan dibuat

b. max=0
Di gunakan untuk memberikan varibel pada max

c. while True:
bentuk syntax Perulangan

d. a=int(input('Masukkan bilangan = '))
di gunakan untuk memasukan bilangan variabel pada nilai (a)

e. if max < a
f. max = a
Di gunakan sebagai penegasan bahwa jika max lebih kecil dari nilai(a) maka max = nilai(a)

g. if a==0:
h. break
dan ini di gunakan untuk perintah apabila nilai (a) di isi (0) maka pencarian nilai berhenti dengan menggunakan break

i. print('Bilangan terbesarnya adalah = ',max)
dan perintah ini untuk menampilkan hasil bilangan yang dimasukan dan terbesar

Pilih menu Run pada menu Pycharm untuk menjalankan hasil dari syntax yang kita buat

![gambar1](https://user-images.githubusercontent.com/46748866/53256640-ed272400-36fa-11e9-9f50-58324b02e9df.png)


3. Latihan Ketiga

Membuat program sederhana dengan perulangan: "program1".py

1. Seorang pengusaha menginvestasikan uang untuk memulai usahanya dengan modal awal 100 juta,
2. pada bulan pertama dan kedua belum mendapatkan laba.
3. pada bulan ketiga baru mulai mendapatkan laba sebesar 1%
4. dan pada bulan ke 5, pendapatan meningkat 5%,
5. selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%
6. sehingga laba menjadi 3%. 7. Hitung total keuntungan selama 8 bulan berjalan usahanya.*

1.Ketikan syntax :

x=100000000
sum=0 y=0
lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) .5, int(x) * .5, int(x) * .5, int(x) .2]

print('modal awal seorang pengusaha :',x)

for i in lb :
sum=sum+i
y+=1
print('laba bulan ke-', y ,'sebesar :',i)

print('total laba yang di dapet adalah :',sum)

untitled3 1

a. x=100000000
di gunakan untuk meberikan variabel pada nilai(x) sebagai modal awal

b. sum=0
Digunakan untuk memberikan variabel pada syntax penjumlahan(Sum)

c. y=0
Digunakan untuk memberikan variabel pada nilai (y) untuk mengurutkan keterangan laba pada bulan

d. *lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) .5, int(x) * .5, int(x) * .5, int(x) .2]
menerangkan bahwa (lb) = hasil atau persenan dari modal awal

e. print('modal awal seorang pengusaha :',x)
menampilkan hasil dari hitungan laba di atas

f. for i in lb :
syntax ini berfungsi mengulang dan memasukan laba ke dalam nilai(i)

g. sum=sum+i
menjumlah kan nilai laba yang berada di dalam nilai(i)

h. y+=1
mengurutkan nilai pada laba,

i. print('laba bulan ke-', y ,'sebesar :',i)
menampilkan hasil dari variabel yang di dapat

j. print('total laba yang di dapet adalah :',sum)
menampilkan hasil jumlahan variabel atau hasil laba

Pilih menu Run pada menu Pycharm untuk menjalankan hasil dari syntax yang kita buat

![gambar3](https://user-images.githubusercontent.com/46748866/53256815-60c93100-36fb-11e9-8d56-4e4b92158a3a.png)


SEKIAN TUGAS DARI SAYA

Miftakhul Yusro from TI. 18. B1.

----------Terima Kasih-----------