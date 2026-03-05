# Cara Publish Landing Page ke GitHub

Saya telah menyiapkan Landing Page premium untuk **File Master** dan membuat repositori Git lokal di folder `File Master Page`.

Karena keterbatasan akses untuk *membuat* repositori baru di akun GitHub Anda secara otomatis, silakan ikuti 2 langkah super mudah ini untuk mempublikasikannya:

### 1. Buat Repositori di GitHub
- Masuk ke [GitHub.com](https://github.com)
- Klik tombol **New Repository**
- Beri nama: `File Master Page`
- Klik **Create repository** (Jangan centang Readme atau License).

### 2. Jalankan Perintah ini di Terminal (di folder File Master Page)
Buka terminal dan jalankan 2 baris ini:
```bash
git remote add origin https://github.com/isparmo/file-master-page.git
git push -u origin master
```

**Selesai!** Landing Page Anda akan langsung live. Jika Anda mengaktifkan **GitHub Pages** di pengaturan repo tersebut, dunia bisa langsung melihat promosi aplikasi keren Anda.
