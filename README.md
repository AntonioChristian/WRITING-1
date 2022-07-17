# WRITING-1
UNIX COMMAND LINE,GIT&amp;GITHUB,HTML,CSS,ALGORITMA
# UNIX COMMAND LINE

* **Unix command line**: sebuah metode untuk berinteraksi dengan computer melalui beberapa perintah atau biasa disebut dengan (command) yang dimana
penulisan/pengerjaan baik memindahkan, membuat, ataupun mengcopy file semua prosesnya base on terminal .


•	Ada beberapa cara untuk mengakses Command Line dengan menggunakan beberapa tools yang biasa di gunakan yaitu: 
-	Power shell
-	Command prompt

• Anatomi pada tampilan terminal powershell

(P C:\user\ASC>)


•	Adapun perintah atau navigasi yang biasa digunakan di terminal unix command line: 
1.	LS (List Folder): menampilkan list folder yang ada pada directory
2.	CD (memindahkan folder)
3.	CD .. (Untuk berpindah ke folder sebelumnya)
4.	Clear (membersihkan tampilan pada terminal)
5.	Ni_nama file.ekstensi (membuat file baru) maksud dari ekstensi disini contoh (.doc ,.htm, .tx) tetapi jika terminal di linux perintahnya menjadi touch_nama file.ektensi
6.	Cp_nama file yang mau di copy.ekstensi _ nama file baru.ekstensi (mencopy file). Agar mudah di baca oleh terminal. File yg akan di copy di buat terlebih dahulu
7. cp_nama file yang mau dicopy.ektensi nama directory\nama folder yang ingin di copy(perintah untuk mencopy file ke folder)
8. cp -r_nama folder (perintah mencopy folder beserta isi dalam folder yang mau di copy)
9. rm_nama folder yang mau dihapus (perintah menghapus file)
10. rm contoh-copy.txt (perintah untuk menghapus multiple text) contoh : contoh-powershell.txt. setiap file yang berbeda harus diberi tanda koma (,)
11.	Mv nama folder yang mau di pindahkan.ekstensi (memindahkan / moving file ke directory baru)
12.	Mkdir_nama folder yang akan dibuat (membuat folder atau directory baru tanpa spasi)
13. Mkdir "nama folder baru" (perintah membuat file baru dengan menggunakan spasi)


# GIT & GITHUB

• **GIT** : Merupakan tools yang sering atau awam digunakan oleh programer yang dapat melacak setiap perubahan yg terjadi pada suatu folder. Git juga bisa di asumsikan sebagai Version Control System.

• **GIT & GITHUB** : Merupakan tools code collaboration yang wajib ada bagi setiap programer yang berfungsi untuk saling berkolabirasi dalam mengembangkan suatu project.

• **Yang membedakan GIT DAN GITHUB** : 

**GIT** dapat menggunakan *command-line tool* yang berfungsi untuk pengubah code serta dapat digabungkan menuju perangkat lokal. sedangkan **GITHUB** merupakan penyedia *interface* grafis berbasis *cloud* sebagai tempat untuk melakukan seluruh tugas.

* ### Apa Itu Version Control System ? 
Tugasnya adalah *Mencatat* setiap *Perubahan* pada *file* dalam suatu proyek

* Git juga biasanya digunakan oleh programer sebagai penyimpanan fle pemrograman mereka karena lebih efektif. file yang disimpan menggunakan git akan terlacak seluruh perubahannya termaksuk siapa yang mengubah filenya.

* ### Kenapa programer perlu menggunakan Git dan Github? dengan menggunakan **GIT** dan **GITHUB**, setiap programer akan bisa bekerja dalam sebuah tim dengan tujuan dapat **Berkolaborasi** mengerjakan proyek yang sama tanpa harus repot **Copy paste** folder aplikasi yang terupdate.


• **INSTALASI GIT**

1. Cek apakah instalasi berhasil dengan menggunakan 

2. Setup Awal

3. Cek apakah setup berhasil

* yang harus di perhatikan bahwa dalam mengseup, email harus **SAMA** dengan email yang digunakan pada **GITHUB**

## PERINTAH (COMMAND)

• **REPOSITORY GIT**

