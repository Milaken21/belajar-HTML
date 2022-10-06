**Web Development Basic
DAY 1
Unix Command Line Git & GitHub Dasar**

* Aplikasi dibagi menjadi 2 jenis dari segi tampilan yaitu GUI (Graphic User Interface)  dan CLI (Command Line Interface)
* Command line interface (CLI) atau Shell yang berbasis teks
* Shell merupakan perintah yang digunakan untuk mengintruksikan sistem operasi
* Shell ini adalah program yang menerima perintah, kemudian meneruskan perintah tersebut ke system untuk dieksekusi. 
* Contoh CLI sh, bash, zsh, dan cmd.exe
* Bash (Bound Again Shell) identik untuk unix/linux
* Shell, program yang digunakan untuk berkomunikasi atau memerintah sistem
* Command Line Interface, jenis shell yang berbasis teks
* Terminal Emulator, aplikasi untuk mengakses CLI
* Sebuah filesystem mengatur bagaimana data disimpan di dalam sebuah system
* Sistem operasi Windows & Unix-like menyusun file dan direktori menggunakan struktur yang bentuknya mirip tree  
* File System Tree: Cara sistem operasi menyusun file-filenya dalam bentuk hierarki atau tree
* Direktori yang paling atas atau paling pertama disebut “root directory”.
* Ditambah -a untuk melihat file yang di hidden atau disembunyikan

# Command untuk navigasi
* Pwd (Print Working Directory) command untuk melihat current working directry
* Ls (lists) command untuk melihat isi file yang ada di sebuah directory
* Cd (Change Directory) Command untuk pindah directory

# Membuat files dan direktori
* Touch command untuk membuat sebuah file
* Mkdir command untuk membuat sebuah direktori

# Melihat isi file
* Head command untuk melihat beberapa line awal dari sebuah file text
* Tail command untuk melihat beberapa line awal dari sebuah file text
* Cat command untuk melihat isi file

# Menyalin, memindahkan, dan menghapus files & directory
* Cp command untuk mengcopy file atau directory
* Mv (Move) Command untuk memindahkan files atau directory, bisa juga di gunakan untuk rename.
* Rm (Remove) command untuk menghapus file atau directory 

# Summary
* Command “head”, “tail”, dan “cat” untuk isi files di awal, akhir, dan keseluruhan.
* Command “touch” untuk membuat file
* Command “mkdir”  untuk membuat directory
* Command “cp” untuk menyalin file, “cp -R” untuk menyalin directory
* Command “mv” untuk memindahkan file, “mv -R” untuk memindahkan directory
* Command “rm” untuk menghapus file, “rm -R” atau “rm -d” untuk menghapus directory

# GIT & GITHUB
* Git merupakan tools untuk programmer
* Git sebagai version control system
* Version control sistem bertugas untuk  mencatat setiap perubahan pada File (termasuk code yang kita buat) pada suatu proyek baik dikerjakan secara individu maupun tim.
* Git adalah aplikasi yang dapat melacak setiap perubahan yang terjadi pada suatu folder atau file.
* File -file yg disimpan menggunakan git akan terlacak seluruh perubahannya, termasuk siapa yang mengubah.
* Tujuan menggunakan git dan github adalah untuk berkolaborasi mengerjakan proyek yang sama tanpa harus repot copy paste folder aplikasi yang terupdate. Kamu juga tidak perlu menunggu rekan dalam satu tim kamu menyelesaikan suatu program dahulu untuk berkolaborasi. 
* Repository adalah direktori proyek yang kita buat
* 1 repo = 1 proyek = 1 Direktori

# SETUP & INIT
* Git init, inisialisasi direktori yang ada sebagai repository git. Mampu melacak perubahan
* Git klon [url] mengambil seluruh repositori dari lokasi yang dihosting melalui url

# STAGE & SNAPSHOT
* Git status, menampilkan file yang dimodifikasi di direktori kerja, ditampilkan untuk komit anda yang berikutnya
* Git add [file], tambahkan file seperti yang terlihat sekarang ke komit Anda (tahap) berikutnya
* Git add . semua file ditandain
* Git reset [file], unstage file sambil mempertahankan perubahan di direktori kerja
* Git diff, perbedaan dari apa yang diubah tetapi tidak ditampilkan
* Git diff –staged, perbedaan dari apa yang dipentaskan tetapi belum dilakukan 
* Git commit -m “[descriptive message]” komit konten Anda yang dipentaskan sebagai snapshot komit baru 

