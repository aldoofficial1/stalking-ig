# Stalking Instagram by AldoOfficialR

Interactive Node.js script untuk stalking akun Instagram di terminal ala bot WA.

---

## Fitur

* Input username via terminal (readline)
* Spinner saat request menggunakan `ora`
* Error handling menggunakan `try...catch`
* Output rapi dengan box, warna, emoji ala bot WhatsApp
* Loop: bisa stalking banyak username tanpa restart (ketik `exit` untuk keluar)
* Header & branding: "Stalking Instagram by AldoOfficialR"
* Link avatar & bio panjang otomatis dimask (`[link removed]`)

## Instalasi

Pastikan Node.js sudah terpasang.

```bash
# Masuk ke folder project
cd /path/ke/project

# Install dependency tanpa bin links
npm install axios chalk@4 ora@5 boxen@5 --no-bin-links
```

## Cara Pakai

```bash
# Jalankan script
node stalkIG.js
```

1. Masukkan username Instagram yang ingin di-stalk.
2. Script akan menampilkan:

   * Username
   * Name
   * Followers / Following / Posts
   * Bio
   * Avatar (link dimask)
3. Ketik username lain atau `exit` untuk keluar.

## Catatan

* Script ini hanya untuk tujuan belajar / demo.
* Hormati privasi akun Instagram.
* Tidak menyimpan data sensitif.

## Lisensi

MIT License

---

Made with ♥ by AldoOfficialR
