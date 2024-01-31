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
8. BE dan FE sepakat kalau bentukannya angka ya angka, kalau string ya string. 
9. Nomor telepon bentukannya string.
10. Preview PDF/EXCEL/DOCS
   - [x] FE
   - [ ] BE
11. Export (PDF / Excel)
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
14. FE hanya menerima message berdasarkan BE saja, sisanya dihandle sesuai experience ui-nya. 
15. Pastikan BE jika memang error, kembalikan response code juga error / bad request 400 >, 
16. Jika request yang memerlukan data, namun response mengembalikan error, kembalikan datanya dalam bentuk array kosong / object kosong
17. Handle data kosong tampilannya dihandle oleh:
   - [x] FE
   - [ ] BE
18. 
