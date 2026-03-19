# ⚙️ Operator di Python

Operator digunakan untuk **melakukan operasi pada data**.

---

# 🎯 Tujuan

- Memahami berbagai jenis operator
- Menggunakan operator dalam kondisi (`if`)
- Menggabungkan logika program

---

# 🧠 Jenis Operator

## 1️⃣ Operator Aritmatika

Digunakan untuk perhitungan matematika

```python
+  penjumlahan
-  pengurangan
*  perkalian
/  pembagian
%  sisa bagi (modulus)
```

### 💡 Contoh:

```python
a = 10
b = 3

print(a + b)  # 13
print(a % b)  # 1
```

---

## 2️⃣ Operator Perbandingan

Digunakan untuk membandingkan nilai (hasilnya True / False)

```python
>   lebih besar
<   lebih kecil
>=  lebih besar sama dengan
<=  lebih kecil sama dengan
==  sama dengan
!=  tidak sama dengan
```

### 💡 Contoh:

```python
umur = 18

print(umur >= 17)  # True
```

---

## 3️⃣ Operator Logika

Digunakan untuk menggabungkan kondisi

```python
and  → kedua kondisi harus benar
or   → salah satu benar
not  → kebalikan kondisi
```

---

### 💡 Contoh Operator `and`

```python
umur = 18
punya_ktp = True

if umur >= 17 and punya_ktp:
    print("Boleh membuat SIM")
```

👉 Penjelasan:  
Kedua kondisi harus **benar**  
- umur >= 17 ✅  
- punya_ktp = True ✅  
👉 Maka output akan tampil

---

### 💡 Contoh Operator `or`

```python
nilai = 80

if nilai >= 75 or nilai == 100:
    print("Lulus")
```

👉 Penjelasan:  
Cukup **salah satu kondisi benar**  
- nilai >= 75 ✅  
👉 Maka tetap lulus

---

### 💡 Contoh Operator `not`

```python
login = False

if not login:
    print("Silakan login terlebih dahulu")
```

👉 Penjelasan:  
`not` membalik kondisi  
- login = False  
- not False = True  
👉 Maka kondisi dijalankan

---

## 🔥 Contoh Gabungan

```python
umur = 18
punya_ktp = False

if umur >= 17 and not punya_ktp:
    print("Harus membuat KTP terlebih dahulu")
```

👉 Penjelasan:
- umur >= 17 ✅  
- punya_ktp = False → not False = True ✅  
👉 Maka kondisi terpenuhi

---

---

# ⚠️ Error yang Sering Terjadi

## ❌ Salah operator

```python
if umur = 17
```

👉 Harus:
```python
if umur == 17
```

---

## ❌ Salah logika

```python
if nilai >= 80 or nilai <= 100
```

👉 Ini hampir selalu True ❌

---

# 💡 Tips

- Gunakan `and` untuk syarat ganda
- Gunakan `or` untuk pilihan
- Gunakan `not` untuk membalik kondisi

---

# 🚀 Kesimpulan

- Operator membantu membuat logika lebih kompleks
- Sangat penting untuk percabangan
- Digunakan di hampir semua program

---

# 🚀 Selanjutnya

👉 [06 - Perulangan](../06-perulangan/)