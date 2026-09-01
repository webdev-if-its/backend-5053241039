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
(tulis di sini)

## Catatan Merge Conflict
(tulis di sini)

## Kenapa .gitignore Penting
(tulis di sini)

## Refleksi
(tulis di sini)