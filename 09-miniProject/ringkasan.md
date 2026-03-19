# 📚 Ringkasan Python Dasar

Ringkasan ini berisi poin penting dari semua materi yang sudah dipelajari.

---

## 📦 00 - Instalasi

### 🧠 Tujuan
Menyiapkan Python agar bisa digunakan

### 📌 Langkah:
- Install Python
- Install code editor (VS Code / lainnya)
- Cek dengan:
```bash
python --version
```

---

## 👋 01 - Hello World

### 🧠 Tujuan
Menampilkan output pertama

### 📌 Contoh:
```python
print("Hello World")
```

---

## 📦 02 - Variabel

### 🧠 Tujuan
Menyimpan data

### 📌 Contoh:
```python
nama = "Andi"
umur = 15
```

### 📌 Tipe Data:
- string → teks
- integer → angka
- boolean → True / False

---

## 🔁 03 - Input & Output

### 🧠 Tujuan
Menerima input dari user

### 📌 Contoh:
```python
nama = input("Masukkan nama: ")
print("Halo", nama)
```

---

## 🔀 04 - Percabangan

### 🧠 Tujuan
Mengambil keputusan

### 📌 Contoh:
```python
nilai = 80

if nilai >= 75:
    print("Lulus")
else:
    print("Tidak Lulus")
```

---

## ➕ 05 - Operator

### 🧠 Jenis Operator:
- Aritmatika → + - * /
- Perbandingan → > < ==
- Logika → and, or

### 📌 Contoh:
```python
if nilai >= 75 and nilai <= 100:
    print("Lulus")
```

---

## 🔁 06 - Perulangan

### 🧠 Tujuan
Mengulang kode

### 📌 For:
```python
for i in range(5):
    print(i)
```

### 📌 While:
```python
i = 0
while i < 5:
    print(i)
    i += 1
```

---

## 📦 07 - Struktur Data

### 📌 1. List
- menyimpan banyak data
- bisa diubah

```python
data = ["Andi", "Budi"]
```

---

### 📌 2. Tuple
- seperti list
- tidak bisa diubah

```python
data = ("Andi", "Budi")
```

---

### 📌 3. Set
- data unik (tidak ada duplikat)

```python
data = {1, 2, 3}
```

---

### 📌 4. Dictionary
- key : value

```python
data = {
    "nama": "Andi",
    "nilai": 80
}
```

---

### 📌 5. Nested
- data di dalam data

```python
data = [
    {"nama": "Andi", "nilai": 80}
]
```

---

## ⚙️ 08 - Function

### 🧠 Tujuan
Merapikan kode dan menghindari pengulangan

---

### 📌 Function Dasar

```python
def sapa():
    print("Halo")

sapa()
```

---

### 📌 Parameter (Input Function)

```python
def sapa(nama):
    print("Halo", nama)

sapa("Andi")
```

---

### 📌 Return (Hasil Function)

```python
def tambah(a, b):
    return a + b

hasil = tambah(5, 3)
print(hasil)
```

---

## 🎯 Kesimpulan Besar

Setelah belajar ini semua, kamu sudah bisa:
- membuat program sederhana
- mengolah data
- menggunakan logika
- membuat kode lebih rapi dengan function

---

## 🚀 Next Step

👉 Gunakan semua ini di:
```text
09 - Mini Project
```

---

🔥 Kamu sudah siap jadi programmer pemula!