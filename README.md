# DATABASE
Table yg harus dibuat: Plural/jamak
Silahkan jika mau ditambahkan foreign key syntax di create table dst
Tapi kita tidak akan concern dibagian itu.
but lebih kepada fungsionalities and UI.

1. Products (data barang)

  id autoincrement integer
  
  code varchar
  
  name varchar
  
  price integer
  
  stock integer
  
  created_at datetime (untuk menyimpan tgl ketika record dibuat)
  
  updated_at datetime (untuk diupdate dgn taggl record di update)
  


2. Users (untuk login):

 
  id autoincrement integer
  
  username varchar
  
  password varchar
  
  full_name  varchar
  
  phone varchar
  
  created_at datetime
  
  updated_at datetime



3. Orders (master transaksi)

 
  id autoincrement integer
  
  total  integer
  
  created_at datetime
  
  updated_at datetime



4. Transactions (detail transaksi):

 
  id autoincrement integer
  
  order_id integer
  
  product_id integer
  
  price integer
  
  quantity integer
  
  sub_total integer


>> execute: posuas.sql

# TODO
1. phpmyadmin -> mysql (database), apache (webserver), php (lang) atau sejenisnya agar mempermudah generate /create table dst atau bisa juga via netbeans
2. java jdk
3. netbeans
cara install google: how to install phpmyadmin step by step, etc.

# WORK
1. buat database dan table2nya dulu via apapun blh, mau pma, atau workbench, etc
2. buat GUInya (menu, main form, dan internal form)
3. mulai koding
   1. buat kelas dan method koneksi
   2. buat method untuk exekusi query mysql
   3. buat action performed dgn klik pada object2 GUI
4. yg sudah selesai minta dinilai kapanpun dan selanjutnya tidak usah masuk kelas is OK.


# CLASSES for you :)
class2 berikut ini untuk referensi membantu anda untuk:

1. mengetahui waktu sekarang yg akan dipake di created_at dan atau updated_at
2. melakukan koneksi ke database
3. mengexecute query SQL(create, update, delete, select)

>> open: risTime.java, 
Utility class untuk mendapatkan waktu sekarang:


Further reference ??? Search on youtube/google to explore more !


//////////////////////////////////////////////
See: source-references.zip
password: JombloDevelopmentKit.java
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

Selamat belajar. ^_^

arissan <arissetyawan.email@gmail.com>
