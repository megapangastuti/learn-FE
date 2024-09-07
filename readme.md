1. index.html adalah file utama yang akan kita masukkan ketika kita running program
 - file utama yang akan kita jalankan ketika kita nyalain website kita
2. halaman utama ketika kita membuka website disebut index
3. shortcut untuk membuat sebuah file html baru : "html:5" lalu tekan enter
4. <> => disebut tag
5. <html> </html> => satu webpage
6. <body> </body> => apapun yg kita lihat
7. <head> </head> => apapun yg kita g lihat => informasi tambahan tentang webpage yang kita punya
8. extensions => aplikasi tambahan untuk proses developing
9. extensions yg dibutuhin :
   - live server => untuk membantu kita melihat perubahan pada webpage yang kita miliki secara real time
   - prettier
10. setiap tag memiliki purpose dan sifatnya masing masing
11. <h1>Hello World</h1>
    => disebut sebuah element => berisi tag dan contentnya
    => <h1></h1> disebut tag
    => "Hellow world" disebut content
    => <h1> disebut tag pembuka
    => </h1> disebut tag penutup
12. <input type="text"> => disebut sebagai self closing tag
    => nggak butuh pembuka dan penutup
    => bersifat mandiri
    => type="text"
       => type disebut sebagai attribute
          => deskripsi tambahan bahwa sifat tag html ini harus seperti apa
          => cara penulisan ada ditengah2 tag html
          => attribute tidak memiliki urutan, jadi boleh dibolak balik
          => nggak semua attribute bervalue
          => contoh attribute yang nggak bervalue => disabled => buat matiin suatu button
       => "text" disebut valuenya
          => tipe data inputan berupa text
          => kalo type ="number" brarti cuma inputan angka yg bisa diterima
    => placeholder="input your name"
       => attribute untuk menulis text yang akan tampil didalam suatu field untuk menangkap inputan
13. <style></style>
    => bisa masuk ke body atau head
    => personal preference taro di body aja
    => mirip dengan tag script dalam html => make js di html
    => style untuk menulis css di dalam html
14. css ada anatominya tapi lebih simpel dari html
15. terdapat lebih dari 1 css file itu boleh
16. biasanya file css akan dipisahkan tergantung kebutuhannya, terkadang dipisahkan berdasarkan page, button, dll
17. Tag selector => kita select sebuah element html berdasarkan tag
18. class selector
19. class="text-blue font-sans" => bisa manggil lebih dari 1 class, caranya tinggal dipisah dengan spasi
20. Selector Specificity => power level dari masing2 css
   => setiap rule set memiliki power levelnya
   => bagi yang punya specificity lebih besar, dia akan meng overwrite peraturan dibawahnya
21. membuat sebuah class name tidak boleh pake spasi, bisa pake dash atau underscores, umumnya pake dash
22. class selector lebih fleksibel dibanding tag selector
23. id selector => paling kuat power levelnya
24. inline style => nulis css dalam tag html 
    => jarang ditemui
    => agak ribet maintain nya
    => bisa dilakukan lebih dari satu jenis styling
    => power levelnya lebih tinggi dari tag selector
    => power levelnya lebih tinggi dari class selector
    => power levelnya lebih tinggi dari id selector
    => berarti power levelnya paling tinggi dibanding ketiganya
    => yang jauh akan kalah dengan yang dekat
25. Pseudo Class => 
    => ketika kita punya suatu webpage/website terkadang kita ingin memiliki styling yang berbeda beda ketika kita ingin melakukan interaksi ke sebuah elemen html
    => contoh : ada dua button, yang satu BG orange tulisan putih, yang satu BG putih tulisan orange => misal kita hover ke button itu, tulisannya berubah jadi hitam
    => jadi pseudo class adalah suatu styling yang kita apply pada suatu element ketika kita melakukan interaksi tertentu
    => misal ketika kita hover, atau klik, dll
26. Flex => adalah suatu teknik untuk layouting
    => contoh : misalkan ada lebih dari 1 button, flex ini digunakan untuk mengatur jarak diantara button yg ada. bahkan cara bagaimana dia berjejer, flex box yg atur
27. Flexbox bukan satu2nya cara untuk layouting, tetapi ini adalah cara yg paling umum
28. Guna flexbox hanya untuk layouting aja, hanya untuk meletakkan suatu elemen didalam suatu webpage, cara berjajarnya gimana, sebanyak apa, dll



note :
1. chapter 2 HTML CSS theo bilang ada link yg terlampir, tapi g ada link terlampir di lms nya