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
    <li>selector kelas semu(memilih elemen berdasarkan status tertentu)</li>
    <h6>apa itu pseudo clas</h6>
    <p>class semu yang digunakan untuk mendefinsikan keadaan khusus dari suatu elemen
    <p>misalnya dapat digunakan untuk </p>
    <ul>
        <li>gaya elemen saat pengguna mengarahkan mouse keatasnya 
        <li>gaya tautan yang dikunjungi dan belum dikunjungi secara berbeda</li>
        <li>gaya elemen saat mendapat fokus</p>
    </ul>
    <li>selector elemen semu(memilih dan menata bagian elemen)</li>
    <li>selector attribute (memilih elemen berdasarkan attribut atau nilai attribut</li>
</ul>