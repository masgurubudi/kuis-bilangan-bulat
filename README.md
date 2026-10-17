# Kuis Bilangan Bulat — Game Matematika SMP

Game/kuis interaktif bilangan bulat (penjumlahan, pengurangan, perkalian, pembagian)
untuk siswa SMP. Satu file HTML, bisa dimainkan offline di browser HP maupun laptop.

## Cara memainkan
Buka `index.html` di browser. Tidak perlu internet, tidak perlu install apa pun.

## Cara mempublikasikan ke GitHub Pages (gratis)

1. Buat repositori baru di GitHub (misalnya bernama `kuis-bilangan-bulat`).
2. Upload file `index.html` ke repositori tersebut (bisa lewat tombol
   *Add file → Upload files* di website GitHub, tanpa perlu git).
3. Buka *Settings → Pages*, pada *Branch* pilih `main` lalu *Save*.
4. Tunggu ±1 menit — kuis bisa dimainkan di alamat:
   `https://<username-github>.github.io/kuis-bilangan-bulat/`

## Lewat terminal (alternatif)

```bash
cd kuis-bilangan-bulat
git init
git add index.html README.md
git commit -m "Kuis bilangan bulat SMP"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

Lalu aktifkan Pages seperti langkah 3–4 di atas.
