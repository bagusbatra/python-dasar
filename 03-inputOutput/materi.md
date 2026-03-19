# ⌨️ Input & Output di Python

Pada materi ini, kamu akan belajar membuat program yang bisa **menerima input dari user** dan menampilkan output.

---

# 🎯 Tujuan

- Memahami fungsi `input()`
- Mengambil data dari user
- Menggabungkan input dan output

---

# 🧠 Apa itu `input()`?

`input()` adalah fungsi untuk **mengambil data dari pengguna (user)**

---

## 💡 Contoh Sederhana

```python
nama = input("Masukkan nama: ")
print("Halo", nama)
```

---

## ▶️ Cara Kerja

1. Program meminta input
2. User mengetik sesuatu
3. Program menyimpan ke variabel
4. Ditampilkan kembali dengan `print()`

---

## 🎉 Contoh Output

```text
Masukkan nama: Bagus
Halo Bagus
```

---

# ⚠️ Penting: Semua Input = String

```python
umur = input("Masukkan umur: ")
print(umur)
```

👉 Walaupun user input angka, tetap dianggap **string**

---

# 🔢 Konversi Tipe Data

Gunakan:

```python
int()   # ke angka bulat
float() # ke desimal
```

---

## 💡 Contoh

```python
umur = int(input("Masukkan umur: "))
print(umur + 1)
```

---

## 🎉 Output

```text
Masukkan umur: 17
18
```

---

# ➕ Contoh Aritmatika

```python
angka1 = int(input("Masukkan angka pertama: "))
angka2 = int(input("Masukkan angka kedua: "))

hasil = angka1 + angka2
print("Hasil:", hasil)
```

---

# ⚠️ Error yang Sering Terjadi

## ❌ Tidak pakai int()

```python
angka = input("Masukkan angka: ")
print(angka + 1)
```

👉 Error karena string + angka

---

## ❌ Salah urutan

```python
print("Halo " + nama)
nama = input("Nama: ")
```

👉 Variabel harus dibuat dulu

---

# 💡 Tips

- Gunakan kalimat yang jelas di `input()`
- Gunakan nama variabel yang mudah dipahami

---

# 🚀 Kesimpulan

- `input()` digunakan untuk mengambil data dari user
- Semua input adalah string
- Gunakan `int()` jika ingin angka

---

# 🚀 TUGAS

👉 [LATIHAN03](./latihan03.md/)

---

# 🚀 Selanjutnya

👉 [04 - Percabangan](../04-percabangan/)