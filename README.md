Indra Riksa Herlambang - 1154051

XML Schema Definiton (XSD) digunakan untuk menjelaskan atau mendefinisikan struktur dari dokumen xml dengan batasan-batasan yang lebih kompleks pada elemen dan atribut, untuk lebih singkatnya XSD digunakan untuk memverifikasi struktur dari dokumen xml.

Langakah untuk membuat file xml dan schema xsd :
1. File xml dapat diintegrasikan dengan berbagai project, untuk keperluan praktikum ini kita akan membuat project tidak utuh, hanya     membuat file xml dan xsd dengan tools dan plugin eclipse, kemudian memeriksa apakah dokumen tersebut valid, well form.
2. Klik file -> new -> project -> plug-in project
3. Beri nama: tugasbab4_1154051, lalu klik next -> finish
4. Pada package yang telah dibuat klik kanan pilih new -> other-> XML file -> beri nama murid.XML -> finish
5. Setelah file XML terbuat, selanjutnya mengisi data pada file xml tersebut
6. Setelah selesai, klik kanan pada murid.xml, lalu pilih Create XML Definition. Beri nama datamurid.xsd -> finish
7. Lalu selanjutnya membuat reference file xsd pada file xml, Klik kanan pada datamurid.xsd lalu pilih generate -> XMLfile-> beri nama datamurid.xml -> next -> finish. Lalu link referensi tersebut di copy ke murid.xml
8. Setelah itu membuat patterns agar value dari atribut "aktif" isinya ya atau tidak, dan email dengan menggunakan ketentuan @indrarh.com
9. Klik datamurid.xsd -> pada struktur klik murid -> klik aktif -> klik kanan pada mouse -> show properties -> pada constraint tambahkan pattern "ya|tidak"
10. Selanjutnya pada struktur klik email -> klik kanan pada mouse -> show properties -> pada constraint tambahkan pattern ".+@indrarh.com"
11. Selanjutnya tinggal di validasi, jika sudah benar maka tidak akan muncul error.
