# LAB1 Web

<table border="2" cellpading="10">
  <tr>
    <td><b>Nama</b></td>
    <td>Ilham Nur Utomo</td>
  </tr>
  <tr>
    <td><b>NIM</b></td>
    <td>312010129</td>
  </tr>
  <tr>
    <td><b>Kelas</b></td>
    <td>TI.20.A1</td>
  </tr>
  <tr>
    <td><b>MataKuliah</b></td>
    <td>Pemrograman Web</td>
  </tr>
</table>

# <b>Praktikum</b>

## <b>Text editor dan browser</b>
- Berikut adalah tampilan text editor <i>(VScode)</i> dan browser <i>(Microsoft Edge)</i> yang saya gunakan.
![img1](image/0-vswelcome.PNG)
- Memasukan perintah dasar <b>HTML</b>.
![img2](image/0-1-%20tagd.PNG)

### <b>1. Membuat Paragraf</b>
![img3](image/0-1-1_a%2Bparagraph.PNG)
- center right
![img4](image/0-1-1-1_al%2Bcenter-right.PNG)
- justify left
![img5](image/0-1-1-2_al%2Bjustify-left.PNG)
- right center
![img6](image/0-1-1-3_al%2Bright-center.PNG)

### <b>2. Menambahkan Judul</b>
- <i>H1 dan H2, dengan menghapus tag align</i>
![img7](image/0-1-2_a%2Bheading.PNG)

### <b>3. Memformat Teks</b>
- Menggunakan tag ``<mark>``,``<b>``,``<i>``,dan ``<ins>``
![img8](image/0-1-3_a%2Btext-formatting.png)
- Mencoba beberapa tag, dengan paragraf baru
![img9](image/0-1-3-1_a%2Btry-text-formatting.png)

### <b>4. Menyisipkan Gambar</b>
![img10](image/0-1-4_a%2Binsert-image.PNG)
- Menambahkan atribut ``width`` untuk menyesuaikan ukuran
![img11](image/0-1-4-1_a%2Btry-insert-image.PNG)

### <b>5. Menambahkan Hyperlink</b>
![img12](image/0-1-5_a%2Bhyperlink.PNG)
- Tampilan halaman 2
![img13](image/0-1-5-1_a%2Btry-hyperlink.PNG)

## Latihan
<b>1. 1akukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?</b>
  - Jawaban = Ya, akan berubah. Seperti berikut:
  Sebelum
  ![img14](image/0-1-5_a%2Bhyperlink.PNG)
  <br>Sesudah
  ![img15](image/1-wrong-tag.PNG)
  - Kesalahan penulisan dari ``<title>`` menjadi ``<tilte>`` dapat merubah isi (pada) tag yang seharusnya ``Tag HTML Dasar`` menjadi ``lab1_tag_dasar.html``. Browser tidak mengerti perintah ``<tilte>`` kemudian hanya menampilkan nama file-nya saja.  
<br>

<b>2. Apa perbedaan dari tag ``<p>`` dengan tag ``<br>``, berikan penjelasannya!</b>
  - Jawaban = Keduanya merupakan hal berbeda,
  ![img16](image/2-diff-p-br.PNG)
  - Tag ``<p>`` (paragraph) akan memberi ruang kosong setiap kali ganti baris, sedangkan ``<br>`` tidak menambah ruang pada keduanya(sebelum/sesudah baris). Tag ``<p>`` juga memiliki penutup ``</p>`` (karna fungsinya sebagai paragraf), sedangkan ``<br>`` tidak memiliki.
<br>

<b>3. Apa perbedaan atribut ``<title>`` dan ``<alt>`` pada tag ``<img>``, berikan penjelasannya!</b>
  - Jawaban = Keduanya merupakan hal berbeda,
  ![img17](image/3-diff-title-alt.PNG)
  - Tag ``<alt>`` akan menampilkan kata jika gambar gagal dimuat (link error, kesalahan penulisan kode, dll).<br>
  ![img18](image/3-diff-title-alt-n.jpg)
  -Sedangkan Tag ``<title>`` akan menampilkan kata jika kursor diarahkan kepada gambar yang mengandung atribut tersebut.
<br>

<b>4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!</b>
  - Jawaban = Width sudah cukup, namun tergantung tujuan dari media nanti.
  ![img18](image/4-diff-width-height.PNG)
  - Tag ``<width>`` untuk mengatur lebar gambar.
  - Tag ``<height>`` untuk menagatur tinggi gambar.
  - Keduanya memiliki fungsi masing-masing dalam media horizontal dan vertikal.
<br>

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent), apa yang terjadi pada masing-masing nilai atribut tersebut?
  - Jawaban = Untuk navigasi le halaman yang dituju, ada 4 proses:
  - Pada atribut ``_blank``, ketika mengklik tautan, akan membuka halaman yang dituju pada <b>tab baru</b>.<br>
  ![gif1](https://media.giphy.com/media/ErVTKbX6RtjMb1g0wS/giphy.gif)<br>
  - Pada atribut ``_self``, ketika mengklik tautan, akan membuka halaman yang dituju pada <b>Frame-nya(sendiri)</b>.<br>
  ![gif2](https://media.giphy.com/media/7CZhYRcUJhEi6eFUtj/giphy.gif)<br>
  - Pada atribut ``_top``, ketika mengklik tautan, akan membuka halaman yang dituju pada <b>satu (jendela) halaman penuh</b>, hampir mirip dengan ``_self``.<br>
  ![gif3](https://media.giphy.com/media/rPKV1UADltNDJtzE8o/giphy.gif)<br>
  - Pada atribut ``_parent``, ketika mengklik tautan, akan membuka halaman yang dituju pada <b>Frameset langsung(induk)</b>, hampir mirip dengan ``_self``.<br>
  ![gif4](https://media.giphy.com/media/jGkHlYlRBzDLjFYPNa/giphy.gif)
