# Aplikasi Data Mahasiswa

Aplikasi Data Mahasiswa adalah aplikasi web untuk mengelola data mahasiswa. Pada aplikasi ini terdapat fitur CRUD (Create, Read, Update, Delete) untuk mengelola data mahasiswa dari aplikasi web ke sistem basis data.

# Basis Data

Basis data yang digunakan adalah MySQL.
1. Server    = localhost
2. Username  = root
3. Password  = 
4. Database  = uts_webprog1
5. TableName = data_mahasiswa

# Struktur Basis Data

   Nama        Type
1. nim         varchar(9)
2. nama        varchar(35)
3. jurusan     varchar(50)

# Software yang Dibutuhkan

1. XAMPP Control Panel
2. Visual Studio Code
3. Web Browser (Google Chrome)

# Penjelasan Aplikasi

Pada halaman beranda terdapat judul aplikasi, table data, button tambah data, button ubah dan button hapus.

Jika ingin menambahkan data, klik button tambah data. Kemudian ketikkan NIM, Nama, Jurusan. Klik Simpan. Pada proses tambah data, data yang dimasukkan tidak boleh kosong, dan pada bagian field NIM hanya boleh dimasukkan nilai angka dan dibatasi hanya 9 inputan. Jika tidak sesuai maka tidak bisa disimpan.

Jika ingin merubah data, klik button ubah pada baris data yang akan dirubah. Pada halaman ubahData pengguna hanya dapat merubah data nama dan jurusan saja. Oleh karena itu, field NIM tidak dapat diketik. Field nama dan jurusan tidak boleh kosong. Jika kosong maka tidak akan bisa disimpan.

Jika ingin menghapus data, klik button hapus pada baris data yang akan dihapus.

Jika tidak ada data yang disimpan, maka table data mahasiswa akan muncul pesan data nihil.

# Dibuat oleh

1. Nama    : Maulana Abdul Siddiq
2. NIM     : 16090112
3. Kelas   : 4C
4. Teknik Informatika
