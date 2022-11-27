# Pertemuan10-praktikum5
Repositiry ini dibuat untuk memenuhi tugas Pertemuan 10 - Bahasa Pemrograman (Module Praktikum 5)

Nama : saripudin

NIM : 312210077

Matkul : Bahasa Pemrograman

Kelas : TI.22.B.1

Pada halaman ini (Tugas Pertemuan-9-Module Praktikum 5) Dosen memberi tugas sebagai berikut :

* Latihan yang ada pada module praktikum 5

![Latihan-soal1](https://user-images.githubusercontent.com/115473865/204139139-972da427-6dca-4207-b457-cbb67be5c468.png)

print("===================================================================")
print("Nama         :   saripudin")
print("NIM          :   312210077")
print("Kelas        :   TI.22.B1")
print("Mata Kuliah  :   B. Pemrograman")
print("===================================================================")

* Berikut adalah program syntax yang saya buat untuk memenuhi latihan module 5

  ```Python
# Buat dictionary daftar kontak
print("Buat dictionary nama sebagai key, dan nomor sebagai value")

isi = {'Ari': '081267888', 'Dina': '087677776'}
print("Nama | Nomor kontak")
print(isi)

print("Tampilkan Kontaknya Ari")
print(isi['Ari'])

print("Tambah kontak baru dengan nama Riko, nomor 087654544")
isi['Riko']= '087654544'
print(isi)

print("Ubah kontak Dina dengan nomor baru 088999776")
isi['Dina']= '088999777'
print(isi)

print("Tampilkan semua Nama")
print(isi.keys())

print("Tampilkan semua Nomor")
print(isi.values())

print("Tampilkan daftar Nama dan nomornya")
print(isi.items())

print("Hapus kontak Dina")
del isi['Dina']
print(isi)

print("===================================================================")
