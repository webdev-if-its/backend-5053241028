# backend-nrp

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
- Nama: Oktavian Ramadhan
- NRP: 5053241028
- Kelas: M

## Commit vs Push
Commit adalah menyimpan perubahan yang telah kita lakukan sementara di local atau hanya di perangakat yg kita gunakan dan hanya bisa kita lihat sendiri. Sedangkan Push adalah menetapkan perubahan yg telah commit dan sekarang perubahan yg telah kita lakukan tidak terjadi hanya di local tetapi bisa dilihat orang lain juga. Apabila ada satu orng yg melakukan commit dan lupa untuk melakukan push maka perubahan yang dilakukan tidak akan terlihat oleh orang lain.

## Reproducibility
Apabila teman kita menjalankan mengunakan verison go yg lebih lama maka akan terjadi compilation error. apabila mengunakan versi yg lebih baru akan tetep berjalan degan baik.

## Catatan Merge Conflict
Terjadi conflict pada bagian function CetakInfo di line 29. itu terjadi kerena adanya perbedaaan pada line yg sama dari kedua branch itu. Masalah itu bisa diselesaikan dengan memilih versi yang mana yg benar untuk diterapkan misal dari merge tadi adalah versi incoming merge.

## Kenapa .gitignore Penting
Apabila file build ataupun ide ikut tercommit maupun push akan menyebakan error build pada rekan tim kita yg melakukan pull dari file build kia

## Refleksi
saya mengalami kesusahan pada level 3. karena saya mengira bahwa hanya ada 1 return saja yang di tandai dengan "TODO". Saya akhirnya tahu bahwa saya salah paham.