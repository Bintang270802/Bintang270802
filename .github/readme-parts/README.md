# 📝 README Parts - Documentation

## Struktur Folder

File-file di folder ini akan otomatis digabungkan menjadi `README.md` utama menggunakan GitHub Actions.

### File Parts:

1. **header.md** - Header profil dengan nama dan gambar anime
2. **about.md** - Bagian About Me
3. **tech-stack.md** - Teknologi dan tools yang dikuasai
4. **contribution.md** - Contribution graph dan anime zone
5. **statistics.md** - GitHub statistics (stats, top langs, streak)
6. **connect.md** - Social media links dengan anime kawaii
7. **footer.md** - Footer dengan wave animation

## Cara Kerja

1. Edit file yang ingin diubah di folder `.github/readme-parts/`
2. Commit dan push perubahan ke branch `main`
3. GitHub Actions akan otomatis menjalankan workflow
4. README.md akan di-generate ulang dan di-commit otomatis

## Manual Trigger

Anda juga bisa trigger workflow secara manual:
1. Buka tab "Actions" di repository
2. Pilih workflow "Update README"
3. Klik "Run workflow"

## Urutan File

File akan digabungkan dengan urutan:
```
header.md
---
about.md
---
tech-stack.md
---
contribution.md
---
statistics.md
---
connect.md
---
footer.md
```

## Tips

- Setiap file sudah include heading (##) sendiri
- Separator `---` ditambahkan otomatis
- Edit file individual untuk perubahan spesifik
- Lebih mudah maintain dan organize code
