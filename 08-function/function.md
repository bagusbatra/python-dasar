# ⚙️ FUNCTION (Fungsi di Python)

## 🎯 Tujuan Pembelajaran
Setelah belajar materi ini, kamu akan bisa:
- Memahami apa itu function
- Membuat function sendiri
- Menggunakan function dalam program
- Membuat kode lebih rapi dan mudah dibaca

---

## 🧠 Apa itu Function?

Function adalah:
👉 **sekumpulan kode yang bisa dipanggil kembali**

Artinya:
- kita tidak perlu menulis kode yang sama berulang-ulang
- cukup buat sekali, pakai berkali-kali

---

## 📌 Contoh Tanpa Function

```python
print("Halo Andi")
print("Halo Budi")
print("Halo Citra")
```

👉 Kalau banyak nama, kita harus nulis terus 😓

---

## ✅ Contoh Dengan Function

```python
def sapa():
    print("Halo teman!")

sapa()
sapa()
```

👉 Tinggal panggil function saja 🎉

---

## ✍️ Cara Membuat Function

Struktur dasar:

```python
def nama_function():
    # isi function
```

Contoh:

```python
def halo():
    print("Halo Dunia")

halo()
```

---

## 🔁 Function Bisa Dipanggil Berkali-kali

```python
def salam():
    print("Selamat belajar!")

salam()
salam()
salam()
```

---

## 📌 Function dengan Banyak Perintah

```python
def info():
    print("Nama: Andi")
    print("Kelas: 7A")
    print("Umur: 15")

info()
```

---

## ⚠️ Penting!

### 1. Harus dipanggil

```python
def halo():
    print("Halo")

# tidak dipanggil → tidak muncul output
```

---

### 2. Perhatikan indentasi

```python
def halo():
print("Halo") ❌ ERROR
```

✔ yang benar:
```python
def halo():
    print("Halo")
```

---

## 📌 Contoh Kasus 1 (Sapaan)

```python
def sapa():
    print("Halo siswa!")

sapa()
```

---

## 📌 Contoh Kasus 2 (Menu Program)

```python
def menu():
    print("1. Lihat Data")
    print("2. Tambah Data")
    print("3. Keluar")

menu()
```

---

## 📌 Contoh Kasus 3 (Data Sederhana)

```python
def tampil_data():
    print("Nama: Andi")
    print("Nilai: 80")

tampil_data()
```

---

## 🧠 Kapan Harus Pakai Function?

Gunakan function jika:
- kode sering diulang
- program mulai panjang
- ingin membuat kode lebih rapi

---

## 🧠 Kesimpulan

Function adalah:
- ✔ kumpulan kode
- ✔ bisa dipanggil ulang
- ✔ membuat program lebih rapi
- ✔ dasar penting untuk program besar

---

🔥 Kalau kamu paham function, kamu sudah mulai jadi programmer beneran!