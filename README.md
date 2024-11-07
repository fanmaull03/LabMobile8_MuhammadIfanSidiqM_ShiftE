# Penjelasan CRUD pada setiap gambar/page

<img src="https://github.com/user-attachments/assets/fe704f56-79c3-4075-9012-d55eb334a5a5" width="280">
<br> 
<b>1. Create (Tambah Data Mahasiswa)</b> <br> <br>
<ul>
  <li>Tombol "TAMBAH MAHASISWA": Tombol ini digunakan untuk menambahkan data mahasiswa baru. Ketika tombol ini ditekan, sebuah modal akan muncul (sesuai implementasi kode sebelumnya) dengan input untuk nama dan jurusan mahasiswa.</li>
  <li>Proses: Setelah data nama dan jurusan diisi dan dikonfirmasi (misalnya dengan menekan tombol "Tambah Mahasiswa" pada modal), data baru akan dikirim ke server menggunakan metode POST. Server akan menyimpan data tersebut ke dalam database, dan data baru ini akan ditampilkan di daftar mahasiswa setelah diambil kembali.</li>
</ul>
<br>
<b>2. Read (Tampil Data Mahasiswa)</b> <br> <br>
<ul>
  <li>Daftar Data Mahasiswa: Di bagian utama, data mahasiswa ditampilkan dalam bentuk kartu (card) yang menampilkan nama dan jurusan mahasiswa.</li>
  <li>Proses: Data ini diambil dari database dengan permintaan GET yang dikirim ke server. Saat halaman pertama kali dimuat, aplikasi akan mengambil seluruh data mahasiswa dari server dan menampilkannya.</li>
</ul>
<br>

<b>3. Update (Edit Data Mahasiswa)</b> <br> <br>
<ul>
  <li>Tombol "EDIT": Setiap mahasiswa memiliki tombol "EDIT" di sebelah kanan. Ketika tombol ini ditekan, sebuah modal akan muncul dengan input yang sudah diisi dengan data mahasiswa yang akan diedit.</li>
  <li>Proses: Setelah perubahan pada nama atau jurusan mahasiswa dilakukan, data yang diperbarui akan dikirim ke server menggunakan metode PUT atau POST (tergantung implementasi server) untuk memperbarui data mahasiswa yang ada. Data yang diperbarui kemudian akan ditampilkan di daftar setelah permintaan berhasil.</li>
</ul>

<b>4. Delete (Hapus Data Mahasiswa)</b> <br> <br>
<ul>
  <li>Tombol "HAPUS": Setiap mahasiswa juga memiliki tombol "HAPUS" di sebelah kanan tombol "EDIT". Ketika tombol ini ditekan, aplikasi akan menampilkan konfirmasi (alert) yang menanyakan apakah pengguna yakin ingin menghapus data tersebut.</li>
  <li>Proses: Jika pengguna mengonfirmasi untuk menghapus, aplikasi akan mengirim permintaan DELETE ke server dengan ID mahasiswa yang akan dihapus. Server akan menghapus data tersebut dari database, dan daftar mahasiswa di aplikasi akan diperbarui dengan data terbaru (tanpa data yang dihapus).</li>
</ul>
