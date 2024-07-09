felxbox adala tool untuk mengatur posisi sebuah box dalam 1 dimensi dan secara dinamis
istilah :
 - conteiner:  sebuah bingkai atau box besar yang akan menyimpan item-item, contoainer juga bisa disebut pembungkus atau parent
 - item :  box yang ada dalam container, juga bisa disebut childs dari contaner
 - main axis : pengaturan yang kita set untuk mengurutkan elemen-elemen atau item-item secara horizintal atau dari kiri ke kanan (sumbu utama)
 - cross axis : pengaturan yang akita set untuk mengurutkan elem elemen secar vertikal atau dari atas ke bawah (sumbu yang berlawanan dari sumbu utama )
 - main size : ukuran panjang dari container
 - cross size : ukuruan lebar dari container
 - main start : menentukan awal dari elemen
 - main end : menentukan akhir dari elemen
 - cross start and cross end


properti yang kita definisikan pada container:
 - display : flex;  > membuat sebuah elemen parent menjadi sebuah flex box dan membuat elemen child di dalamnya berprilaku flex
 - flex-direction : row | reverse-row | collum | reverse-collum > mendefinisikan kearah mana uturan elemen di dalam sebuah container, untuk default adalah row atau dari kiri ke kanan
 - flex-wrap : nowrap(default) | warp | warp-reverse > untuk mastikan item dalam suatu contaner akan ke kolom atau baris setelahnya jika tidak tidak muat di baris itu ( jika tidak menggunakan wrap, maka dia akan memaksa item untuk masuk ke container, akibatnya ukuran dari item akan di korbankan )
 - justify-content: flex-start(rata kiri) | flex-end (rata kanan) | center (rata tengah) | space-between (elemen awal dan akhir di ujung, elemen tengah diatur sama untuk sisinya)| space-around | space-evenly > mengatur kesejajaran secara horzontal
 - align-items: flex-start | flex-end | center | stretch (menstratching item secara vertikal) | baseline (mensejajarkan item berdasarkan tulsisan atau isi di dalamnya bukan boxnya seperti center) > artibut ini mengatur kesejajaran secar vertikal
- align-content > untuk atribut ini semua parameternya sama seperti align-tem namun fungsinya adalah untuk mengatur item yang lebih dari satu baris dalam suatu kontainer


properti yang kita definisika pada item :
 - order : (num) > untuk mengatur urutan dari setiap item pada suatu baris, pada defaultnya order tiap item adalah 0(jika belum di definisikan), order akan urut dari kecil ke besar
 - flex-grow : (num) untuk mengakur ukuran secara dinamis (panjang baris)
 - align-self : (num) untuk mengatur posisi secara vertikal satu item saja 
 - box-sizing : border-box > tidak merubah ukuran box