# 📥 PARAMETER (Input pada Function)

## 🎯 Tujuan Pembelajaran
Setelah belajar materi ini, kamu akan bisa:
- Memahami apa itu parameter
- Mengirim data ke dalam function
- Menggunakan parameter dalam program

---

## 🧠 Apa itu Parameter?

Parameter adalah:
👉 **data yang dikirim ke dalam function**

Dengan parameter:
- function jadi lebih fleksibel
- bisa digunakan untuk banyak data

---

## 📌 Tanpa Parameter

```python
def sapa():
    print("Halo Andi")

sapa()
```

👉 Hanya untuk 1 orang saja ❌

---

## ✅ Dengan Parameter

```python
def sapa(nama):
    print("Halo", nama)

sapa("Andi")
sapa("Budi")
sapa("Citra")
```

👉 Bisa untuk banyak orang 🎉

---

## ✍️ Cara Membuat Parameter

Struktur:

```python
def nama_function(parameter):
    # isi function
```

Contoh:

```python
def halo(nama):
    print("Halo", nama)

halo("Andi")
```

---

## 📌 Lebih dari 1 Parameter

```python
def data(nama, umur):
    print("Nama:", nama)
    print("Umur:", umur)

data("Andi", 15)
```

---

## ⚠️ Urutan Parameter Penting!

```python
def data(nama, umur):
    print(nama, umur)

data(15, "Andi") ❌ salah urutan
```

---

## 📌 Contoh Kasus 1 (Nilai Siswa)

```python
def nilai_siswa(nama, nilai):
    print(nama, "mendapat nilai", nilai)

nilai_siswa("Andi", 80)
nilai_siswa("Budi", 70)
```

---

## 📌 Contoh Kasus 2 (Luas Persegi)

```python
def luas(sisi):
    hasil = sisi * sisi
    print("Luas:", hasil)

luas(4)
luas(6)
```

---

## 📌 Contoh Kasus 3 (Penjumlahan)

```python
def tambah(a, b):
    print("Hasil:", a + b)

tambah(5, 3)
tambah(10, 2)
```

---

## ⚠️ Kesalahan yang Sering Terjadi

### 1. Tidak mengisi parameter

```python
def sapa(nama):
    print(nama)

sapa() ❌ ERROR
```

---

### 2. Jumlah parameter tidak sesuai

```python
def tambah(a, b):
    print(a + b)

tambah(5) ❌ ERROR
```

---

## 🧠 Kesimpulan

Parameter adalah:
- ✔ input untuk function
- ✔ membuat function fleksibel
- ✔ bisa lebih dari satu
- ✔ urutan harus benar


---

🔥 Dengan parameter, function kamu jadi lebih pintar!

# 🚀 Selanjutnya

👉 [RETURN](./return.md)