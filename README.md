# pratikum5
# NAMA: AGUNG HERLAMBANG
# NIM: 312410296
# KELAS: TI.24.A4
# MATKUL BAHASA PEMROGRAMAN 

# ELEMEN PY


```pyhton
list_a = [1, 2, 3, 4, 5]

print(list_a[2])

print(list_a[1:4])

print(list_a[-1])

list_a[3] = 10
print(list_a)

list_a[3:] = [11, 12, 13]
print(list_a)

list_b = list_a[:2]
print(list_b)

list_b.append("misalnya")
print(list_b)

list_b.extend([14, 15, 16])
print(list_b)

list_a.extend(list_b)
print(list_a)
````
# KODE PROGRAM DI VIUSAL CODE SEBAGAI BERIKUT:
![GAMBAR)](https://github.com/user-attachments/assets/4a4fbb8d-4d4c-4499-bbbc-e47da6576e34)

# HASIL DARI PROGRAM BERIKUT:
![gambar](https://github.com/user-attachments/assets/374b0ed5-fa72-4b73-94af-25e8c1a634ac)

# MENAMBAH DATA PY


```pyhton
class Mahasiswa:
    def _init_(self, nama, nim, nilai_tugas, nilai_uts, nilai_uas):
        self.nama = nama
        self.nim = nim
        self.nilai_tugas = nilai_tugas
        self.nilai_uts = nilai_uts
        self.nilai_uas = nilai_uas

    def hitung_nilai_akhir(self):
        return (self.nilai_tugas + self.nilai_uts + self.nilai_uas) / 3

mahasiswa = []

while True:
    nama = input("Nama: ")
    nim = int(input("NIM: "))
    nilai_tugas = int(input("Nilai Tugas: "))
    nilai_uts = int(input("Nilai UTS: "))
    nilai_uas = int(input("Nilai UAS: "))

    mahasiswa.append(Mahasiswa(nama, nim, nilai_tugas, nilai_uts, nilai_uas))

    tambah_data = input("Tambah data (y/t)? ")
    if tambah_data.lower() == "t":
        break

print("-" * 60)
print("| No | Nama       | NIM  | Tugas | UTS  | UAS  | Akhir     |")
print("-" * 60)

for i, mhs in enumerate(mahasiswa):
    nilai_akhir = mhs.hitung_nilai_akhir()
    print(f"| {i+1:<2} | {mhs.nama:<10} | {mhs.nim:<4} | {mhs.nilai_tugas:<5} | {mhs.nilai_uts:<5} | {mhs.nilai_uas:<5} | {nilai_akhir:<9.2f} |")

print("-" * 60)
````

# penjelasan DARI CODE MENAMBAH DATA:

```pyhton
class Mahasiswa:
    def __init__(self, nama, nim, nilai_tugas, nilai_uts, nilai_uas):
        self.nama = nama
        self.nim = nim
        self.nilai_tugas = nilai_tugas
        self.nilai_uts = nilai_uts
        self.nilai_uas = nilai_uas
__init__: Konstruktor ini digunakan untuk menginisialisasi objek Mahasiswa dengan atribut: nama, nim, nilai_tugas, nilai_uts, nilai_uas

def hitung_nilai_akhir(self):
    return (self.nilai_tugas + self.nilai_uts + self.nilai_uas) / 3
````

# Metode ini mengembalikan nilai akhir mahasiswa, yang merupakan rata-rata dari nilai_tugas, nilai_uts, dan nilai_uas.

```pyhton
mahasiswa = []
````

# Sebuah daftar kosong mahasiswa disiapkan untuk menyimpan objek Mahasiswa yang akan ditambahkan

``pyhyon
while True:
    nama = input("Nama: ")
    nim = int(input("NIM: "))
    nilai_tugas = int(input("Nilai Tugas: "))
    nilai_uts = int(input("Nilai UTS: "))
    nilai_uas = int(input("Nilai UAS: "))

    mahasiswa.append(Mahasiswa(nama, nim, nilai_tugas, nilai_uts, nilai_uas))

    tambah_data = input("Tambah data (y/t)? ")
    if tambah_data.lower() == "t":
        break
        ````
# Meminta pengguna untuk memasukkan data mahasiswa berulang kali hingga pengguna memasukkan t untuk berhenti, Setiap input digunakan untuk membuat data Mahasiswa, yang kemudian ditambahkan ke dalam daftar mahasiswa

```pyhton
print("-" * 60)
print("| No | Nama       | NIM  | Tugas | UTS  | UAS  | Akhir     |")
print("-" * 60)

for i, mhs in enumerate(mahasiswa):
    nilai_akhir = mhs.hitung_nilai_akhir()
    print(f"| {i+1:<2} | {mhs.nama:<10} | {mhs.nim:<4} | {mhs.nilai_tugas:<5} | {mhs.nilai_uts:<5} | {mhs.nilai_uas:<5} | {nilai_akhir:<9.2f} |")

print("-" * 60)
````

## Header tabel dicetak terlebih dahulu, diikuti oleh baris-baris data untuk setiap mahasiswa, Untuk setiap mahasiswa, metode hitung_nilai_akhir dipanggil untuk menghitung nilai akhir, lalu data ditampilkan dalam format tabel

# CODE PROGRAM DI VISUAL CODE SEBAGAI BERIKUT :
![gambar)](https://github.com/user-attachments/assets/db7a87c6-3aab-461a-94f6-0187414538a5)

# HASIL PROGRAM DI ATAS SEPERTI DI BAWAH INI :
![gambar](https://github.com/user-attachments/assets/8fcf131a-430c-4d39-9c46-56f02bede7a4)

# DAN DI BAWAH INI ADALAH FLOWCHART NYA :
![gambar](https://github.com/user-attachments/assets/3a848af4-286c-46b9-98cd-6b0203bacfb1)






        


