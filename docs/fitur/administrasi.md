---
sidebar_position: 1
description: Panel manajemen administrasi sekolah
---

# Administrasi

Pada modul Administrasi terbagi menjadi 2 submodul yang dapat mengatur kebutuhan administrasi sistem Anda.

- Pengguna
- Informasi Sekolah

## Pengguna

Submodul Pengguna adalah panel untuk mengorganisir siapa saja yang dapat mengakses sistem ini dengan pilihan _role_ sebagai berikut:

- Admin Sekolah
- Kepala Sekolah
- Tata Usaha
- Bendahara

> Untuk mengetahui hak akses setiap _role_, bisa merujuk ke halaman [Hak Akses Pengguna](/docs/pengetahuan-dasar/hak-akses-pengguna).

Menu pengguna bisa diakses dari menu Administrasi - Pengguna.

![Menu pengguna](/img/administrasi/pengguna/menu.png)

### Data Pengguna

Berikut tampilan halaman data pengguna.

![Menu pengguna](/img/administrasi/pengguna/data.png)

### Tambah Pengguna

Berikut tampilan halaman tambah pengguna.

![Menu pengguna](/img/administrasi/pengguna/form.png)

:::caution PERHATIAN

- Nama - Wajib diisi.
- Email - Wajib diisi.
- Jabatan - Wajib diisi.

:::

### Integrasi Staff

Setiap data pengguna terintegrasi dengan data staff, sehingga setiap pertambahan pengguna, maka staff juga turut bertambah. Lebih jauh tentang hal ini, bisa dibaca di halaman [Staff](/docs/fitur/sekolah.md).

## Informasi Sekolah

## Impor Sekolah

Ini adalah halaman khusus untuk Admin Sempoa untuk dapat meng-_import_ satu informasi penuh tentang sebuah sekolah.

> Format file Excel-nya bisa diunduh dari [sini](/file/schools_import.xlsx).

Ada enam bagian/halaman pada file import tersebut, antara lain:

1. General
2. Tingkatan
3. Data Guru & staff
4. Data Dompet
5. Tipe Uang Sekolah
6. Data Siswa

:::danger PERHATIAN

Seluruh nama kolom harus sama dengan ketentuan di bawah ini. Ketidaksesuaian dengan template akan menimbulkan hasil yang berbeda.

:::

### General

Pada bagian **general** terdapat 14 poin berurutan yang **wajib diisi** seluruhnya, antara lain:

| Kolom                                       | Contoh Data                        | Keterangan                                   |
| ------------------------------------------- | ---------------------------------- | -------------------------------------------- |
| Nama Sekolah                                | SDN 01                             | wajib                                        |
| **_Nomor Pokok Sekolah Nasional_**          | XYYZZZZZ                           | wajib. <br />8 digit unik                    |
| Tingkat Sekolah (TK / SD / SMP / SMA / SMK) | SD                                 | wajib.<br /> opsi: TK / SD / SMP / SMA / SMK |
| Alamat                                      | Jalan Raya, No. XX, RT 00Y/00Z     | wajib                                        |
| Email Sekolah (email resmi utk kontak)      | info@sdn01-bogor.sch.id            | wajib                                        |
| No Telpon Sekolah                           | 08xxxxxxxxx                        | wajib                                        |
| Nama Kepsek / Penanggungjawab Umum          | Abraham Lincoln                    | wajib                                        |
| **_NIK Kepsek_**                            | 1234567812345678                   | wajib                                        |
| **_Email Kepsek_**                          | abraham.lincoln@sdn01-bogor.sch.id | wajib                                        |
| No Telpon Kepsek (WA)                       | 08xxxxxxxxx                        | wajib                                        |
| Nama Admin                                  | Ilyas Teknologi                    | wajib                                        |
| **_NIK Admin_**                             | 8765432187654321                   | wajib                                        |
| **_Email Admin_**                           | ilyas.teknologi@sdn01-bogor.sch.id | wajib                                        |
| Tahun akademik yang sedang berjalan         | 2023-2024                          | wajib                                        |

