SQL (Structured Query Language) adalah bahasa pemrograman yang digunakan untuk mengelola dan berinteraksi dengan basis data relasional. SQL digunakan untuk menyimpan dan memproses informasi dalam basis data relasional, yang menyimpan informasi dalam bentuk tabel, dengan baris dan kolom yang mewakili atribut data yang berbeda serta berbagai hubungan antara nilai data.

## Jenis-Jenis Perintah SQL

Ada beberapa jenis perintah yang digunakan dalam penggunaan SQL. Dimana jenis perintah dibutuhkan seperlu mengakses dan memanajemen data dalam databse. Jenis perintah SQL yang dimaksud adalah sebagai berikut:

### 1. DDL (_Data Definition Language_)

DDL merupakan sub perintah bahasa SQL yang dimanfaatkan guna membangun kerangka database. Seperti halnya tabel dan database. Ada 3 perintah penting di dalam DDL, diantaranya create, alter, dan drop.  
Create merupakan suatu perintah untuk membuat beberapa kebutuhan. Seperti database anyar, kolom anyar, view anyar, dan tabel anyar. Alter merupakan perintah yang berfungsi mengubah struktural tabel yang sudah dibuat. Melibuti pengubahan nama tabel, penambahan kolom, pengubahan kolom, penghapusan kolom, dan menambah atribut kolom. Sedangkan drop merupakan perintah untuk menghapus database ataupun tabel.

### 2. DML (_Data Manipulation Language_)

DML merupakan sub perintah bahasa SQL yang dimanfaatkan dalam manipulasi data database yang sudah dibuat. Ada 4 perintah penting di dalam DML. Keempat perintah yang dimaksud yaitu insert, select, update, dan delete.  
Empat perintah penting DML memiliki fungsi berbeda. Dimana insert merupakan perintah yang bisa digunakan untuk memasukkan data baru dalam tabel. Perintah ini dapat dijalankan saat database dan tabel telah selesai dibuat. Select merupakan perintah untuk mengambil lalu menampilkan data dari tabel atau sejumlah table memanfaatkan relasi. Update adalah perintah untuk memperbarui data dalam tabel. Sementara delete adalah perintah untuk mengahpus data dari tabel.

### 3. DCL (_Data Control Language_)

DCL merupakan sub bahasa SQL dengan fungsi pengontrolan data dan server database. Misalnya manipulasi _user_ dan _priviledges_. Terdapat 2 perintah penting dalam DCL yakni _gran_t dan _revoke_.  
_Grant_ merupakan perintah untuk memberi hak akses dari admin ke pengguna atau _user_. Adapun hak akses yang dimaksud bisa hak untuk membuat, mengambil data, mengubah data, hingga menghapus data. Selain itu ada hak khusus lainnya yang diberikan berkaitan dengan sistem database. Sedangkan _revoke_ merupakan perintah untuk mencabut hak akses yang sabelumnya diberikan kepada pengguna. Jadi bisa dibilang _revoke_ memiliki fungsi berkebalikan dengan _grant_.