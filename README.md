# SBC/SBM Lab

Website edukasi interaktif tentang **Single Board Computer (SBC)** dan **Single Board Controller**. Berisi perbandingan spesifikasi, contoh board populer, panduan memilih, dan kuis singkat.

Dibuat dengan HTML, CSS, dan JavaScript murni — tidak ada proses build, tidak ada dependency selain font dari Google Fonts.

## Cara publish ke GitHub Pages

1. **Buat repository baru** di GitHub (public), misalnya `sbc-sbm-lab`.
2. **Upload file `index.html`** ini ke root repository tersebut.
   - Lewat web: buka repo → "Add file" → "Upload files" → pilih `index.html` → commit.
   - Lewat terminal:
     ```bash
     git init
     git add index.html README.md
     git commit -m "Initial commit: SBC/SBM Lab"
     git branch -M main
     git remote add origin https://github.com/USERNAME/sbc-sbm-lab.git
     git push -u origin main
     ```
3. **Aktifkan GitHub Pages**:
   - Buka repo → tab **Settings** → menu **Pages** (di sidebar kiri).
   - Pada bagian **Build and deployment** → **Source**, pilih **Deploy from a branch**.
   - Pilih branch **main** dan folder **/ (root)** → klik **Save**.
4. Tunggu 1–2 menit, lalu situs akan aktif di:
   ```
   https://USERNAME.github.io/sbc-sbm-lab/
   ```
   (ganti `USERNAME` dan `sbc-sbm-lab` sesuai akun dan nama repo kamu)

## Struktur file

```
.
├── index.html   # seluruh website (HTML + CSS + JS dalam satu file)
└── README.md
```

Karena semuanya ada dalam satu file `index.html`, kamu bebas mengedit isi materi, warna, atau menambah section langsung di file tersebut tanpa perlu tool build apa pun.