- Merupakan directory proyek yang dibuat. dimana 1 repo= 1 proyek= 1 Direktory

1. Membuat Repository

![repository](image/repository.jpeg)

Command di atas merupakan perintah membuat sebuah directory baru. Jika folder sudah ada sebelumnya maka kita tidak lagi menggunakan command di atas melainkan ada command yang baru yaitu (**git init.**)

2. Git Status

- merupakan command untuk mengecek status repository yang kita buat tadi apakah filenya sudah ada atau tidak


• Ada 3 kondisi file pada git

- **MODIFIED**

  Kondisi dimana revisi atau **Perubahan Sudah Dilakukan**, tetapi belum **ditandai** dan **belum disimpan** didalam version control 

- **STAGED**

  Kondisi dimana **Revisi sudah ditandai** namun **Belum di simpan** didalam Version Control

- **COMMITTED**

  Kondisi dimana **Revisi sudah disimpan** didalam Version Control

3. GIT ADD

- Command atau perintah untuk menambahkan 1 file ke stagging area dan masih perlu di comit kembali. 

4. GIT COMMIT

- Perintah atau Command yang digunakan untuk save perubahan pada version control

5. GIT LOG

- Perintah atau command yang digunakan untuk melihat history/kumpulan (commit) yang telah di buat

6. GIT REVERT

- Perintah yang digunakan untuk membatalkan semua perubahan yang ada tanpa menghapus commit. (git revert -n (nomor commit)

7. GIT BRANCH

- Perintah yang dapat digunakan untuk kolaborasi di satu branch yang sama
Jika mau membuat fitur register, command yang digunakan,


8. GIT REMOTE

Perintah yang digunakan untuk melihat brhasil atau tidak antara GIT & GITHUB. Contoh perintahnya (git remote -v)

# HTML
- **HTML** Merupakan bahasa Computer yang digunakan untuk membuat **Kerangka atau Struktur** Web Pages. HTML berperan penting dalam pengembangan web dimana html bisa membuat suatu halaman website yang bisa dibaca dan dipahami dengan lebih mudah.HTML bersifat static yaitu hanya menampilkan gambar untuk pengalaman *interface* user

### HTML TAG
- HTML terdiri dari komponen yaitu **HTML TAG**
pada umumnya, ada 2 tipe HTML Tag :
1. **OPENING TAG** (Tag Pembuka)
2. **CLOSING TAG** (Tag Penutup)


### STRUKTUR DOKUMEN HTLM
- Dokumen HTML memiliki 3 tag utama yaitu <(html)>, <(head)>, dan <(body)>


### TAG HTML

- Ada beberapa tag yang populer digunakan 
1. a 
2. (P)
3. (H1-H6)
4. (Title)
5. (Head)
6. (ol) & (ul)
7. (img)
8. (video)
9. (nav)

### ATRIBUTE HTML
1. Id
2. class
3. href
4. src
5. div


# CSS
- Merupakan bahasa computer yang digunakan untuk *mendesign* suatu halaman website ke internet. peran css dalam web developmend ialah sebagai tampilan *interface* yang bisa memanjakan mata baik dalam segi gambar, warna dan styling lainnya.

### MENYISIPKAN CSS
- Ada 3 cara dalam menyisipkan CSS Kedalam HTML
1. INLINE (Menggunakan Atribute style)
2. INTERNAL (Menggunakan element style)
3. EKSRENAL (Membuat File Terpisah)

### CSS SYNTAX
- Merupakan syntax yang digunakan untuk menunjukan atau memilih element HTML yang akan di beri style. syntaxnya seperti ini :


# ALGORITMA DAN PSEUDOCODE
- **ALGORITMA** Adalah langkah-langkah yang di ambil untuk menyelesaikan masalah.
- Mengapa kita harus belajar struktur data dan algoritma ? Memudahkan kita dalam proses menyelesaikan permasalahan memulai bahasa pemrograman dan membuat program yang kita buat menjadi lebih efisien
- Tujuan membuat algiritma ialah sebagai sarana dalam mengasah kemampuan analisa dalam setaip permasalahan yang terjadi
- **PSEUDOCODE** Adalah penulisan sebuah algoritma menggunakan bahasa general atau tidak spesifik
