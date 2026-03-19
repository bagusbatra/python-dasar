# 📦 Variabel di Python

Variabel adalah tempat untuk **menyimpan data**.

---

# 🎯 Tujuan

* Memahami apa itu variabel
* Menyimpan dan menampilkan data
* Mengenal tipe data dasar

---

# 🧠 Apa Itu Variabel?

Variabel = **wadah untuk menyimpan nilai**

---

## 💡 Analogi

Bayangkan variabel seperti:
📦 Kotak dengan label

```text
nama = "Bagus"
```

👉 `nama` = label
👉 `"Bagus"` = isi kotak

---

# ✍️ Contoh Variabel

```python
nama = "Bagus"
umur = 17
tinggi = 170.5
```

---

# ▶️ Menampilkan Variabel

```python
print(nama)
print(umur)
```

---

## 🎉 Output

```text
Bagus
17
```

---

# 🔤 Tipe Data Dasar

## 🟢 String (teks)

```python
nama = "Bagus"
```

---

## 🔵 Integer (angka bulat)

```python
umur = 17
```

---

## 🟣 Float (angka desimal)

```python
tinggi = 170.5
```

---

# 🔗 Menggabungkan Teks

```python
nama = "Bagus"
print("Nama saya " + nama)
```

---

## 🎉 Output

```text
Nama saya Bagus
```
---
# ➕ Aritmatika di Python

Python juga bisa digunakan untuk **perhitungan matematika**.

---

## 🔢 Operator Dasar

```python
a = 10
b = 5

print(a + b)  # penjumlahan
print(a - b)  # pengurangan
print(a * b)  # perkalian
print(a / b)  # pembagian
```

---

## 💡 Contoh Kasus

```python
jumlah = 3
harga = 10000

total = jumlah * harga
print("Total harga:", total)
```

---

# ⚠️ Error yang Sering Terjadi

## ❌ Lupa tanda kutip

```python
nama = Bagus
```

👉 Harus:

```python
nama = "Bagus"
```

---

## ❌ Tidak konsisten tipe data

```python
umur = "17"
print(umur + 1)
```

👉 Error karena string + angka

---

# 💡 Tips Penamaan Variabel

✅ Gunakan nama jelas:

```python
nama_siswa = "Bagus"
```

❌ Jangan:

```python
a = "Bagus"
```

---

# 🚀 Kesimpulan

* Variabel digunakan untuk menyimpan data
* Python tidak perlu deklarasi tipe
* Gunakan nama yang jelas

---

# 🚀 Selanjutnya

👉 [03 - Input & Output](../03-input-output/)
