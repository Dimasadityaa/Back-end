# elemen heading

    <h1>heading 1</h1>
    <h2>heading 2</h2>
    <h3>heading 3</h3>
    <h4>heading 4</h4>
    <h5>heading 5</h5>
    <h6>heading 6</h6>

# elemen paragraf

    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Beatae, hic.</p>

# link html

    <a href="">this is a link</a>

# gambar html

    <img src="picture.png" alt="alternatif">

    ## map img
    <img src="workspace.jpg" alt="Workplace" usemap="#workmap">

    <map name="workmap">
        <area shape="rect" coords="1,1,1,1" alt="alt" href="example.htm">
    </map>

    shape
        - rect mendifinisikan daerah persegi panjang
        - circle mendefinsikan daerah melingkar
        - poly mendefiniskan wilayah poliginal
        - default mendefinisikan seluruh wilayah

        coords="berisi angka" berfunsgi sebagai penempatan area yang dapat diklik digambar

        ringkasan
        -gunakan <map> elemen HTML untuk mendefinisikan peta gambar
        -gunakan <area> elemen HTML untuk menentukan area yang dapat di klik di peta gambar
        -gunakan usemap attribute HTML dari <img> elemen untuk menunjuk ke peta gambar
        -gunakan background-repeat properti no-repeat untuk menghindari gambar berulang
        -gunakan background-size properti cover untuk menutupi seluruh elemen dengan gambar latar belakang

        <picture> elemen berisi satu atau lebih <source> elemen, masing-masing mengacu pada gambar yang berbeda melalui scrset attribute, dengan cara ini browser dapat memilih gambar yang paling sesuai dengan tampilan dan/atau perangkat saat ini, setiap <source> elemen memiliki media attribute yang menentukan kapa gambar paling cocok

        contoh code
            <picture>
                <source media="(min-width: 650px)" scrset="gambar.png">
                <source media="(min-width: 450)" scrset="gambar.png">
            </picture>
# <br> 

    <br> tag yang mendefinisikan satu baris

    <br>

# elemen pemformatan HTML

    <b> teks tebal
    <strong> teks penting
    <i> teks miting
    <em> teks yang ditekankan
    <mark> teks yang ditanda
    <small> teks yang lebih kecik
    <del> teks yang dihapus
    <ins> teks yang disispkan
    <sub> teks subskrip
    <sup> teks superskrip

# elemen kutipan 

    fungsi <blockquote> elemen html mendefinisikan bagian yang dikutip dari sumber lain

    contoh:

    <blockquote cire="http://google.com>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Beatae, hic.</blockquote>


# elemen <q>

    fungsi <q> untuk kutipan singkat

    contoh:

    <q>ini kutipan</q>

# elemen <abbr> 

    fungsi <abbr> untuk singkatan

    contoh:

    <p>the <abbr title="world healt organization">who</abbr>was founded in 1948</p>

# elemen </addres>
    
    fungsi <addres> untuk informasi kontak

    contoh:

    <addres>
    ditulis oleh dimas.<br>
    visit id at:<br>
    example.con<br>
    ind
    </addres>

# elemen <cite>

    fungsi <cite> untuk judul karya

    contoh:

    <p><cite>the scream</cite> by x, painted in 1893</p>

# elemen <bdo>

    fungsi <bdo> untuk penggantian dua arah / untuk mengganti arah teks saat ini

    contoh:

    <bdo dir="rtl">This text will be written from right to left</bdo>

# komentar dihtml

    <!--- this a comment -->
    
# tabel

    contoh 

    sebuah tabel html sederhana:
        <table>
        <tr>
            <th>company</th>
            <th>contact</th>
            <th>country</th>
        </tr>
        <tr>
            <td>example</td>
            <td>example</td>
            <td>example</td>
        </tr>
        <tr>
            <td>example</td>
            <td>example</td>
            <td>example</td>
        </tr>
        </table>


    note:

    setiap sel tabel didefinisikan oleh <td>

    setiap baris tabel dimulai dengan <tr>

    jika anda ingin sel anda menjadi header maka gunakan <th>

    colspan attribut mewakili jumlah kolom yang akan direntang

    rowspan attribute membuat rentang cell pada beberapa baris

    colgroup elemen digunakan sebagai wadah untuk spesfikasi kolom

    contoh colgroup:

    <colgroup>
        <col span="3" style="background-color: #D6EEEE">
    </colgroup>


# list

    <ul> digunakan untuk membuat list tidak terurut
    
    <ol> digunakan untuk membuat list terurut

    note:

    list-style-type properti css digunakan untuk menentukan gaya penanda item daftar

    list-style-type disc menampilkan list bulat

    list-style-type circle menampilkan lingkaran

    list-style-type square meampilkan kotak

    list bersarang:

    contoh

    <ul>
        <li></li>
        <li>
            <ul>
                <li></li>
            </ul>
        </li>
    </ul>

    gunakan float: left; untuk menampilkan list horizontal

    type attribute dari <ol> tag, mendefinsikan jenis item list penanda

    type="1" list dengan angka 

    type="A" list dengan huruf besar

    type="a" list dengan huruf kecil

    type="I" list dengan angka romawi huruf besar

    type="i" list dengan angka romawi huruf kecil


    start attribute untuk menentukan nomor yang akan dimulai

    gunakan <dl> elemen HTML untuk menentukan daftar deksripsi

    gunakan <dt> elemen HTML untuk mendefinisikan istilah deskripsi 
    
    gunakan <dd> elemen HTML untuk mendeskripsikan istilah daftar deskripsi


# block dan inline


    block:

    elemen level block dimulai pada baris baru

    elemen level blok selalu menggunakan lebar penuh yang tersedia (membentang ke kiri dan kanan sejauh mungkin)

    elemen level block memiliki margin atas dan bawah, sedangkan elemen inline tidak

    elemen elemen level block:

    <address><article><aside><blockquote><canvas><dd><div><dl><dt><fieldset><figcaption><figure><footer><form><h1>-<h6><header><hr><li><main><nav><noscript><ol><p><pre><section><table><tfoot><ul><video>


    inline:

    elemen sebaris tidak dimulai pada baris baru

    elemen sebaris hanya membutuhkan lebar sebanyak yang diperlukan

    elemen elemen level inline:

    <a><abbr><acronym><b><bdo><big><br><button><cite><code><dfn><em><i><img><input><kbd><label><map><object><output><q><samp><script><select><small><span><strong><sub><sup><textarea><time><tt><var>

    
# div

    <div> elemen sering digunakan sebagai wadah untuk elemen HTML lainya.

    <div> elemen tidak ada yang diperlukan attribut, tetapi style, class dan id yang umum

# span

    <span> elemen merupakan sebuah wadah inline digunakan untuk menandai sebuah bagian dari teks, atau bagian dari dokumen

    <span> elemen tidak ada yang perlukan attribut, tetapi style, class dan id yang umum

# class

    class attribut HTML digunakan untuk menentukan kelas untuk elemen HTML

    beberapa eleme HTML dapat berbagi kelas yang sama

    Ringkasan Bab
        classAtribut HTML menentukan satu atau lebih nama kelas untuk sebuah elemen
        Kelas digunakan oleh CSS dan JavaScript untuk memilih dan mengakses elemen tertentu
        The classatribut dapat digunakan pada setiap elemen HTML
        Nama kelas peka huruf besar-kecil
        Elemen HTML yang berbeda dapat menunjuk ke nama kelas yang sama
        JavaScript dapat mengakses elemen dengan nama kelas tertentu dengan getElementsByClassName() metode

