# Pengelolaan Data Mahasiswa Menggunakan Konsep Modular dan PBO
Proyek ini adalah aplikasi sederhana untuk mengelola data mahasiswa yang dirancang dengan Pemrograman Modular dan Pemrograman Berorientasi Objek (PBO) menggunakan Python.
Aplikasi ini dirancang untuk memberikan kemudahan dalam pengelolaan data mahasiswa seperti penambahan, pencarian, penghapusan, dan penampilan data. Struktur proyek yang modular memungkinkan kode mudah dipahami, dikembangkan, dan dipelihara.

# Tujuan Proyek
Proyek ini bertujuan untuk memperkenalkan konsep modularitas dan pemrograman berorientasi objek dalam pengembangan perangkat lunak. Dengan memanfaatkan Python, proyek ini memisahkan logika aplikasi ke dalam beberapa modul sesuai dengan tanggung jawabnya. 
Pendekatan ini tidak hanya meningkatkan keterbacaan kode tetapi juga memungkinkan pengembang untuk menambahkan fitur baru tanpa memengaruhi bagian lain dari aplikasi.

# Fitur Utama
#### 1. Menambah Data Mahasiswa
Pengguna dapat menambahkan data mahasiswa baru dengan atribut seperti NIM, Nama, dan Jurusan. Data disimpan dalam daftar yang dikelola oleh kelas khusus.

#### 2. Menampilkan Data Mahasiswa
Aplikasi menyediakan fitur untuk menampilkan daftar mahasiswa secara rapi dengan menampilkan semua atribut yang tersedia.

#### 3. Mencari Data Mahasiswa
Fitur pencarian memungkinkan pengguna menemukan mahasiswa berdasarkan NIM. Jika data ditemukan, aplikasi akan menampilkan informasi mahasiswa tersebut.

#### 4. Menghapus Data Mahasiswa
Data mahasiswa dapat dihapus berdasarkan NIM. Fitur ini memastikan data yang tidak relevan atau tidak valid dapat dikeluarkan dari daftar.

## Struktur Proyek
Proyek ini memiliki struktur direktori sebagai berikut:
```
markdown

Project_Mahasiswa/
├── class_data/
│   ├── data.py
│   ├── __pycache__/ (Placeholder)
├── class_process/
│   ├── process.py
│   ├── __pycache__/ (Placeholder)
├── class_view/
│   ├── view.py
│   ├── __pycache__/ (Placeholder)
├── main.py
├── __pycache__/ (Placeholder)

py
```
###### `class_data/data.py`
Modul ini bertanggung jawab untuk mendefinisikan kelas Mahasiswa dan DataMahasiswa. Kelas Mahasiswa merepresentasikan objek mahasiswa, sedangkan DataMahasiswa mengelola daftar mahasiswa, termasuk metode untuk menambahkan dan mengambil data.
![image](https://github.com/user-attachments/assets/08288bc4-fbd3-4ec8-9831-b84c80405d6b)

###### `class_process/process.py`
Modul ini menangani logika pemrosesan, seperti pencarian dan penghapusan data mahasiswa berdasarkan NIM. Modul ini memisahkan logika bisnis dari penyimpanan data untuk menjaga modularitas.
![image](https://github.com/user-attachments/assets/d783c31a-4afb-4019-bf92-1dfc8822505d)

###### `class_view/view.py`
Modul ini digunakan untuk menampilkan data ke pengguna. Semua format output dikelola di sini untuk menjaga pemisahan antara logika pemrosesan dan antarmuka.
![image](https://github.com/user-attachments/assets/97f72d70-cfce-4ec4-863e-db9bb35b2fdd)

###### `main.py`
File utama aplikasi yang mengintegrasikan semua modul. File ini memuat implementasi langsung dari fitur seperti menambah, mencari, menampilkan, dan menghapus data mahasiswa.
![image](https://github.com/user-attachments/assets/188c2fa5-fab4-40cf-bf42-e0f39caae36d)



-----------------------------------------------------------------------------------------------------------------------------


## Keunggulan Proyek
###### `Skalabilitas`: Mudah menambahkan fitur baru berkat pendekatan modular.
###### `Reusabilitas`: Kelas dan metode yang sudah ada dapat digunakan kembali di proyek lain.
###### `Keterbacaan`: Kode terstruktur dan mudah dipahami.

Proyek ini merupakan implementasi dasar dari pengelolaan data mahasiswa menggunakan konsep Pemrograman Modular dan Pemrograman Berorientasi Objek (PBO).Dengan membagi kode ke dalam modul-modul terpisah yang masing-masing memiliki tanggung jawab spesifik, 
proyek ini tidak hanya memberikan kemudahan dalam pengelolaan data, tetapi juga memperkenalkan cara-cara efisien dalam menulis kode yang terstruktur dan mudah dipelihara.

Melalui pengembangan lebih lanjut, proyek ini dapat diperluas dengan berbagai fitur tambahan, seperti integrasi dengan database atau antarmuka grafis, untuk menghadirkan aplikasi yang lebih canggih dan mudah diakses. Diharapkan proyek ini dapat menjadi fondasi 
yang kokoh bagi mereka yang ingin memahami dan memanfaatkan konsep-konsep dasar dalam pemrograman modular dan berorientasi objek.

Semoga dokumentasi ini membantu dalam memahami alur dan struktur aplikasi. Terima kasih telah meluangkan waktu untuk menjelajahi proyek ini, dan jika Anda memiliki pertanyaan atau masukan, jangan ragu untuk menghubungi saya melalui repositori GitHub.
