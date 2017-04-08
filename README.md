Indra Riksa Herlambang - 1154051

XML Schema Definiton (XSD) digunakan untuk menjelaskan atau mendefinisikan struktur dari dokumen xml dengan batasan-batasan yang lebih kompleks pada elemen dan atribut, untuk lebih singkatnya XSD digunakan untuk memverifikasi struktur dari dokumen xml.

File xml dapat diintegrasikan dengan berbagai project, disini kita akan membuat file xml dan xsd dengan tools dan plugin eclipse, kemudian memeriksa apakah dokumen tersebut valid dan well form.

Langkah untuk membuat file xml dan schema xsd :
1. Klik file -> new -> project -> plug-in project
2. Beri nama: tugasbab4_1154051, lalu klik next -> finish
3. Pada package yang telah dibuat klik kanan pilih new -> other-> XML file -> beri nama murid.xml -> finish
4. Setelah file XML terbuat, selanjutnya mengisi data pada file xml tersebut
5. Setelah selesai, klik kanan pada murid.xml, lalu pilih Create XML Definition. Beri nama datamurid.xsd -> finish
6. Lalu selanjutnya membuat reference file xsd pada file xml, Klik kanan pada datamurid.xsd lalu pilih generate -> XMLfile-> beri nama datamurid.xml -> next -> finish. Lalu link referensi tersebut di copy ke murid.xml
7. Setelah itu membuat patterns agar value dari atribut "aktif" isinya ya atau tidak, dan email dengan menggunakan ketentuan @indrarh.com
8. Klik datamurid.xsd -> pada struktur klik murid -> klik aktif -> klik kanan pada mouse -> show properties -> pada constraint tambahkan pattern
9. Selanjutnya pada struktur klik email -> klik kanan pada mouse -> show properties -> pada constraint tambahkan pattern
10. Selanjutnya tinggal di validasi, jika sudah benar maka tidak akan muncul error.
