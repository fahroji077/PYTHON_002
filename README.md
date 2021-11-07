# PYTHON_002

1. STRING
```y
#string dengan tanda petik
nama = "muhammad 'fahroji'"
print(nama[4])

#string dengan tanda -
nama = "muhammad 'fahroji'"
print(nama[-4])

#string pengambilan huruf 0-8
nama = "muhammad 'fahroji'"
print(nama[0:8])

#string pengambilan huruf dari 8-ujung kalimat
nama = "muhammad 'fahroji'"
print(nama[8:])
```
![image](https://user-images.githubusercontent.com/93015185/140632564-8e0d2d75-ab69-4a18-867b-788d6d9d7dac.png)

2.  Formatted String

```y
#formatted string
first_nama = "muhammad"
last_nama = "fahroji"


message = f"nama kamu adalah = {first_nama} {last_nama}"

print(message)
```
![image](https://user-images.githubusercontent.com/93015185/140632575-e62b4216-80cd-4b9d-be39-2b9529d4ce0a.png)

3.  String Method

```y
#string method
cours = "belajar paython bersama muhammad fahroji"
#len itu fangsen
karakter = len(cours)

print (karakter)

#string method
karakter = "belajar paython bersama muhammad fahroji"

#method untuk kapital semua (.upper()), untuk huruf kecil semua (.lower())
#awalan kapital (capitalizatoon()), untuk setiap kata (.title()), mengubah kata (.replace("",""))

#huruf kapita
print(karakter.upper())

#huruf kapital setiap kata
print(karakter.title())

#mengubah kata dengan replace
print(karakter.replace("paython", "masak"))

#pengecekan data/kalimat True atau flase
kata = " belajar masak bareng muhammad fahroji"
language = "bareng"

print(language in kata)
```
![image](https://user-images.githubusercontent.com/93015185/140632619-7b1fb66a-4c29-4e05-8fbf-4ed1a0212269.png)

4. Matematika

```y
#matematika
x = 5
y = 3

print(x + y)

# ** artinya perpangkatan

print(x ** y)

#jika tanda bagi / maka hasinya akan fload,jika tanda bagi // maka hasilnya angka bulat
print(x / y)
print(x // y)

#operator modulo
print(x % y)

#cara penambahan nilai variabel
x = 5
x = x + 10
print(x)

#atau
x = 5
x += 10
print(x)
```
![image](https://user-images.githubusercontent.com/93015185/140632641-0d64b1a1-6e64-4923-83a8-50a6a792e781.png)

5. Operator Precedence

```y
#Operator Precedence

nomor = (4 + 10) * 5 ** 2
print(nomor)

#tanda kurung akan didahulukan daripada
# perpangkatan akan didahulukan daripada
# perkalian atau pembagian akan didahulukan 
# penjumlahan atau pengurangan
```
![image](https://user-images.githubusercontent.com/93015185/140632660-de585434-0163-48e6-b623-3bfb3d60bd9c.png)

6. Math Module

```y
#Math Module

#jika 5.5 akan dibulatkan ke atas dan begitu sebaliknya

number = 5.4
number = round(number)
print(number)

#solusi untuk tetap memangsakan pembulatan ke atas dengan ceil menggunakan konsep inport math
import math
number = 5.2
number = math.ceil(number)
print(number)

#untuk pembulatan kebawah dengan floor menggunakan konsep inport math
import math
number = 5.8
number = math.floor(number)
print(number)
```
![image](https://user-images.githubusercontent.com/93015185/140632720-4bf200c6-d4e0-416d-9ffe-74151671ef2c.png)
