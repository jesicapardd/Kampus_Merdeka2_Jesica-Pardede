*database merupakan alat untuk melakukan pengelolaan data dari suatu produk

*relationship di database: one to one (satu payment method memiliki satu deskripsi), one to many (satu user bisa memiliki banyak transaksi), many to many (banyak transaksi bisa memiliki banyak produk)

*relational database management system (RDBMS) merupakan software yang menggunakan relational database model sebagai dasarnya (contoh: mysql, postgresql, ms sql server, dsb)

*sql merupakan bahasa untuk melakukan pengelolaan terhadap database relational

*jenis perintah sql ada data definition language (ddl), data manipulation language (dml), dan data control language (dcl)

*ddl biasanya digunakan untuk mengelola db dan tabel (contoh: create table, drop table)

tipe data di mysql ada num (float, int, bigint, dsb), alphanumeric (varchar, text, longtext, dsb), dan date (timestamp)
*dml biasanya digunakan untuk mengelola data di dalam suatu tabel

*statement select digunakan untuk menampilkan data (select * from users)

*statement insert digunakan untuk menyisipkan data (INSERT INTO Customers (CustomerName, City, Country) VALUES ('Cardinal', 'Stavanger', 'Norway'))

*statement update digunakan untuk melakukan perubahan data (UPDATE Customers SET ContactName = 'Alfred Schmidt', City= 'Frankfurt' WHERE CustomerID = 1)

*statement delete digunakan untuk menghapus data (DELETE FROM Customers WHERE CustomerName='Alfreds Futterkiste')

*ketika menampilkan data kita bisa menambahkan kriteria khusus dengan menggunakan statement like (mengandung), between (diantara), and (dan), or (atau), orderby (pengurutan), limit (batas banyak data) (select * users where name like %john%)

*kita bisa mengombinasikan data dari sejumlah tabel menggunakan statement join

*union operator digunakan untuk mengombinasikan hasil dari sejumlah statement select

*agregasi digunakan untuk mengambil nilai beberapa baris dikelompokkan bersama untuk membentuk nilai ringkasan tunggal (min, max, sum, avg, count, having)

*subquery digunakan untuk mengembalikan data yang akan digunakan dalam query utama sebagai syarat untuk lebih membatasi data yang akan diambil
