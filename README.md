264311038


| No | Elemen ERD                        | Aturan Transformasi                                                       |
|----|-----------------------------------|---------------------------------------------------------------------------|
| 1  | Entitas kuat                      | Menjadi satu relasi (tabel), atribut kunci menjadi Primary Key            |
| 2  | Atribut biasa                     | Menjadi kolom pada relasi                                                 |      
| 3  | Atribut turunan (SUBTOTAL, TOTAL) | Tidak disimpan sebagai kolom biasa, dihitung dari atribut lain            |
| 4  | Relasi 1:N                        | Primary Key sisi "1" menjadi Foreign Key di sisi "N"                      |
| 5  | Relasi M:N                        | Menjadi relasi baru, PK gabungan dari kedua FK, atribut relasi ikut masuk |

