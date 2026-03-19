# 🔁 RETURN (Mengembalikan Nilai dari Function)

## 🎯 Tujuan Pembelajaran
Setelah belajar materi ini, kamu akan bisa:
- Memahami apa itu return
- Mengembalikan nilai dari function
- Menyimpan hasil function ke variabel
- Menggunakan hasil function untuk perhitungan

---

## 🧠 Apa itu Return?

Return adalah:
👉 **perintah untuk mengembalikan hasil dari function**

Artinya:
- function tidak hanya menampilkan (print)
- tapi juga bisa memberikan hasil untuk digunakan lagi

---

## 📌 Tanpa Return

```python
def tambah(a, b):
    print(a + b)

hasil = tambah(5, 3)
print(hasil)
```

👉 Output:
8  
None ❌

Kenapa?
👉 karena tidak pakai return

---

## ✅ Dengan Return

```python
def tambah(a, b):
    return a + b

hasil = tambah(5, 3)
print(hasil)
```

👉 Output:
8 ✔

---

## ✍️ Cara Menggunakan Return

Struktur:

```python
def nama_function():
    return hasil
```

---

## 📌 Contoh Sederhana

```python
def luas_persegi(sisi):
    return sisi * sisi

hasil = luas_persegi(4)
print("Luas:", hasil)
```

---

## 📌 Return Bisa Disimpan

```python
def kali(a, b):
    return a * b

x = kali(2, 3)
y = kali(4, 5)

print(x)
print(y)
```

---

## 📌 Return Bisa Digunakan Lagi

```python
def tambah(a, b):
    return a + b

hasil = tambah(5, 3) * 2

print(hasil)
```

---

## 📌 Return dengan Percabangan

```python
def cek_lulus(nilai):
    if nilai >= 75:
        return "Lulus"
    else:
        return "Tidak Lulus"

print(cek_lulus(80))
print(cek_lulus(60))
```

---

## ⚠️ Return Menghentikan Function

```python
def contoh():
    print("A")
    return
    print("B")  # tidak akan dijalankan
```

---

## ⚠️ Kesalahan yang Sering Terjadi

### 1. Lupa return

```python
def tambah(a, b):
    a + b  # tidak ada return ❌
```

---

### 2. Mengira print = return

```python
def tambah(a, b):
    print(a + b)

hasil = tambah(5, 3)
print(hasil)  # None ❌
```

---

## 🧠 Perbedaan Print vs Return

| Print | Return |
|------|--------|
| Menampilkan | Mengembalikan |
| Tidak bisa dipakai lagi | Bisa digunakan lagi |
| Hanya output | Bisa disimpan ke variabel |

---

## 📌 Contoh Kasus 1 (Hitung Nilai)

```python
def total_nilai(a, b, c):
    return a + b + c

hasil = total_nilai(80, 75, 90)
print("Total:", hasil)
```

---

## 📌 Contoh Kasus 2 (Rata-rata)

```python
def rata_rata(a, b):
    return (a + b) / 2

print(rata_rata(80, 90))
```

---

## 📌 Contoh Kasus 3 (Diskon)

```python
def hitung_diskon(total):
    if total > 100000:
        return total * 0.8
    else:
        return total

print(hitung_diskon(120000))
```

---

## 🧠 Kesimpulan

Return adalah:
- ✔ mengembalikan nilai dari function
- ✔ bisa disimpan ke variabel
- ✔ bisa digunakan untuk perhitungan
- ✔ lebih powerful dari print


---

🔥 Kalau kamu paham return, kamu sudah naik ke level programmer serius!

---

# 🚀 TUGAS

👉 [LATIHAN08](./latihan08.md/)

# 🚀 Materi Selanjutnya

👉 [Tugas Akhir](../09-miniProject/)