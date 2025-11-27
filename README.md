## Nama: Shofi Aulianda
## Kelas : TI.25.A.2
## NIM : 312510183
## Pertemuan : 11

## Kode latihan 1
<img width="610" height="234" alt="image" src="https://github.com/user-attachments/assets/288fb02d-f932-43f6-b529-96a484286f9e" />

## Output latihan 1
<img width="718" height="175" alt="Screenshot_20251127_080806" src="https://github.com/user-attachments/assets/4106bef9-dac3-4241-9aed-476a354c4e65" />

## Kode tugas praktikum 
<img width="515" height="401" alt="Screenshot_20251127_082637" src="https://github.com/user-attachments/assets/0fc97c6a-f75c-47c2-b276-08e4ab4f0732" />

## Output tugas praktikum
<img width="571" height="194" alt="Screenshot_20251127_084713" src="https://github.com/user-attachments/assets/bbd965e2-dea2-4c30-abd6-d9ef0013c60f" />

## Flowchart
                 ┌────────────────────┐
                 │      MULAI         │
                 └─────────┬──────────┘
                           │
                 ┌─────────▼──────────┐
                 │   Tampilkan Menu   │
                 └─────────┬──────────┘
                           │
                ┌──────────▼───────────┐
                │ Pilih Menu (1 - 5)?  │
                └───────┬───┬───┬───┬──┘
                        │   │   │   │
         ┌──────────────▼┐ ▼ ┌─▼─┐ ▼  ┌───────────────┐
         │   Menu 1?     │ │ │Menu│ │   Menu 5?      │
         │ (Tambah Data) │ │ │ 3? │ │  (Keluar)      │
         └───────┬───────┘ │ │(Hapus)│ └───────┬─────┘
                 │         │ └───┬───┘         │
                 │         │     │             │
        ┌────────▼───┐ ┌──▼──────▼───┐ ┌──────▼──────┐
        │ Input Nama │ │ Input Nama   │ │ Tampilkan   │
        │ Input Nilai│ │ Hapus Data   │ │ "Selesai"   │
        │ Simpan     │ │ Tampilkan Msg│ │   Selesai   │
        └───────┬────┘ └─────────────┘ └─────────────┘
                │
                │
        ┌───────▼─────┐
        │ Kembali ke  │
        │     MENU    │
        └───────┬─────┘
                │
     ┌──────────▼───────────┐
     │ Menu 2? (Tampilkan?) │
     └──────────┬───────────┘
                │
       ┌────────▼─────────┐
       │ Tampilkan Data    │
       │ (Cek Kosong atau  │
       │ tampilkan isi)    │
       └────────┬─────────┘
                │
                │
     ┌──────────▼───────────┐
     │ Menu 4? (Ubah Data?) │
     └──────────┬───────────┘
                │
       ┌────────▼──────────┐
       │ Input Nama         │
       │ Jika Ada → Input   │
       │ Nilai Baru & Ubah  │
       │ Jika Tidak → Msg   │
       └────────┬──────────┘
                │
                │
                ▼
           (Kembali ke MENU)    
    ```
    Fungsi-Fungsi dalam Program
1. tambah()

Digunakan untuk menambahkan data mahasiswa baru.
Program akan meminta:

Nama mahasiswa

Nilai mahasiswa

Kemudian data akan disimpan pada dictionary data_mahasiswa.

2. tampilkan()

Menampilkan seluruh data mahasiswa yang tersimpan.
Jika data masih kosong, program menampilkan pesan “Data masih kosong.”

Data ditampilkan dalam format:
```
Nama: <nama> | Nilai: <nilai>
```

3. hapus(nama)

Menghapus data mahasiswa berdasarkan nama.

*Jika nama ditemukan → data akan dihapus

*Jika tidak ditemukan → muncul pesan “Data 'nama' tidak ditemukan.”

4. ubah(nama)

Mengubah nilai mahasiswa berdasarkan nama.

*Jika nama ada → pengguna memasukkan nilai baru

*Jika nama tidak ada → muncul pesan “Data ‘nama’ tidak ditemukan.”