# BRANCH & MERGE
* Git branch, daftar cabang Anda. akan muncul di sebelah cabang yang sedang aktif 
* Git branch [branch-name], membuat branch baru di commit yang sekarang
* Git checkout, beralih ke cabang lain dan periksa ke direktori kerja Anda
* Git merge [branch], gabungkan riwayat cabang yang ditentukan ke yang sekarang
* Git log, tampilkan semua komit dalam riwayat cabang saat ini

# INSPECT & COMPARE
* Git log, menampilkan history commit untuk perubahan aktif yang sekarang
* Git log branchB..branchA, menampilkan commit di branchA yang tidak ada di branchB
* Git log –follow [file] menampilkan commit yang merubah file, bahkan diseluruh pergantian nama
* Git diff branchB…branchA, menampilkan perbedaan dari apa yang ada di branchA yang tidak ada di branchB 
* Git show [SHA], menampilkan objek apa pun di Git dalam format yang dapat dibaca manusia 

# SHARE & UPDATE 
* Git remote add [alias] [url], menambahkan sebuah url git sebagai sebuah alias
* Git fetch [alias], ambil semua cabang dari remote Git itu
* Git merge [alias]/[branch], gabungkan cabang jarak jauh ke cabang Anda saat ini untuk memperbaruinya 
* Git push [alias][branch], Mengirimkan komit cabang lokal ke cabang repositori jarak jauh 
* Git pull, ambil dan gabungkan komit apa pun dari cabang jarak jauh pelacakan 

# TRACKING PATH CHANGES
* Git rm, hapus file dari proyek dan lakukan penghapusan untuk komit
* Git mv [existing-path] [new-path], ubah jalur file yang ada dan lakukan langkah 
* Git log –stat - m, tampilkan semua log komit dengan indikasi jalur apa pun yang dipindahkan 

# REWRITE HISTORY
* Git rebase [branch], terapkan komitmen apa pun dari cabang saat ini di depan yang ditentukan
* Git reset –hard [commit], bersihkan area pementasan, tulis ulang pohon kerja dari komit yang ditentukan 

# TEMPORARY COMMITS
* Git stash, Simpan perubahan yang dimodifikasi dan bertahap
* Git stash list, daftar urutan tumpukan perubahan file yang disimpan 
* Git stash pop, tulis bekerja dari atas tumpukan simpanan
* Git stash drop, buang perubahan dari atas tumpukan simpanan  

Web Development Basic
DAY 2
HTML

* HTML (Hypertext markup language)
* Digunakan untuk menampilkan konten pada browser
* Contoh konten yang dapat ditampilkan seperti Text, Image, Video, Link, dan masih banyak lainnya.
* HTML bersifat statis. HTML hanya bertugas menampilkan konten yang diminta oleh developer.
* HTML bukanlah sebuah bahasa pemrograman, artinya HTML tidak bisa dinamis mengolah data.
* Ada 2 tools utama yang harus dipersiapkan untuk membuat HTML yaitu Browser dan Code Editor

# HTML STRUCTURE
* HTML tersusun sebagai kesatuan dari sebuah tingkatan (family tree relationship).
* Saat sebuah element berada di dalam element lain, maka disebut child element.
* Element yang berada diatas element lain disebut parent element.

# HTML ANATOMY
* Element
* Content
* Opening tag
* Closing tag
	
# HTML ELEMENT
* HTML element didefinisikan dengan opening tag, content, dan closing tag.

# HTML ATRIBUTE
Attribute adalah properties dari sebuah HTML Element.
Semua HTML Element memiliki attribute.

# HTML COMMENT
* Dengan menggunakan HTML Comment, kita dapat memberikan penjelasan maksud dari line code yang kita kerjakan.
* Comment tidak akan dieksekusi oleh sistem.
* Comment hanya untuk dibaca oleh sesama programmer.

* Menggunkan extention “live server” agar html auto reload
* Tidak semua HTML Element memiliki content. Seperti element <br>. Element ini disebut empty element. Empty element tidak memiliki closing tag.
* src atau source adalah  attribute untuk memberitahukan sumber gambar, bisa melalui file lokal ataupun dari internet
* Alt adalah alternative, Jika gambar tidak berhasil dimunculkan kita bisa memberi tahu ke user di tag img kita menampilkan gambar apa
* Video merupakan double closing tag sehingga kita menaruh konten di antara opening dan closing
* controls berguna untuk kita bisa mengatur videonya di play / pause dan indikator menit
* Table adalah salah satu elemen yang akan sering kita temukan dan gunakan. Contohnya data pada admin, invoice, data user, stock prices, dan masih banyak lagi.
* HTML tugasnya hanya membuat dan menampilkan konten saja ya.
* Semantic artinya kita menggunakan element html yang sesuai dengan kebutuhan konten. Jadi daripada kita menuliskan <div class=”header”> Kita menuliskan <header> Ini * * sangat membantu untuk developer supaya lebih “Easy to read and understand”
* Kegunaan semantic HTML, Meningkatkan Accessibility, Meningkatkan SEO, Lebih mudah di maintain.
* DEPLOY HTML, Deploy adalah sebuah proses untuk menyebarkan aplikasi yang sudah kita kerjakan supaya bisa digunakan oleh orang-orang
* Jika aplikasi kita HTML atau Web App kita perlu mendeploy ke server.
* Sedangkan jika aplikasi kita mobile seperti Android Atau IOS kita bisa deploy ke Google Play Store atau App Store