:::caution PERHATIAN

Nomor Pokok Sekolah Nasional, email dan NIK kepala sekolah, serta email dan NIK admin sekolah menjadi **_identifier_**.

Nomor Pokok Sekolah Nasional bisa dicari dari halaman [Dapodik](https://dapo.kemdikbud.go.id/pencarian).

:::

### Tingkatan

Pada bagian **tingkatan** terdapat 2 poin berurutan yang **wajib diisi** seluruhnya, antara lain:

| Kolom         | Contoh Data                  | Keterangan                         |
| ------------- | ---------------------------- | ---------------------------------- |
| Tingkat Kelas | 1 _atau_ 1 SD _atau_ Kelas 1 | wajib                              |
| Kelas         | 1 A, 1 B, 1 C,1 D, 1 E       | wajib.<br />dipisahkan dengan koma |

Berikut simulasinya:

| Tingkat Kelas | Kelas              |
| ------------- | ------------------ |
| Kelas 1       | 1 A, 1 B, 1 C, 1 D |
| Kelas 2       | 1 A, 1 B, 1 C, 1 D |
| Kelas 3       | 1 A, 1 B, 1 C, 1 D |
| Kelas 4       | 1 A, 1 B, 1 C      |
| Kelas 5       | 1 A, 1 B, 1 C      |
| Kelas 6       | 1 A, 1 B           |

:::caution PERHATIAN

Semua data adalah **_identifier_**, maka perlu diperhatikan penulisannya. Perbedaan titik, spasi, bahkan 1 huruf akan menyebabkan perubahan
data yang signifikan.

:::

### Data Guru & Staff

Pada bagian **data guru & staff** terdapat 9 poin berurutan yang **wajib diisi** seluruhnya, antara lain:

| Kolom         | Contoh Data                                           | Keterangan                      |
| ------------- | ----------------------------------------------------- | ------------------------------- |
| **_NIK_**     | AABBCCEEFFGGHHHI                                      | wajib                           |
| Nama          | Amelia Widiastuti                                     | wajib                           |
| Alamat        | Psr. Kusmanto No. 440, Bandar Lampung 92712, Bengkulu | wajib                           |
| No Telp       | 08xxxxxxxxx                                           | wajib                           |
| Tanggal Lahir | 12/30/2013                                            | wajib <br /> format: MM/DD/YYYY |
| Jenis Kelamin | P                                                     | wajib <br /> opsi: L / P        |
| Agama         | Katolik                                               | wajib                           |
| No KK         | AABBCCEEFFGGHHHI                                      | wajib                           |
| Jabatan       | guru                                                  | tidak wajib                     |

:::caution PERHATIAN

NIK menjadi **_identifier_**.

:::

### Data Dompet

Pada bagian **data dompet** terdapat 3 poin berurutan yang **wajib diisi** seluruhnya, antara lain:

| Kolom      | Contoh Data | Keterangan                      |
| ---------- | ----------- | ------------------------------- |
| **_Nama_** | Kas Sekolah | wajib                           |
| Saldo Awal | 100000      | wajib. <br /> tanpa titik/koma. |
| Dana BOS?  | n           | wajib. <br /> opsi: y / n       |

:::caution PERHATIAN

Nama dompet menjadi **_identifier_**.

:::

Berikut simulasinya:

| Nama           | Saldo Awal | Dana BOS? |
| -------------- | ---------- | --------- |
| Kas Sekolah    | 0          | n         |
| BCA 123123     | 15890000   | n         |
| Mandiri 321321 | 5850000    | n         |
| BOS            | 0          | y         |

### Tipe Uang Sekolah

Pada bagian **tipe uang sekolah** terdapat 4 poin berurutan yang **wajib diisi** seluruhnya, antara lain:

| Kolom               | Contoh Data | Keterangan                                  |
| ------------------- | ----------- | ------------------------------------------- |
| **_Nama_**          | SPP         | wajib                                       |
| Rutin?              | y           | wajib. <br /> opsi: y / n                   |
| **_Tingkat Kelas_** | Kelas 1     | wajib. <br /> sesuai dengan data Tingkatan. |
| Nominal             | 150000      | wajib. <br /> tanpa titik/koma.             |

:::caution PERHATIAN

Nama dan Tingkat Kelas menjadi **_identifier_**.

:::

Berikut simulasinya:

| Nama       | Rutin? | Tingkat Kelas | Nominal |
| ---------- | ------ | ------------- | ------- |
| SPP        | y      | Kelas 1       | 150000  |
| SPP        | y      | Kelas 2       | 150000  |
| SPP        | y      | Kelas 3       | 150000  |
| SPP        | y      | Kelas 4       | 150000  |
| SPP        | y      | Kelas 5       | 150000  |
| SPP        | y      | Kelas 6       | 150000  |
| Uang Ujian | n      | Kelas 1       | 50000   |
| Uang Ujian | n      | Kelas 2       | 50000   |
| Uang Ujian | n      | Kelas 3       | 50000   |
| Uang Ujian | n      | Kelas 4       | 50000   |
| Uang Ujian | n      | Kelas 5       | 50000   |
| Uang Ujian | n      | Kelas 6       | 50000   |

### Data Siswa

Pada bagian **data siswa** terdapat 26 poin berurutan yang **wajib diisi** seluruhnya, kecuali beberapa, antara lain:

| Kolom             | Contoh Data               | Keterangan                                  |
| ----------------- | ------------------------- | ------------------------------------------- |
| Nama              | Lukita Jamil              | wajib                                       |
| Email             | lukita@gmail.com          | wajib                                       |
| Jenis Kelamin     | L                         | wajib.<br />opsi: L / P                     |
| Alamat            | Jalan Raya XYZ            | wajib                                       |
| Tanggal Lahir     | dd-mm-yyy                 | wajib                                       |
| Agama             | Katolik                   | wajib                                       |
| No Telp           | 081xxxxx                  | wajib                                       |
| No KK             | 3989yyyy                  | wajib                                       |
| **_NIK_**         | 3989zzzz                  | wajib                                       |
| **_NISN_**        | 1234xxxx                  | wajib                                       |
| **_NIS_**         | 5678yyyy                  | wajib                                       |
| Nama Ayah         | Harjasa Parman            | wajib                                       |
| Alamat Ayah       | Jl Diponegoro             | tidak wajib                                 |
| Email Ayah        | harjasa.parman@gmail.com  | tidak wajib                                 |
| No Telepon Ayah   | 0878xxxx                  | tidak wajib                                 |
| Nama Ibu          | Hartati Parwati           | wajib                                       |
| Alamat Ibu        | Jl Diponegoro             | tidak wajib                                 |
| Email Ibu         | hartati.parwati@gmail.com | tidak wajib                                 |
| No Telp Ibu       | 0878xxxx                  | tidak wajib                                 |
| Nama Wali         | Harjasa Parman            | tidak wajib                                 |
| Alamat Wali       | Jl Diponegoro             | tidak wajib                                 |
| Email Wali        | harjasa.parman@gmail.com  | tidak wajib                                 |
| No Telp Wali      | 0878xxxx                  | tidak wajib                                 |
| Kelas             | 1 A                       | wajib.<br />sesuai dengan data kelas.       |
| Nominal           | 100000                    | wajib.<br />tanpa titik/koma.               |
| Tipe Uang Sekolah | SPP                       | wajib.<br />sesuai dengan tipe uang sekolah |

:::caution PERHATIAN

NIK, NIS, dan NISN menjadi **_identifier_**.

NISN bisa dicari dari halaman [Dapodik](https://nisn.data.kemdikbud.go.id/index.php/Cindex/formcaribynama).

:::
