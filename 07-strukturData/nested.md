# 📌 NESTED DATA (Struktur Data Bersarang)

## 🎯 Tujuan Pembelajaran
Setelah belajar materi ini, kamu akan bisa:
- Memahami apa itu nested data
- Menggunakan list di dalam list
- Menggunakan dictionary di dalam dictionary
- Menggabungkan list dan dictionary
- Mengakses data yang lebih kompleks

---

## 🧠 Apa itu Nested Data?

Nested artinya **bersarang (data di dalam data)**

Contoh:
- List di dalam list
- Dictionary di dalam dictionary
- List berisi dictionary

👉 Digunakan untuk menyimpan **data yang lebih kompleks**

---

## 📦 1. List di Dalam List

### Contoh:
```
data = [
    ["Andi", 80],
    ["Budi", 70],
    ["Citra", 90]
]
```
---

## 🔍 Mengakses Data

`print(data[0])` → ["Andi", 80]  
`print(data[0][0])` → Andi  
`print(data[0][1])` → 80  

---

## 🔁 Perulangan
```
for siswa in data:
    print("Nama:", siswa[0])
    print("Nilai:", siswa[1])
```

---

## 📦 2. Dictionary di Dalam Dictionary

### Contoh:
```
siswa = {
    "s1": {
        "nama": "Andi",
        "nilai": 80
    },
    "s2": {
        "nama": "Budi",
        "nilai": 70
    }
}
```

---

## 🔍 Mengakses Data

`print(siswa["s1"]["nama"])` → Andi  
`print(siswa["s2"]["nilai"])` → 70  

---

## 🔁 Perulangan
```
for key in siswa:
    print("ID:", key)
    print("Nama:", siswa[key]["nama"])
    print("Nilai:", siswa[key]["nilai"])
```
---

## 📦 3. List Berisi Dictionary

### Contoh:
```
data = [
    {"nama": "Andi", "nilai": 80},
    {"nama": "Budi", "nilai": 70},
    {"nama": "Citra", "nilai": 90}
]
```
---

## 🔍 Mengakses Data

`print(data[0]["nama"])`→ Andi  
`print(data[1]["nilai"])` → 70  

---

## 🔁 Perulangan
```
for siswa in data:
    print(siswa["nama"], "-", siswa["nilai"])
```

---

## 📌 Contoh Kasus 1 (Data Siswa)
```py
data = [
    {"nama": "Andi", "nilai": 80},
    {"nama": "Budi", "nilai": 60},
    {"nama": "Citra", "nilai": 90}
]

for siswa in data:
    if siswa["nilai"] >= 75:
        print(siswa["nama"], "Lulus")
    else:
        print(siswa["nama"], "Tidak Lulus")
```
---

## 📌 Contoh Kasus 2 (Cari Nilai Tertinggi)
```py
data = [
    {"nama": "Andi", "nilai": 80},
    {"nama": "Budi", "nilai": 60},
    {"nama": "Citra", "nilai": 90}
]

tertinggi = 0
nama_tertinggi = ""

for siswa in data:
    if siswa["nilai"] > tertinggi:
        tertinggi = siswa["nilai"]
        nama_tertinggi = siswa["nama"]

print("Nilai tertinggi:", nama_tertinggi, "-", tertinggi)
```
---

## 📌 Contoh Kasus 3 (Data Kelas)
```py
kelas = {
    "7A": ["Andi", "Budi"],
    "7B": ["Citra", "Dina"]
}

for k in kelas:
    print("Kelas:", k)
    for nama in kelas[k]:
        print("-", nama)
```
---

## ⚠️ Kesalahan yang Sering Terjadi

### 1. Salah akses data

`print(data["nama"])` ❌  
`print(data[0]["nama"])` ✔  

---

### 2. Bingung struktur

Selalu pahami:
- ini list?
- ini dictionary?
- urutannya bagaimana?

---

## 🧠 Kesimpulan

Nested data adalah:
- ✔ data di dalam data
- ✔ digunakan untuk data kompleks
- ✔ kombinasi list & dictionary
- ✔ sering dipakai di project nyata

---

🔥 Kalau kamu paham nested data, kamu sudah siap bikin project nyata!