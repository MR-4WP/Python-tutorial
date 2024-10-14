Belajar Python dari Nol

Python adalah salah satu bahasa pemrograman yang paling populer dan mudah dipelajari. Bahasa ini sering digunakan untuk pengembangan web, analisis data, kecerdasan buatan (AI), dan masih banyak lagi. Dalam panduan ini, kita akan memulai perjalanan belajar Python dari nol.

Daftar Isi

1. Persiapan Lingkungan Pengembangan


2. Dasar-Dasar Python

Hello World

Komentar

Variabel dan Tipe Data



3. Struktur Kontrol

If-Else

Looping: For dan While



4. Fungsi


5. Struktur Data: List, Tuple, dan Dictionary


6. Penanganan File


7. Penanganan Error


8. Referensi Lanjutan



Persiapan Lingkungan Pengembangan

Sebelum mulai menulis kode Python, pastikan kamu sudah menginstal Python di komputer. Ikuti langkah-langkah berikut untuk menginstal:

1. Download Python dari python.org.


2. Ikuti petunjuk instalasi sesuai sistem operasi yang digunakan.


3. Setelah terinstal, buka terminal (atau command prompt) dan ketik python --version untuk memastikan instalasi berhasil.



Editor Kode

Untuk menulis kode Python, kamu bisa menggunakan editor teks apa saja, tetapi yang paling umum digunakan adalah:

Visual Studio Code

PyCharm

Jupyter Notebook


Dasar-Dasar Python

Hello World

Langkah pertama dalam belajar bahasa pemrograman adalah menampilkan kalimat "Hello World". Berikut adalah contoh kode Python:

print("Hello, World!")

Komentar

Komentar digunakan untuk memberi penjelasan pada kode. Python menggunakan tanda pagar # untuk menulis komentar.

# Ini adalah komentar
print("Ini bukan komentar")

Variabel dan Tipe Data

Variabel digunakan untuk menyimpan data. Python mendukung berbagai tipe data seperti integer (bilangan bulat), float (bilangan desimal), string (teks), dan boolean (True/False).

# Contoh variabel
nama = "Andi"         # Tipe data string
umur = 25             # Tipe data integer
tinggi = 175.5        # Tipe data float
is_student = True     # Tipe data boolean

Struktur Kontrol

If-Else

Struktur kontrol if-else digunakan untuk membuat keputusan berdasarkan kondisi tertentu.

umur = 18

if umur >= 18:
    print("Kamu sudah dewasa")
else:
    print("Kamu belum dewasa")

Looping: For dan While

For dan while adalah dua jenis perulangan yang digunakan di Python.

For Loop


for i in range(5):
    print(i)

While Loop


count = 0
while count < 5:
    print(count)
    count += 1

Fungsi

Fungsi adalah blok kode yang dirancang untuk melakukan tugas tertentu. Fungsi memudahkan kita untuk mengorganisir kode agar lebih modular dan mudah digunakan kembali.

def sapa(nama):
    print(f"Halo, {nama}!")

sapa("Andi")

Struktur Data: List, Tuple, dan Dictionary

Python memiliki beberapa struktur data yang sering digunakan:

List: Digunakan untuk menyimpan beberapa nilai dalam satu variabel.


buah = ["apel", "mangga", "jeruk"]
print(buah[0])  # Output: apel

Tuple: Mirip dengan list, namun bersifat immutable (tidak bisa diubah).


angka = (1, 2, 3)
print(angka[1])  # Output: 2

Dictionary: Struktur data yang menyimpan pasangan key-value.


siswa = {"nama": "Andi", "umur": 20}
print(siswa["nama"])  # Output: Andi

Penanganan File

Python memudahkan kita untuk membuka, membaca, dan menulis file. Berikut adalah contoh sederhana membuka file dan menulis ke dalamnya:

# Membuka file dan menulis ke dalamnya
with open("contoh.txt", "w") as file:
    file.write("Ini adalah contoh teks.")

Penanganan Error

Penanganan error atau exception handling berguna untuk mengatasi kesalahan yang mungkin terjadi saat program berjalan. Gunakan try-except untuk menangani error.

try:
    angka = int(input("Masukkan angka: "))
    print(angka)
except ValueError:
    print("Input bukan angka!")

Referensi Lanjutan

Untuk belajar Python lebih dalam, berikut beberapa sumber belajar yang dapat kamu gunakan:

Dokumentasi Python

Real Python

W3Schools Python Tutorial
