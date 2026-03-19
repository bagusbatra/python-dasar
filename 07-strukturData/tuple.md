# 📌 TUPLE (Data Tetap di Python)

## 🎯 Tujuan Pembelajaran
Setelah belajar materi ini, kamu akan bisa:
- Memahami apa itu tuple
- Membuat tuple
- Mengakses data dalam tuple
- Menggunakan tuple dalam perulangan
- Mengetahui perbedaan tuple dan list

---

## 🧠 Apa itu Tuple?

Tuple adalah **kumpulan data seperti list**, tetapi:

👉 ❌ **TIDAK bisa diubah (immutable)**

Artinya:
- Tidak bisa tambah data
- Tidak bisa hapus data
- Tidak bisa ubah isi

---

## ✍️ Cara Membuat Tuple

Tuple ditulis dengan:
- tanda kurung biasa `( )`

Contoh:
```py
hari = ("Senin", "Selasa", "Rabu")  
angka = (1, 2, 3, 4)  
```
---

## ⚠️ Perbedaan dengan List

| Fitur        | List | Tuple |
|-------------|------|------|
| Bisa diubah | ✔    | ❌   |
| Tanda       | [ ]  | ( )  |
| Fleksibel   | ✔    | ❌   |

---

## 🔢 Index pada Tuple

Sama seperti list, tuple punya index:
```
hari = ("Senin", "Selasa", "Rabu")

print(hari[0]) → Senin  
print(hari[1]) → Selasa  
```
---

## ❗ Index Negatif
```
print(hari[-1]) → Rabu  
```

---

## ❌ Tidak Bisa Diubah
```
hari = ("Senin", "Selasa", "Rabu")

hari[0] = "Minggu" ❌ ERROR
```

---

## 🔁 Perulangan pada Tuple
```
hari = ("Senin", "Selasa", "Rabu")

for h in hari:
    print(h)
```

---

## 📏 Panjang Tuple
```
print(len(hari))
```

---

## 🔍 Mengecek Isi Tuple
```
print("Senin" in hari) → True  
print("Jumat" in hari) → False  
```

---

## ⚠️ Tuple 1 Data

Jika hanya 1 data, harus pakai koma:

`a = (5,)` ✔  
`a = (5)` ❌ (ini bukan tuple)

---

## 🔄 Konversi Tuple ↔ List

### Tuple ke List
```
hari = ("Senin", "Selasa")  
hari_list = list(hari)
```

---

### List ke Tuple
```
data = ["Andi", "Budi"]  
data_tuple = tuple(data)
```

---

## 📌 Contoh Kasus 1 (Data Tetap)
```py
bulan = ("Jan", "Feb", "Mar")

for b in bulan:
    print(b)
```

---

## 📌 Contoh Kasus 2 (Koordinat)
```py
titik = (10, 20)

print("X:", titik[0])  
print("Y:", titik[1])  
```

---

## 📌 Contoh Kasus 3 (Data Aman)
```py
username = ("admin", "user1", "user2")

print(username)
```

👉 Data tidak bisa diubah sembarangan

---

## ⚠️ Kesalahan yang Sering Terjadi

### 1. Mengira bisa diubah

tuple tidak bisa diubah ❌

---

### 2. Lupa koma pada 1 data

`a = (5)` ❌  
`a = (5,)` ✔  

---

## 🧠 Kesimpulan

Tuple adalah:
- ✔ kumpulan data
- ✔ berurutan (punya index)
- ❌ tidak bisa diubah
- ✔ cocok untuk data tetap / aman

---

🔥 Kalau kamu paham tuple, kamu sudah tahu cara menjaga data tetap aman!