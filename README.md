# backend-5053241039

Repo tugas mata kuliah **Pengembangan Backend Dasar**, dibuat dari template [`webdev-if-its/backend-template`](https://github.com/webdev-if-its/backend-template). Ganti judul di atas jadi nama repo kalian sendiri (`backend-nrp`, contoh: `backend-5025201012`).

## Aturan Umum

- Tugas tiap pertemuan disimpan di folder `pertemuan-XX/` pada repo ini.
- Commit message wajib menyebut level yang dicapai: `pertemuan-XX: level N selesai`.
- Deadline push: sebelum pertemuan berikutnya dimulai.
- Semua level dicek otomatis lewat `go test` — baca `pertemuan-XX/SOAL.md` tiap minggu untuk detail levelnya.

## Mengambil Pertemuan Baru Tiap Minggu

Repo ini **tidak otomatis sinkron** dengan template dosen. Begitu ada pertemuan baru, jalankan (ganti `pertemuan-02` sesuai minggu berjalan):

```bash
git fetch https://github.com/webdev-if-its/backend-template.git main
git checkout FETCH_HEAD -- pertemuan-02
```

Perintah ini **aman dijalankan kapan pun** — tidak akan menimpa folder pertemuan lain yang sudah kalian kerjakan, karena hanya mengambil folder yang disebutkan. Setelah itu, commit folder barunya seperti biasa.

Kalau dosen memperbaiki sesuatu di pertemuan yang sudah dirilis (mis. ada bug di test), biasanya cukup ambil ulang file yang diperbaiki saja, bukan seluruh folder — akan diumumkan file mana yang berubah.

---

Bagian di bawah ini **isi bertahap** sesuai level yang sedang kalian kerjakan (lihat `pertemuan-01/SOAL.md`) — heading-nya dicek otomatis, jangan diganti namanya.

## Identitas
- Nama: Handhika Putra Widyartono
- NRP: 5053241039
- Kelas: M

## Commit vs Push
Commit: Commit dalam github itu jika kita sudah membuat/merubah sebuah code yang sudah ada di repository, kita akan men-commit perubahan code kita menggunakan terminal dengan cara 'cd project', lalu 'git add' untuk menambahkan file codingan yang berubah ke local, dan untuk commit perubahan dengan cara 'git commit -m "feat: add navbar"' yang bertujuan jika kita push nanti, kita atau orang lain dapat melihat dokumentasi atau penjelasan apa saja yang berubah atau ditambahkan di file ini

Push: Setelah commit, kita perlu push untuk istilahnya mengupload hasil commit kita yang tadi di local, ke githubnya dan akan keliatan commit yang sudah tadi di lakukan.

## Reproducibility
Jika satu orang menggunakan versi yang go yang lama, tidak akan bisa di compile. Solusinya adalah memakai docker

## Catatan Merge Conflict
Merge conflict terjadi tergantung di baris yang di edit, untuk kasus ini di bagian function CetakInfo di karenakan branch line function return nya antara branch main dan branch fitur-sapaan berbeda, sehingga muncul nya conflict merge dan untuk mengatasinya mungkin di periksa lagi codingannya dan kira kira yang sangat diperlukan yang mana atau menyesuaikan dokumentasi yang ada seperti apa.

## Kenapa .gitignore Penting
.gitignore penting karena jika project besar di upload di github dan otomatis orang publik dapat mengakses github, file codingan kita akan bahaya jika API atau kode yang sensitif dan bersifat private dilihat oleh publik, dengan adanya .gitignore, github paham file mana saja yang tidak di upload ke github, sebagai contoh yang paling sering adalah .env karena menyimpan hal private seperti API key, password, database password, dan lain-lain.

## Refleksi
Dari saya, kesulitan di pertemuan 01 lebih ke setup Go dan sedikit sulit memahami syntax Go seperti %s, mungkin bisa di overview sedikit perbandingan syntax bahasa populer misalnya Javascript/Typescript dengan Go seperti apa perbandingannya.

Dan juga saya harap di kelas Backend ini, saya bisa dapat gambaran secara detail bahwa backend itu fungsi nya untuk apa, apa perbedaan menggunakan dan tidak menggunakan framework dalam backend seperti apa. Dan menurut saya yang paling efektif untuk saya yaitu dengan menjadikan contoh real project, misalnya seperti Tokopedia kira kira alur backend nya seperti apa dan kenapa perlu backend.

Saya akhirnya paham ternyata bahasa Go tidak terlalu semengerikan itu.