Web Development Basic
DAY 3
CSS
* CSS adalah bahasa yang digunakan untuk mendesain halaman website.
* Dengan CSS, kita bisa mengubah warna, menggunakan font custom, editing text format, mengatur tata letak, dan lainnya.
* Ada 3 cara menggunakan CSS
	* Inline CSS, Inline styles adalah kita menambahkan CSS pada attribute element HTML
	* .CSS Files, Jika kita membutuhkan banyak code pada CSS, direkomendasikan untuk memisahkan code CSS di file tersendiri (extension .css) dan terpisah dari file HTML.
	* Access file .css in HTML Tidak ada aturan baku untuk penempatan path file .css. Namun harus dalam 1 folder project yang sama.
* CSS - Tag Name
	* Menggunakan tag Elemen HTML secara langsung pada CSS.
	* Jika menggunakan Tag Element, maka ini bersifat global. Global artinya akan mempengaruhi seluruh Tag Elemen HTML yang ada pada file tersebut
* CSS - Class Name
	* menggunakan attribute class pada elemen HTML lalu memanggil nama class tersebut pada CSS
	* HTML yang memiliki class yang sama, akan mempunyai styling yang sama saat digunakan pada CSS.
	* Gunakan (.) saat memanggil class pada CSS
* CSS - Multiple Class
	* Kita dapat menggunakan lebih dari 1 class yang berbeda untuk 1 element HTML
	* Contoh Kasus: Kita memiliki 2 heading kemudian ingin memiliki warna yang sama. Tapi, kita ingin format heading yang satu huruf besar (uppercase) dan heading yang huruf kecil (lowercase).
