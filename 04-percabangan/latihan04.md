# 📝 Latihan Percabangan

Kerjakan latihan berikut:

---

## 🟢 Soal 1 (Mudah)

Buat program:
- input umur

Jika umur >= 17:
👉 tampilkan "Dewasa"  
Jika tidak:
👉 tampilkan "Belum Dewasa"

---

## 🟡 Soal 2 (Sedang)

Buat program:
- input nilai

Jika:
- ```>= 90 → A```
- ```>= 80 → B```
- ```>= 75 → C```
- ```< 75 → D```

---

## 🔴 Soal 3 (Berpikir)

Buat program:
- input username
- input password

Jika:
- username = "admin"
- password = "123"

👉 tampilkan "Login Berhasil"  
Jika tidak:
👉 tampilkan "Login Gagal"

---

# 🚀 Challenge (Level Hard 🔥)

Buat program **Penilaian Siswa Lengkap**

---

## 🎯 Ketentuan:

1. Input:
   - nama siswa
   - nilai (angka)

2. Tentukan:
   - ```>= 90 → A```
   - ```>= 80 → B```
   - ```>= 70 → C```
   - ```< 70 → D```

3. Tampilkan:
    - jika nilai > 80 maka lulus
    - jika nilai < 80 maka gagal

```text
===== HASIL =====
Nama  : Bagus
Nilai : 85
Grade : B
Status: Lulus
================
```

---

# 🚀 Challenge (Level Hard 🔥 - Nested If)

Buat program **Simulasi Ujian Pembuatan SIM**

---

## 🎯 Studi Kasus

Dalam pembuatan SIM, terdapat 2 ujian:

- Ujian Teori
- Ujian Praktik

---

## 📥 Input:

- nama peserta
- nilai teori
- nilai praktik

---

## 🧠 Aturan Penilaian:

Gunakan **nested if (if di dalam if)**

1. Jika:
   - nilai teori > 90
   - DAN nilai praktik > 90  
   👉 **Status: LULUS**

2. Jika:
   - salah satu > 90  
   👉 **Status: LULUS BERSYARAT**

3. Jika:
   - keduanya ≤ 90  
   👉 **Status: GAGAL**

---

## 💡 Contoh Output:

```text
===== HASIL UJIAN SIM =====
Nama           : Bagus
Nilai Teori    : 95
Nilai Praktik  : 92
Status         : LULUS 🎉
==========================
```

---

## 💡 Contoh Lain:

```text
===== HASIL UJIAN SIM =====
Nama           : Bagus
Nilai Teori    : 95
Nilai Praktik  : 70
Status         : LULUS BERSYARAT ⚠️
==========================
```

---

```text
===== HASIL UJIAN SIM =====
Nama           : Bagus
Nilai Teori    : 60
Nilai Praktik  : 70
Status         : GAGAL ❌
==========================
```

---

## ⚠️ Ketentuan Wajib

- Gunakan **nested if**
- Gunakan `int()` untuk input angka
- Output harus rapi

---


## 📂 Simpan File

```text
latihan04.py
```

Simpan di:

```text
pengumpulan/nama_kamu/
```

---

## 🧠 Tujuan Challenge

- Memahami konsep **if elif else**
- Memahami logika percabangan
- Mengambil keputusan dalam program
- Menggabungkan input + kondisi
- Simulasi kasus dunia nyata

---

Semangat! 💪

# 🚀 Materi Selanjutnya

👉 [05 - operator](../05-operator/)