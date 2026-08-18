# Fisika Interaktif — MAN 1 Soppeng

Kumpulan materi Fisika interaktif (simulasi + kuis) untuk siswa kelas X, XI, XII.
Web statis murni (HTML + CSS + JS), di-deploy via GitHub Pages.

## Struktur
```
index.html              → beranda daftar materi
assets/style.css        → style mobile-first
materi/xi/glbb.html     → GLBB (Gerak Lurus Berubah Beraturan)
```

## Cara deploy (GitHub Pages)
1. Push repo ini ke GitHub.
2. Settings → Pages → Source: `main` branch, folder `/ (root)`.
3. Tunggu ±1 menit, buka `https://<user>.github.io/<repo>/`.

## Menambah materi
1. Buat file di `materi/<kelas>/<topik>.html` (copy struktur glbb.html).
2. Tambahkan link di `index.html`.
