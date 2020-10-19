#Dokumentasi Git

Dokumentasi Belajar Git

•	git --version : perintah untuk menunjukkan versi Git dan sistem operasi yang dingunakan.

•	git init : perintah untuk membuat direktori/repositori, jika direktori dengan nama yang sama sudah ada maka Git akan melakukan inisialisasi di direktori tersebut.

•	git status : mengetahui status dari repository lokal

•	git add : menambahkan file baru ke dalam repository yang dituju
- git add index.html : menambahkan file ‘index.html’ ke staging area

•	git commit -m “upload newfile index.html” : menyimpan perubahan file yang dilakukan beserta detail file

•	git push origin master: melakukan upload file yang telah berada di staging area yang ada di local

•	git pull origin master: melakukan pembaharuan file yang ada di lokal dengan cara mengambil file dari repository

•	git log : akan menampilkan apa saja commit yang pernah dilakukan
- git log -1 : menampilkan 1 commit terakhir
- git log – index.html : menampilkan spesifik commit pada file index.html

•	git checkout : berfungsi untuk berpindah branch ataupun berpindah ke keadaan commit berdasarkan hash commit yang dituju.
- git checkout e0006  -- style.css : berpindah ke commit sebelumnya, untuk mengembalikan file ‘style.css’ yang telah dihapus.
- git checkout update1 : berpindah ke branch update1

•	git branch : menampilkan semua branch yang ada di repository dan menunjukkan kita berada di posisi branch yang mana
- git branch update1: membuat branch baru yang bernama ‘update1’ di posisi commit terakhir
Note: Dengan berada di branch update1, semua perubahan baik itu penambahan file ataupun perubahan isi file hanya akan terjadi di branch update1 tampa mempengaruhi branch lainnya.
- git log –all –decorate –online –graph : menampilkan bentuk branch dalam bentuk graph 

•	git merge : menggabungkan dua branch antara branch master/branch aktif dengan branch yang dituju/dipilih
- git merge update1: menggabungkan branch master dengan branch update1
- git branch –merge : melihat daftar branch yang sudah di merge
- git branch -d update1 : menghapus branch dengan kondisi branch yang akan dihapus sudah di merge sebelumnya. 
- git branch -D <nama_branch>: menghapus branch secara langsung tampa kondisi apapun
- git merge update1: menggabungkan branch master dengan branch update1

•	git remote add origin : menghubungkan local repository dengan ke remote repository (github)

•	git push origin main : menggirimkan perubahan ke master branch tujuan lewat remote repository yang terhubung.

•	git pull origin main : menggabungkan semua perubahan yang ada di remote ke repository lokal
	





