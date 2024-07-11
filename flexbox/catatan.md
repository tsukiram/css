parent dan child
 - contoh :
    <div class="container"> 
        <div class="satu">1</div>
        <div class="dua">2</div>
        <div class="tiga">3</div>
        <div class="empat">4</div>
    </div>
    ------------------------
    .container{
        ini akan mengatur elemen parent container
    }

    .container div {
        ini akan mengatur element child dalam container yang bertipe div (satu, dua, tiga, empat)
    } // melihat tipe div yang berada dalam class container sebagai parent
 - mengambil spesifik child berdasarkan indeks child dalam parent
   contoh : 
   .parent span:nth-child(2){...}
   penjelasan : menunjuk ke cild pertama di dalam parent yang bertipe span dengan indeks ke-2 atau urutan ke 2 dari atas

Input and Actions
 - melakukan sesuatu ketika input di masukkan
   contoh : melakukan sesuatu ketika input checklist di check
   .parent input:checked ~ span:nth-child(2){
    background-color : #red
    }
   penjelasan : ketika tipe input yang merupakan child dari parent di checklist (input:checked) maka pada saudara kandung atau child dari parent juga (~) yang bertipe span yang merupakan anak ke 2 dari parent diganti background colornya menjadi merah (background-clor : #red)


Possition 
 - right: 0 ; > untuk membuat elemen pindah ke paling kanan dari screen

Body 
body{
    overflow-x: hidden ; > membuat elemen yang tumbah di sembunyik dari body, misalnya menyembunyikan navbar
}
animation
 - transform : rotate(x, y)
 - transition : (time)


