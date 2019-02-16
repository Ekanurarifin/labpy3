# labpy3

# labpy3
1.) Latihan 1 py
ALGORITMA ALUR 
```
a. import random
b. n = int(input("Masukan nilai N : "))
Untuk menginputkan bilangan yang di inginkan
c. for i in range(n) :
Rumus menghitung perulangan sebanyak nilai N
d. a=random.uniform(0.0,0.5)
untuk menampilkan jumalah bilangan terkecil dari 0.0 sampai 0.5 nilai yang di inputkan
e. print ("Data ke : ", i, "=> ", a)
untuk menamnpilkan hasil
f. print("Selesai")
untuk menampilkan hasil teks selesai
```
CODINGAN LATIHAN1PY
```
import random
n = int(input("Masukan nilai N : "))
for i in range(n) :
a=random.uniform(0.0,0.5)
print ("Data ke : ", i, "=> ", a)
    
print("Selesai")
```

![img](https://github.com/Ekanurarifin/labpy3/blob/master/latihan1.PNG)

2.) Latihan 2 py
ALGORITMA ALUR

```
a.) a=1
    max=0
agar bisa masuk ke syarat while max=0 //variable max diisi 0
b.) while a!=0:
looping while dengan syarat a bukan 0
c.) if a>max:
        max=a
proses if untuk mencari nilai terbesar
d.) a=int(input('Masukkan bilangan :'))
input nilai a dengan tipe data integer
e.) if a==0:
    break
jika inputan a diisi angka 0 maka break alias berhenti looping
        
f.) print ('Nilai terbesarya adalah :',max)
print nilai terbesar, variabel max
```

CODINGAN LATIHAN 2 py

```
a=1
max=0
while a!=0:
    if a>max:
        max=a
    a=int(input('Masukkan bilangan :'))
    if a==0:
         break
        
print ('Nilai terbesarya adalah :',max)
```

![img](https://github.com/Ekanurarifin/labpy3/blob/master/latihan2.PNG)




3.) Program 1 py
ALGORITMA ALUR

```
a.) x=100000000 modal 100,000,000, 
variable x
b.) sum=0 
variable untuk menjumlah total laba
c.)y=0 
variable untuk masa bulan
d.)lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2] 
variable untuk jumlah laba perbulan,dipisahkan dengan koma, tipe data integer
e.)for i in lb : looping for indexs i, 
dengan mengambil data dari lb
f.)sum=sum+i 
rumus untuk menghitung total laba perbulan
g.)y+=1 
masa bulan, tiap looping menambah 1
h.)print("laba bulan ke-", y ,"sebesar :", i ) 
print : y = ambil masa bulan, i = ambil dari data yg ada di dalam lb
i.)print("Total laba adalah :", sum) 
print total laba Tampilkan hasil kelayar 
```

CODINGAN PROGRAM 1 py

```
x=100000000
sum=0
y=0
lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2]
print('Modal awal seorang pengusaha        :',x)
for i in lb :
    sum=sum+i
    y+=1
    print('Laba bulan ke-', y ,'sebesar            :', i)
print('Total laba yang didapat adalah      :', sum)
```

![img](https://github.com/Ekanurarifin/labpy3/blob/master/program1.PNG)
