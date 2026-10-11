# Website Zayamiyu

Halaman statis satu muka untuk zayamiyu.com, plus `privasi.html`. Tanpa npm, tanpa
build, tanpa pelacak, dan font disimpan lokal (tidak memanggil Google Fonts), supaya
klaim "tanpa pelacak" berlaku juga untuk website ini sendiri.

- Dua bahasa dalam satu berkas: elemen `lang="id"` dan `lang="en"`, ditukar tombol di
  kanan atas. Pilihan bahasa disimpan di localStorage pengunjung.
- Tangkapan layar di `img/` diambil dari aplikasi Belajar Berhitung yang asli.
- Tautan ke aplikasi memakai https://berhitung.zayamiyu.com (subdomain di Cloudflare,
  CNAME ke project Vercel belajar-berhitung, DNS only).

**Isi website harus sama dengan isi formulir program dan dengan aplikasinya.** Fitur
yang belum tayang ditandai "Sedang dikembangkan". Jangan ubah labelnya menjadi "Sudah
tersedia" sebelum fiturnya benar-benar tayang.
