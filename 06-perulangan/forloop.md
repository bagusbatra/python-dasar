# 🔁 For Loop di Python

For loop digunakan untuk **mengulang dengan jumlah tertentu**

---

# 🎯 Tujuan

- Memahami perulangan dengan range
- Mengontrol jumlah pengulangan

---

# 🔤 Sintaks Dasar

```python
for variabel in range(n):
    aksi
```

---

# 💡 Contoh Sederhana

```python
for i in range(5):
    print("Perulangan ke-", i)
```

---

## 🎉 Output

```text
Perulangan ke- 0
Perulangan ke- 1
Perulangan ke- 2
Perulangan ke- 3
Perulangan ke- 4
```

---

# 🔍 Penjelasan

- `range(5)` → dari 0 sampai 4
- `i` → variabel loop

---

# ➕ Range dengan Start, Stop

```python
for i in range(1, 6):
    print(i)
```

---

## 🎉 Output

```text
1
2
3
4
5
```

---

# ➕ Range dengan Step

```python
for i in range(0, 10, 2):
    print(i)
```

---

## 🎉 Output

```text
0
2
4
6
8
```

---

# 💡 Contoh Studi Kasus

Menampilkan bilangan genap:

```python
for i in range(2, 11, 2):
    print(i)
```

---

# 💡 Contoh Lain

Menampilkan huruf:

```python
for huruf in "Python":
    print(huruf)
```

---

# 🚀 Kesimpulan

- `for` digunakan jika jumlah perulangan jelas
- `range()` sangat penting
- Bisa digunakan untuk angka dan teks

---

# 🚀 Selanjutnya

👉 [while Loop](./whileloop.md)