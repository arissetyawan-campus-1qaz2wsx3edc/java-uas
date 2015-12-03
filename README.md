# DATABASE
Table yg harus dibuat: Plural/jamak
-----------------------------
1) Products (data barang)
id autoincrement integer
code varchar
name
price integer
stock
created_at (untuk menyimpan tgl ketika record ini dibuat)
updated_at (untuk diupdate dgn taggl record di update)
-----------------------------
2) Users (untuk login):
id
username (untuk login)
password (untuk password) 
full_name
phone
created_at
updated_at
-----------------------------
3) Orders (master transaksi)
id
total
created_at
updated_at
-----------------------------
4) Transactions (detail transaksi):
order_id
id
product_id
price
quantity
sub_total
-----------------------------
>> posuas.sql

# UI MOCKUP/DESIGN:
>> sbg referensi untuk mockup: mockup.zip

# FLOW
>> flow.zip

# TODO
1. phpmyadmin -> mysql (database), apache (webserver), php (lang) atau sejenisnya agar mempermudah generate /create table dst
2. java
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


# classes for you :)
class2 berikut ini untuk membantu anda untuk:

1) mengetahui waktu sekarang yg akan dipake di created_at dan atau updated_at
2) melakukan koneksi ke database
3) mengexecute query SQL
>> classes.zip


Selamat belajar. ^_^

arissan


