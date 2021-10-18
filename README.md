# LatihanVCS
# Cara menggunakan git
**Pengertian singkat git**

Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.
# Cara menambahkan global config

pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi Username dan Email. Jalankan perintah berikut
- git config --global user.name "username"

- git config --global user.email "email"
![2021-10-18 (4)](https://user-images.githubusercontent.com/92381092/137740949-491f4e1c-5bf9-4e3a-8a21-a54ec4a26798.png)
# Jalankan perintah git init. untuk membuat repository local

- git init
![2021-10-18 (5)](https://user-images.githubusercontent.com/92381092/137742132-63e1f133-64ef-4bc9-a68e-6e9bf7b10bc3.png)

# Untuk membuat file dapat menggunakan Text Editor, lalu menyimpan filenya pada repository. disini saya akan membuatkan contoh membuat file README.md dengan perintah berikut

- echo "#labs1" >> README.md
![2021-10-18 (7)](https://user-images.githubusercontent.com/92381092/137746591-0b8c2058-b815-4666-9d74-ac6d47a9099e.png)
# Untuk menambahkan file yang sudah kita buat, gunakan perintah git add (Nama File) atau bisa menggunakan git add. (jika file nya ada banyak)

- git add README.md
- git add
![2021-10-18 (8)](https://user-images.githubusercontent.com/92381092/137747751-a55a4f42-a3ee-4ae1-a488-7f9d6163d63d.png)
# Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m "nama project" dan yang ada didalam kutip "" itu adalah nama komentar setiap kita mencommit project

- git commit -m "nama project"
![2021-10-18 (9)](https://user-images.githubusercontent.com/92381092/137748801-1552f3c9-87b4-4ddc-a32e-dc40a14e88ad.png)
# Untuk menyimpan setiap perubahan pada repository local, gunakan perintah git remote add origin (url)

-git remote add origin








