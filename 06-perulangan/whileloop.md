# 🔁 While Loop di Python

While loop digunakan untuk **mengulang program selama kondisi bernilai True**

---

# 🎯 Tujuan

- Memahami perulangan berbasis kondisi
- Mengontrol kapan loop berhenti

---

# 🔤 Sintaks Dasar

```python
while kondisi:
    aksi
```

---

# 💡 Contoh Sederhana

```python
i = 1

while i <= 5:
    print("Perulangan ke-", i)
    i += 1
```

---

## 🎉 Output

```text
Perulangan ke- 1
Perulangan ke- 2
Perulangan ke- 3
Perulangan ke- 4
Perulangan ke- 5
```

---

# 🔍 Penjelasan

- `i = 1` → nilai awal
- `i <= 5` → kondisi
- `i += 1` → increment (penambah)

---

# ⚠️ Hati-hati Infinite Loop

Jika kondisi selalu True → loop tidak berhenti ❌

```python
i = 1

while i <= 5:
    print(i)
```

👉 Akan berjalan terus karena `i` tidak berubah

---

# ➕ Contoh dengan Input

```python
password = ""

while password != "123":
    password = input("Masukkan password: ")

print("Login berhasil")
```

---

# 💡 Contoh Studi Kasus

Program menghitung total angka:

```python
total = 0
angka = 1

while angka <= 5:
    total += angka
    angka += 1

print("Total:", total)
```

---

# 🚀 Kesimpulan

- `while` digunakan jika jumlah perulangan belum pasti
- Harus ada kondisi berhenti
- Gunakan increment/decrement

---

# 🚀 Selanjutnya

👉 [For Loop](./forloop.md)