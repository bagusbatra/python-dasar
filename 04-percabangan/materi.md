# 🔀 Percabangan di Python (if, else, elif)

Pada materi ini, kamu akan belajar membuat program yang bisa **mengambil keputusan**.

---

# 🎯 Tujuan

- Memahami `if`, `else`, dan `elif`
- Membuat logika percabangan
- Mengontrol alur program

---

# 🧠 Apa itu Percabangan?

Percabangan adalah cara agar program bisa:
👉 memilih aksi berdasarkan kondisi

---

## 💡 Contoh Kehidupan Nyata

```text
Jika hujan → bawa payung
Jika tidak → tidak perlu
```

---

# 🔤 Sintaks Dasar

```python
if kondisi:
    aksi
```

---

## 💡 Contoh

```python
umur = 18

if umur >= 17:
    print("Boleh membuat KTP")
```

---

# 🔀 if - else

```python
if kondisi:
    aksi jika benar
else:
    aksi jika salah
```

---

## 💡 Contoh

```python
umur = 15

if umur >= 17:
    print("Dewasa")
else:
    print("Belum dewasa")
```

---

# 🔁 if - elif - else

Digunakan jika kondisi lebih dari satu

```python
if kondisi1:
    aksi1
elif kondisi2:
    aksi2
else:
    aksi lainnya
```

---

## 💡 Contoh

```python
nilai = 85

if nilai >= 90:
    print("A")
elif nilai >= 75:
    print("B")
else:
    print("C")
```

---

# 🔍 Operator Perbandingan

```python
>   lebih besar
<   lebih kecil
>=  lebih besar sama dengan
<=  lebih kecil sama dengan
==  sama dengan
!=  tidak sama dengan
```

---

# ⚠️ Penting: Indentasi

Python menggunakan **spasi/tab** untuk menentukan blok kode

```python
if True:
    print("Benar")  # harus menjorok ke dalam
```

---

# ❌ Contoh Salah

```python
if True:
print("Salah")
```

👉 Akan error karena tidak ada indentasi

---

# ➕ Contoh Program Interaktif

```python
umur = int(input("Masukkan umur: "))

if umur >= 17:
    print("Anda boleh membuat KTP")
else:
    print("Anda belum cukup umur")
```

---

# ⚠️ Error yang Sering Terjadi

## ❌ Lupa titik dua `:`

```python
if umur >= 17
```

---

## ❌ Salah operator

```python
if umur = 17  # salah
```

👉 Harus:
```python
if umur == 17
```

---

# 💡 Tips

- Gunakan kondisi sederhana dulu
- Perhatikan indentasi
- Gunakan nama variabel yang jelas

---

# 🚀 Kesimpulan

- `if` untuk kondisi
- `else` untuk alternatif
- `elif` untuk banyak kondisi
- Python sensitif terhadap indentasi

---

# 🚀 TUGAS

👉 [LATIHAN04](./latihan04.md/)

---

# 🚀 Selanjutnya

👉 [05 - Operator](../05-operator/)