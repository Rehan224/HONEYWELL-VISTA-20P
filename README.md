**PROGRAM-ALARM-HONEYWELL-VISTA-20P**
```markdown
> Default Master Code : 1234
> Default Installer Code: 4112
> Masuk Program : [Installer Code] 800
> Keluar Program : *99
> Lupa Installer Code :
  - Matikan dan Nyalakan Panel
  - Tunggu ±20 detik
  - tekan * dan # secara bersamaan selama 3 detik
> Lupa Master Code
  - Masuk Program
  - [*20]
  - Isi Code baru (4 digit)
Note: otomatis Installer dan Master Code berubah 
```
- Cara Mengganti Master Code
  - Master Code + 8 + 02 + Master Code Baru

- Cara Mengganti User Code
  - Master Code + 8 + 03 + User Code Baru

- Cara Reset Program
  - Masuk Program
  - [*97]
    
- Cara Mengganti Installer + Master Code 
  - Masuk Program
  - [*20]
  - Isi Code baru (4 digit)
    
- Cara Mengatur Zona
  - Masuk Program
  - [*56]
  - Urutan Zona (01 - 08)
  - Jenis Zona (00, 01, 03, 07)
    ```
    Note:
    Jenis Zona,
    (00) matikan zona
    (01) Untuk Delay
    (03) Untuk Instant
    (07) Untuk 24 jam
    ```
    
- Cara Mengatur Entry Delay
  - Masuk Program
  - [*35]
  - Isi durasi Entry Delay (2 digit) dalam satuan detik
  - Isi ulang durasi Entry Delay

- Cara Mengatur Exit Delay
  - Masuk Program
  - [*34]
  - Isi durasi Exit Delay (2 digit) dalam satuan detik
  - Isi ulang durasi Exit Delay 

- Cara Menambahkan Nomor HP
  - Masuk Program
  - [23]
  - Isi Nomor HP
  - Tekan # (untuk simpan program)
    ```
    Note:
    > Untuk Menambahkan nomor HP bisa sampai 4 nomor HP
    > Ganti code [23] jadi [24], [25], [26]
    > Jadi nanti urutannya,
    [23] untuk nomor pertama
    [24] untuk nomor kedua
    [25] untuk nomor ketiga
    [26] untuk nomor keempat
    ```
---
- Pengetesan Alarm
  - Cara Mengaktifkan Alarm
    - Masukkan User_Code
    - Tekan ARM
  - Cara Mematikan alarm
    - Masukkan User_Code
    - Tekan DISARM
  - Cara Mematikan Sirine
    - Masukkan User_Code
    - Tekan DISARM
  - Cara Hapus Ter-memori
    - Masukkan User_Code
    - Tekan DISARM
---
```markdown
KETERANGAN:
A-01
> A = sudah terjadi alarm, atau ter-memori
> 01 = Urutan Zona

F-01
> F = detektor terbuka
> 01 = Urutan Zona
```