* CSS - ID Name
	* ID Name bersifat unik artinya hanya ada 1 nama ID pada 1 element HTML.
	* Biasanya digunakan jika hanya ada 1 element pada 1 page. Contohnya navigation header dan footer.
	* Gunakan (#namaID) saat memanggil element ID HTML pada CSS
* Perbedaan Class Name dan ID Name
	* Gunakan ID Name jika hanya ada 1 elemen pada file/halaman HTML.
	* Gunakan Class Name jika akan ada beberapa element HTML yang memiliki styling/desain yang sama.
* Chaining Selectors
	* Chaining selector dapat kita gunakan pada case/kasus, Jika kita memiliki 3 tag elemen HTML pada CSS namun kita ingin ada 1 elemen HTML yang memiliki styling berbeda.
* Nested Element
	* Konsep CSS sama dengan HTML yaitu setiap element memiliki parent dan child.
* Important CSS
	* !important CSS berada di level paling atas dari ID dan Class. Maksudnya adalah jika pada styling CSS kita menggunakan !important, maka styling sebelumnya baik itu ID Name atau Class Name akan di override. 
* Multiple selector
	* Pada CSS kita bisa membuat code lebih efisien dan tidak repetitive (melakukan hal yang sama berulang-ulang).



Web Development Basic
DAY 4
ALGORITMA

* “urutan langkah logis tertentu untuk memecahkan suatu masalah” - Microsoft Press Computer and Internet Dictionary (1998)
* proses tersebut dilakukan dengan cara yg logis (masuk akal) dan sistematis (terurut)
* Belajar algoritma sama aja dengan mengingat kembali alur berfikir yg terstruktur.
* Algoritma merupakan pemeran utamanya
* Ciri ciri algoritma
	* Input, memiliki 0 atau lebih inputan
	* Output, memiliki minimal 1 buah output
	* Definitiness (pasti), intruksi jelas tidak ambigu
	* Finiteness (ada batas), memiliki titik untuk berheti atau stop
	* Efectiviness (tepat atau efesien), sebisaa mungkin tepat sasaran dan efisien
* Algoritma memiliki berbagai jenis proses
	* Sequence, interuksi yang dijalankan secara berurutan
	* Selection, interuksi yang dijalankan jika memehuhi suatu kondisi
	* Iteration, interuksi yang berulang kali dijalankan selama memnuhi suatu kondisi
	* Concurrent, interuksi yang dijalankan secara bersamaan
* 	Pernyajian algoritma
	* Deskriptif, Penulisan algoritma dengan cara deskriptif seperti kita menulis tutorial (tata cara) dengan bahasa sehari-hari,
	* Flowchart, penyajian algoritmanya lebih mudah dibaca karena memiliki tampilan visual. Flow chart menggunakan simbol bangun datar sebagai representasi dari * * proses yg dilakukan.
	* Pseudocode, Penulisan algoritma yg hampir menyerupai penulisan pada kode pemrograman disebut dengan pseudo code.
	* Pada umumnya pseudocode memiliki 3 bagian:
		* Judul : Penjelasan dari algoritma yg dibuat
		* Deklarasi : Mendefinisikan/menyiapkan semua nama (variabel) yg akan digunakan
		* Deskripsi : langkah-langkah penyelesaian masalah

JAVASCRIPT
* Javascript adalah bahasa pemograman yang sangat powerful yang digunakan untuk logic pada sebuah website
* Javascript juga dapat membuat website menjadi interaktif dan dinamis
* Syntax bisa dianalogikan seperti kosa kata (vocabulary) dan tata cara (grammar) pada bahasa pemograman.
* Kita menggunakan syntax tertentu untuk membuat statement program, instruksi untuk djalankan/dieksekusi oleh web browser, compiler, ataupun intrepreter
* Console log adalah tempat kita untuk cek logic pemograman web yang kita kembangkan
* Console log juga tempat kita untuk melakukan debugging (mengetahui error pada code) pada pemograman web
* Comments adalah sintaks yang digunakan untuk memberi keterangan tentang suatu statement. Menggunakan bahasa inggris atau bahasa indonesia.
* Tipe data adalah klasifikasi yang kita berikan untuk berbagai macam data yang digunakan dalam programming.
* Ada 6 tipe data fundamental pada Javascript yaitu 
	* number, tipe data yang mengandung semua angka termasuk angka desimal.
	* String, adalah grup karakter yang ada pada keyboard laptop/PC kita yaitu letters (huruf), number (angka), spaces (spasi), symbol, dan lainnya. Harus diawali dan diakhiri dengan single quotes ‘ … ‘ ataupun double quotes “ … “. 
	* boolean,  tipe data yang hanya mempunyai 2 buah nilai. 2 buah nilai tersebut adalah TRUE (benar) or FALSE (salah).
	* null, Tipe data null adalah tipe data yang diartikan bahwa sebuah variable/data tidak memiliki nilai. Null berbeda dengan string kosong. String kosong masih memiliki tipe data string
	* undefined,  tipe data yang merepresentasikan varibel/data yang tidak memiliki nilai.  Undifinied berbeda dengan null
		* Nilai dari pemanggilan variabel yang belum didefinisikan
		* Nilai dari pemanggilan element array yang tidak ada
		* Nilai dari pemanggilan property objek yang tidak ada
		* Nilai dari pemanggilan fungsi yang tidak mengembalikan nilai (return)
		* Nilai dari parameter fungsi yang tidak memiliki argumen
	* Object, Tipe data object adalah koleksi data yang saling berhubungan (related). Tipe data pbject dapat menyimpan data dengan tipe data apapun (number, string, boolean, dan lainnya). Tipe data object mempunyai key dan value.
* variable adalah container/tempat untuk menyimpan sebuah nilai
* 3 hal yang dapat dilakukan pada variabel
	* Membuat variabel dengan nama yang jelas dan menggambarkan tentang data tersebut
	* Menyimpan dan mengupdate informasi/data yang disimpan
	* Mendapatkan/menampilan data yang tersimpan
* 3 Cara mendefinisikan sebuah variabel
	* const , Gunakan const jika variabel tidak dapat diubah nilainya. Biasanya digunakan untuk menggambarkan konstanta sebuah nilai. Seperti konstanta pi = 3.14.
	* Let, mendukung kaidah global variabel dan local variabel. dianjurkan untuk menggunak let untuk variabel yang dinamis/dapat diubah.
* Aturan penamaan variabel
	* Harus mendeskripsikan tentang data yang disimpan
	* Tidak bisa menggunakan number pada awal nama variabel
	* Gunakan camelcase untuk penamaan yang lebih dari 1 kata.
* Operator
	* Assignment operator (=), digunakan untuk menyimpan sebuah nilai pada variabel
	* Increment dan Decrement, untuk menambah atau mengurangi sebesar 1 nilai.
	* Modulus adalah hasil dari sisa bagi.
	* Comparison operator adalah operator yang membandingkan satu nilai dengan nilai lainnya.Hasil operasi yang melibatkan comparison operator adalah antara true or false
		* Lebih kecil dari : <
		* Lebih besar dari: >
		* Lebih kecil atau sama dengan: <=
		* Lebih besar atau sama dengan: >=
		* Sama dengan: ===
		* Tidak sama dengan: !==
	* Logical operator biasa digunakan untuk sebuah CONDITIONAL pada pemograman. Menghasilkan nilai BOOLEAN yaitu TRUE or FALSE.
		* AND operator : &&
		* OR operator: ||
		* NOT operator: !
	* NOT (!), NOT akan membalikkan sebuah nilai BOOLEAN. TRUE menjadi FALSE dan sebaliknya.



Web Development Basic
DAY 5
JAVASCRIPT

* Conditional merupakan statement percabangan yang menggambarkan suatu kondisi.
* Conditional statement akan mengecek kondisi spesifik dan menjalankan perintah berdasarkan kondisi tersebut
* Yang dicek adalah apakah kondisi tersebut TRUE (benar). Jika TRUE maka code didalam kondisi tersebut dijalankan.
* Contoh conditional adalah if statement
```
If (true) {
console.log(‘This Message Will Print’)
};
Contoh
Let lapar = true;
If (lapar) {
Console.log (‘Yuk makan’);
};
```
Contoh conditional if…else statement
Else akan mengeksekusi sebuah statement/code jika suatu kondisi bernilai FALSE
```
Let lapar = false;
If (lapar) {
	console.log(‘Yuk makan’); // program tidak akan menampilkan statement
} else {
	console.log(‘tidak makan’); //program akan menampilkan statement ini
```
# IF ..ELSE IF Statement
Digunakan ketika memiliki berbagai kondisi
```
Let myVariabel = ‘hacktiv8’;
If (myVariable) {
	console.log(myVariable)
} else {
	console.log(‘variable tidak ada’)
}
```
# Truthy and Falsy Assignment
Analoginya adalah jika kita memiliki sebuah website dan meminta inputan username lalu menampilkannya. Jika usernamenya kosong kita bisa isi nilai tersebut.
```
Let defaultName username || ‘stranger’ ;
```
# Switch Case Conditional
Gunakan switch case jika kondisi dan percabangan terlalu banyak
# Ternary Operator
Untuk lebih produktif, programmer harus belajar syntax singkat dari suatu fitur
Ternary operator merupakan short-syntax dari statement if … else.
```
Let isNowSale = true;
isNowSale ? console.log(‘lets shopping now’) : console.log(‘shopping later’);
```
	
# JAVASCRIPT - LOOPING
Looping adalah statement yang mengulang sebuah instruksi hingga kondisi terpenuhi atau jika kondisi stop/berhenti tercapai.
Manual Looping
# For loop
FOR LOOP merupakan instruksi pengulangan yang dapat kita berikan pada program yang kita kembangkan.
Gunakan FOR LOOP jika kita tahu seberapa banyak nilai pasti untuk pengulangannya
For (initialization; condition; post-expression) {
		}
# For loop parameter
Inisialisasi: Sebagai inisialisasi awal dari mana mulainya sebuah pengulangan. Kita memberikan nilai awal/default pada parameter ini
Condition: For loop akan terus berjalan selama kondisi ini terpenuhi. Selama kondisi bernilai TRUE.
Post-expression (Increment/Decrement): Iterasi statement yang digunakan untuk mengupdate variabel yang menjadi kontrol pada pengulangan
```
Let angka = 1;
For (angka; angka <= 10; angka++)  {
	console.log(angka);
}
```
# WHILE LOOP
WHILE LOOP akan menjalankan instruksi pengulangan kondisi bernilai TRUE.
Gunakan WHILE LOOP jika kita tidak mengetahui jumlah pasti pengulangan.
CONTOH:
Jika kita ingin menampilkan list user yang sudah melakukan registrasi. Kita tidak mungkin tahu nilai pasti berapa banyak pengulangan data yang akan tampil. Maka gunakan WHILE.

# DO WHILE
Terkadang kita ingin setidaknya menjalankan pengulangan 1 kali sebelum dilakukan pengecekan kondisi

# NESTED LOOP
Jika kita membuat looping didalam looping. Maka ini dinamakan Nested Loop. Looping pertama dianalogikan sebagai baris. Looping kedua dianalogikan sebagai kolom. 
