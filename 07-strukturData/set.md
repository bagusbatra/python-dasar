# 📌 SET (Kumpulan Data Unik di Python)

## 🎯 Tujuan Pembelajaran
Setelah belajar materi ini, kamu akan bisa:
- Memahami apa itu set
- Membuat set
- Menambah dan menghapus data
- Menggunakan set untuk menghilangkan duplikat
- Menggunakan operasi dasar pada set

---

## 🧠 Apa itu Set?

Set adalah **kumpulan data unik (tidak boleh duplikat)**.

Ciri-ciri set:
- ❌ Tidak berurutan
- ❌ Tidak punya index
- ✔ Tidak boleh ada data yang sama
- ✔ Bisa ditambah dan dihapus

---

## ✍️ Cara Membuat Set

Set ditulis dengan:
- tanda kurung kurawal `{ }`

Contoh:
```py
angka = {1, 2, 3, 4}  
buah = {"apel", "jeruk", "mangga"}  
```
---

## ⚠️ Duplikat Akan Hilang

Jika ada data yang sama, otomatis dihapus:
```py
angka = {1, 2, 2, 3, 3, 4}
```
Hasil:
```
{1, 2, 3, 4}
```
👉 Set sangat berguna untuk **menghilangkan data ganda**

---

## ➕ Menambah Data

Gunakan `.add()`
```py
angka = {1, 2, 3}  
angka.add(4)
```
Hasil:
```
{1, 2, 3, 4}
```

---

## ❌ Menghapus Data

### 1. remove() → hapus data tertentu
```py
angka = {1, 2, 3}  
angka.remove(2)
```

---

### 2. discard() → lebih aman (tidak error jika tidak ada)
```py
angka.discard(5)
```

---

### 3. pop() → hapus data acak
```
angka.pop()
```
---

### 4. clear() → hapus semua
```
angka.clear()
```
---

## ❗ Tidak Bisa Pakai Index

Set tidak berurutan, jadi ini ERROR:
```
angka = {1, 2, 3}  
print(angka[0]) ❌
```
---

## 🔁 Perulangan pada Set

Walaupun tidak berurutan, tetap bisa di-loop:
```py
angka = {1, 2, 3}

for a in angka:
    print(a)
```

---

## 🔍 Mengecek Data
```py
angka = {1, 2, 3}

print(2 in angka) → True  
print(5 in angka) → False  
```
---

## 🔗 Operasi pada Set

### 1. Union (Gabungan)

Menggabungkan dua set:
```py
a = {1, 2, 3}  
b = {3, 4, 5}

hasil = a.union(b)
```
Hasil:
```
{1, 2, 3, 4, 5}
```
---

### 2. Intersection (Irisan)

Data yang sama:
```
hasil = a.intersection(b)
```
Hasil:
```
{3}
```

---

### 3. Difference (Selisih)

Data yang berbeda:
```
hasil = a.difference(b)
```
Hasil:
```
{1, 2}
```
---

## 📌 Contoh Kasus 1 (Hapus Duplikat)
```
data = [1, 2, 2, 3, 3, 4]

unik = set(data)

print(unik)
```
👉 Hasil:
```
{1, 2, 3, 4}
```

---

## 📌 Contoh Kasus 2 (Hobi Unik)
```
hobi = ["makan", "tidur", "makan", "main"]

hobi_unik = set(hobi)

for h in hobi_unik:
    print(h)
```
---

## 📌 Contoh Kasus 3 (Data Sama)
```
kelasA = {"Andi", "Budi", "Citra"}  
kelasB = {"Budi", "Dina", "Citra"}

sama = kelasA.intersection(kelasB)

print("Siswa yang sama:", sama)
```
---

## ⚠️ Kesalahan yang Sering Terjadi

### 1. Mengira set berurutan

Set tidak punya urutan tetap!

---

### 2. Pakai index

`angka[0]` ❌ ERROR

---

### 3. Salah membuat set kosong

`s = {}` → ini dictionary, bukan set

Cara benar:
`s = set()`

---

## 🧠 Kesimpulan

Set adalah:
- ✔ kumpulan data unik
- ✔ tidak berurutan
- ✔ tidak punya index
- ✔ cocok untuk menghapus duplikat
- ✔ bisa operasi matematika (union, intersection, dll)

---

🔥 Kalau kamu paham set, kamu sudah bisa mengolah data dengan lebih rapi!