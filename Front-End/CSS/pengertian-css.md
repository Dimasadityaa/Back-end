<h1>apa itu CSS?</h1>

<ul>
    <li>CSS adalah singkatan dari Cascading Style Sheets</li>
    <li>CSS menjelaskan bagaimana elemen HTML ditampilkan dilayar, kertas, atau media lain</li>
    <li>CSS menghemat banyak pekerjaan, itu dapat mengontrol tata letak beberapa halaman web sekaligus</li>
    <li>Stylesheet eksternal disimpan dalam file css</li>
</ul>

<h2>sintaks css</h2>
<p>
<mark>
h1 {color: blue; font-size: 12px;}
</mark>
</p>

<h2>css selector</h2>
 <ul>
    <li>selector sederhana (pilih elemen berdasarkan nama, id, class)</li>
    <hr>
    <li>
        selector kombinator (memilih elemen berdasarkan hubungan spesifik diantara mereka)
        <p>ada empat kombinator </p>
        <ul>
            <li>descendant selector (space)</li>
            <li>child selector (>)</li>
            <li>adjacent sibling selector (+)</li>
            <li>general sibling selector (~)</li>
        </ul>
        <p>1. descendant selector (space)</p>
        <p>contoh code:</p>
        <p>div p { background-color: yellow;}</p>
        <br>
        <p>2. child selector (>)</p>
        <p>contoh code:</p>
        <p>div > p {nbackground: yellow; }</p>
        <br>
        <p>3. adjacent sibling selector (+)</p>
        <p>contoh code</p>
        <p>div + p { background: yellow; } </p>
        <br>
        <p>general sibling selector (~)</p>
        <p>contoh code:</p>
        <p>div ~ p { font-size: 12px; }</p>
    </li>
    <hr>
    <li>
        selector kelas semu(memilih elemen berdasarkan status tertentu)
        <p>kelas semu digunakan untuk mendefinisikan keadaan khusus dari suatu eleme</p>
        <p>misalnya dapat digunakan untuk</p>
        <ul>
            <li>gaya elemen saat pengguna mengarahkan mouse ke atasnya</li>
            <li>gaya tautan yang dikunjungi dan yang belum dikunjungi secara berbeda</li>
            <li>gaya elemen saat mendapat fokus</li>
        </ul>
        </li>
    <hr>
    <li>
        selector elemen semu(memilih dan menata bagian elemen)
    <p>elemen semu CSS digunakan untuk menata bagian tertentu dari suatu elemen</p>
    <p>misalnya, dapat digunakan untuk</p>
    <ul>
        <li>gaya huruf pertama, atau baris, dari suatu elemen</p>
        <li>sisipkan konten sebelum, atau setelah, konten elemen</p>
    </ul>
    <p> contoh code:</p>
    <p>
    selector::pseudo-elemen {
        properti: value;
    }
    <p>gunakan ::first-line untuk menambah gaya khusus untuk baris pertama</p>
    <p>gunakan ::first-line untuk menambah gaya khusus untuk baris pertama</p>
    <p>gunakan ::before untuk memasukan beberapa konten sebelum konten dari elemen</p>
    <p>gunakan ::after untuk memasukan beberapa konten setekah isi elemen</p>
    <p>gunakan ::marker untuk memilih penanda daftar item</p>
    
</p>
    </li>
    <hr>
    <li>
        selector attribute (memilih elemen berdasarkan attribut atau nilai attribut
         <h3>CSS selector attribut</h3>
    <p>[atribut] selector digunakan untuk elemen dengan atribut tertentu</p>
    <p>contoh</p>
    <p>a [target] {
        background: yellow;
    }
    </p>
    <br>
    <p>CSS attribut="value" selector</p>
    <p>CSS attribut="value" selector digunakan untuk memilih elemen dengan atribut dan nilai tertentu</p>
    <p>contoh berikut memilih semua<a> elemen dengan atribut target="_blank"</p>
    <p>a [target="blank"] {
        background: yellow;
    }
    </p>
    <br>
    <p>CSS [atribut~="nilai"] selector<p>
    <p>CSS [atribut~="nilai"] selector digunakan untuk memilih elemen dengan nilai atribut yang mengandung kata tertentu</p>
    <p>contoh berikut memilih semua elemen dengan atribut judul yang berisi daftar kata yang dipisahkan spasi, salah satunya adalah bunga </p>
<p>[title~="bunga"] {
    border: 5px solid black;
}
</p>
<br>
    <p>CSS [atribut|="nilai"] selector</p>
    <p>CSS [atribut|="nilai"] selector digunakan untuk memilih elemen dengan atribut yang ditentukan dimulai dengan nilai tertentu</p>
    <p>contoh berikut memilih semua elemen dengan nilai atribut kelas yang dimulai dengan "top":</p>
    <p>catatan: nilai harus berupa kata utuh, baik sendiri, seperti class="top", atau diikuti oleh tanda hubung(-), seperti class="top-text"!
    <p>contoh</p>
    <p>[class|="top"] {
        background: yellow;
    }
    </li>
   
</ul>
