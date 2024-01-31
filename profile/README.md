## Eproc Collaboration Charter

### Front End - Back End

1. check nullabity serta undefined itu tanggung jawab keduanya.
2. menampilkan list item, jika bentuknya detail (hanya satu object):
   - [ ] tampilkan berupa object
   - [x] tampilkan berupa list/array/slice
3. common response API Call pastikan seragamkan, di BE memastikan strukturnya sama, di FE bisa dibuatkan global wrapper-nya
4. Parameter dan Request Body, field2nya menggunakan snake_case
5. Naming convention: untuk format datetime / tanggal, pake:
   - [ ] pake prefix
   - [x] pake suffix contoh birth_date, agreement_date
6. format datetime dipastikan 1 tipe saja di BE
7. Untuk format datetime, di tampilan, itu dihandle di BE / FE
   - [x] FE
   - [ ] BE
8. Naming convention: ?
9. Preview PDF/EXCEL/DOCS
   - [x] FE
   - [ ] BE
10. Export (PDF / Excel)
   - [ ] FE
   - [x] BE
11. Upload docs
   - [ ] FE
   - [x] BE
12. Download docs
   - [ ] FE
   - [x] BE
13. Error handling: konteks (bikin request ke BE dan mengembalikan error) bgaimana response ui-nya
   - [ ] FE
   - [x] BE
14. Misal jika mengembalikan object, jika tidak ditemukan kembalikan null saja tanpa perlu response error / bad request  
