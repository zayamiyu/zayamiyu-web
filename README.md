# Website Zayamiyu

Halaman statis satu muka untuk zayamiyu.com, plus `privasi.html`. Tanpa npm, tanpa
build, tanpa pelacak, dan font disimpan lokal (tidak memanggil Google Fonts), supaya
klaim "tanpa pelacak" berlaku juga untuk website ini sendiri.

- Dua bahasa dalam satu berkas: elemen `lang="id"` dan `lang="en"`, ditukar tombol di
  kanan atas. Pilihan bahasa disimpan di localStorage pengunjung.
- Tangkapan layar di `img/` diambil dari aplikasi Belajar Berhitung yang asli.
- Tautan ke aplikasi memakai https://berhitung.zayamiyu.com (subdomain di Cloudflare,
  CNAME ke project Vercel belajar-berhitung, DNS only).

**Isi website harus sama dengan isi formulir program dan dengan aplikasinya.** Aplikasi
disebut "versi beta", dan website hanya menyebut fitur yang sudah benar-benar tayang.
Jangan menambahkan janji fitur yang belum ada.

## Tempat tayang

- Repo ini public dan di-deploy otomatis oleh Vercel (project `zayamiyu-web`) setiap ada
  push ke `main`. Repo milik organisasi GitHub harus tetap public selama memakai paket
  Vercel gratis (Hobby), karena paket itu tidak bisa men-deploy repo private milik
  organisasi.
- Domain: https://www.zayamiyu.com (https://zayamiyu.com diarahkan ke sana). DNS di
  Cloudflare, CNAME ke Vercel, DNS only. Record MX dan TXT milik email iCloud jangan
  diubah.
- Jangan simpan apa pun yang rahasia di repo ini: semuanya bisa dibaca publik.
