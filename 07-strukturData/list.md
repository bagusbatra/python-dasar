# 📌 LIST (Struktur Data Paling Dasar di Python)

## 🎯 Tujuan Pembelajaran
Setelah belajar materi ini, kamu akan bisa:
- Memahami apa itu list
- Membuat list
- Mengakses isi list
- Menambah dan menghapus data
- Menggunakan list dengan perulangan

---

## 🧠 Apa itu List?

List adalah **kumpulan data dalam satu variabel**.

Bayangkan seperti:
👉 daftar nama teman  
👉 daftar nilai  
👉 daftar barang  

Daripada buat banyak variabel:
nama1 = "Andi"  
nama2 = "Budi"  
nama3 = "Citra"  

Kita cukup pakai **1 list saja**:
nama = ["Andi", "Budi", "Citra"]

---

## ✍️ Cara Membuat List

List ditulis dengan:
- tanda kurung siku `[ ]`
- dipisahkan dengan koma

Contoh:
```buah = ["apel", "jeruk", "mangga"]```
```angka = [1, 2, 3, 4, 5]  ```
```campur = ["Andi", 15, True]```

---

## 🔢 Index pada List

Setiap data dalam list punya nomor (index)

⚠️ Index dimulai dari **0**, bukan 1

Contoh:
```py
nama = ["Andi", "Budi", "Citra"]

print(nama[0]) → Andi  
print(nama[1]) → Budi  
print(nama[2]) → Citra  
```

---

## ❗ Mengakses Index Terakhir

Gunakan index negatif:
```py
print(nama[-1]) → Citra  
print(nama[-2]) → Budi  
```
---

## ➕ Menambah Data ke List

### 1. append() → menambah di akhir
```
nama = ["Andi", "Budi"]  
nama.append("Citra")
```

Hasil:
```['Andi', 'Budi', 'Citra']```

---

### 2. insert() → menambah di posisi tertentu
```
nama.insert(1, "Dina")
```
---

## ❌ Menghapus Data

### 1. remove() → hapus berdasarkan nilai
```py
nama = ["Andi", "Budi", "Citra"]  
nama.remove("Budi")
```
---

### 2. pop() → hapus berdasarkan index
```
nama.pop(1)
```
---

### 3. clear() → hapus semua isi list
```
nama.clear()
```
---

## ✏️ Mengubah Data
```py
nama = ["Andi", "Budi", "Citra"]  
nama[1] = "Dina"
```
Hasil:
```['Andi', 'Dina', 'Citra']```

---

## 📏 Panjang List

Untuk menghitung jumlah data:
```py
nama = ["Andi", "Budi", "Citra"]  
print(len(nama))
```
---

## 🔁 Perulangan pada List

### Cara 1 (langsung)
```py
nama = ["Andi", "Budi", "Citra"]

for n in nama:
    print(n)
```
---

### Cara 2 (pakai index)
```py
for i in range(len(nama)):
    print(nama[i])
```
---

## 🔍 Mengecek Isi List
```py
nama = ["Andi", "Budi", "Citra"]

print("Andi" in nama) → True  
print("Dina" in nama) → False  
```
---

## 📌 Contoh Kasus 1 (Nilai Siswa)
```py
nilai = [80, 75, 90, 60]

for n in nilai:
    if n >= 75:
        print("Lulus:", n)
    else:
        print("Tidak lulus:", n)
```
---

## 📌 Contoh Kasus 2 (Daftar Belanja)
```py
belanja = ["beras", "minyak", "gula"]

belanja.append("telur")

for item in belanja:
    print("Beli:", item)
```
---

## 📌 Contoh Kasus 3 (Total Nilai)
```py
nilai = [70, 80, 90]

total = 0

for n in nilai:
    total += n

print("Total nilai:", total)
```
---

## ⚠️ Kesalahan yang Sering Terjadi

### 1. Salah index
```
nama = ["Andi", "Budi"]

print(nama[2]) → HASILNYA ERROR
```
---

### 2. Lupa tanda []
```
nama = "Andi", "Budi" → Ini bukan list!
```
---

## 🧠 Kesimpulan

List adalah:
- ✔ kumpulan data
- ✔ bisa diubah (fleksibel)
- ✔ berurutan (punya index)
- ✔ bisa menyimpan berbagai tipe data

---

🔥 Kalau kamu sudah paham list, kamu sudah naik level dalam Python!