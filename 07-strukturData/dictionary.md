# 📌 DICTIONARY (Key & Value di Python)

## 🎯 Tujuan Pembelajaran
Setelah belajar materi ini, kamu akan bisa:
- Memahami apa itu dictionary
- Membuat dictionary
- Mengakses data berdasarkan key
- Menambah, mengubah, dan menghapus data
- Menggunakan perulangan pada dictionary

---

## 🧠 Apa itu Dictionary?

Dictionary adalah **kumpulan data berpasangan (key : value)**

Contoh:
- nama : Andi
- umur : 15
- kelas : 7A

👉 Jadi tidak pakai index angka, tapi pakai **key**

---

## ✍️ Cara Membuat Dictionary

Dictionary ditulis dengan:
- tanda kurung kurawal `{ }`
- format: key : value

Contoh:
```py
siswa = {
    "nama": "Andi",
    "umur": 15,
    "kelas": "7A"
}
```

---

## 🔍 Mengakses Data

Gunakan key:
```
print(siswa["nama"]) → Andi  
print(siswa["umur"]) → 15  
```
---

## ➕ Menambah Data
```
siswa["alamat"] = "Sidoarjo"
```
---

## ✏️ Mengubah Data
```
siswa["umur"] = 16
```
---

## ❌ Menghapus Data

### 1. del
```
del siswa["kelas"]
```
---

### 2. pop()
```
siswa.pop("umur")
```
---

### 3. clear()
```
siswa.clear()
```
---

## 🔁 Perulangan pada Dictionary

### 1. Menampilkan key saja
```py
for k in siswa:
    print(k)
```
---

### 2. Menampilkan value
```py
for k in siswa:
    print(siswa[k])
```
---

### 3. Menampilkan key dan value
```py
for k, v in siswa.items():
    print(k, ":", v)
```

---

## 📏 Panjang Dictionary
```
print(len(siswa))
```
---

## 🔍 Mengecek Key
```
print("nama" in siswa) → True  
print("alamat" in siswa) → False  
```
---

## ⚠️ Key Harus Unik

Jika key sama, akan ditimpa:
```py
data = {
    "nama": "Andi",
    "nama": "Budi"
}
```
Hasil:
`{"nama": "Budi"}`

---

## 📌 Contoh Kasus 1 (Data Siswa)
```py
siswa = {
    "nama": "Andi",
    "nilai": 80
}

print("Nama:", siswa["nama"])
print("Nilai:", siswa["nilai"])
```

---

## 📌 Contoh Kasus 2 (Daftar Barang)
```py
barang = {
    "pensil": 2000,
    "buku": 5000
}

for nama, harga in barang.items():
    print(nama, "=", harga)
```

---

## 📌 Contoh Kasus 3 (Cek Kelulusan)
```py
siswa = {
    "Andi": 80,
    "Budi": 60,
    "Citra": 90
}

for nama, nilai in siswa.items():
    if nilai >= 75:
        print(nama, "Lulus")
    else:
        print(nama, "Tidak Lulus")
```

---

## ⚠️ Kesalahan yang Sering Terjadi

### 1. Salah akses key

`print(siswa["nama"])` ✔  
`print(siswa[nama])` ❌ ERROR  

---

### 2. Key tidak ada

`print(siswa["hobi"])` ❌ ERROR  

---

## 🧠 Kesimpulan

Dictionary adalah:
- ✔ data berpasangan (key : value)
- ✔ tidak pakai index angka
- ✔ key harus unik
- ✔ fleksibel dan powerful

---

🔥 Kalau kamu paham dictionary, kamu sudah siap membuat sistem data sederhana!