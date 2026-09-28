# NEXORA

NEXORA adalah website informasi sederhana mengenai teknologi dan cybersecurity. Project ini dibuat menggunakan HTML5, CSS3, dan JavaScript dengan tiga halaman materi yang terpisah serta desain responsive untuk laptop dan HP.

## Struktur

```text
NEXORA/
├── assets/
│   ├── images/
│   │   ├── hero-banner.jpg
│   │   └── cyber-security.png
│   └── icons/
│       └── favicon.ico
├── css/
│   └── style.css
├── js/
│   └── script.js
├── index.html
├── technology.html
├── cybersecurity.html
├── 404.html
└── README.md
```

## Fitur
- Landing page NEXORA
- Halaman materi Technology dan Cybersecurity
- Halaman 404
- Semantic HTML: header, nav, main, section, footer
- CSS Variables untuk tema  Dark futuristic blue
- Responsive Web Design dengan media query
- Hamburger menu pada layar kecil
- Dark/Light mode dengan localStorage
- Animasi reveal saat halaman di-scroll
- Tombol kembali ke atas
- Favicon dan aset gambar lokal

## Pengujian Lokal
1. Download atau clone repository.
2. Buka folder project di VS Code.
3. Jalankan `index.html` dengan Live Server, atau buka file tersebut langsung di browser.
4. Cek navigasi Home, Technology, Cybersecurity, dan 404.
5. Uji tampilan desktop dan mobile.
6. Uji hamburger menu dan tombol tema Dark futuristic blue

## GitHub Pages / Live Demo
Setelah repository di-push ke GitHub, buka **Settings → Pages → Deploy from a branch**, pilih branch utama (biasanya `main`) dan folder `/root`, lalu simpan.

Setelah deployment selesai, tautan Live Demo akan berbentuk:
`https://USERNAME.github.io/NAMA-REPOSITORY/`

Ganti URL tersebut dengan link GitHub Pages repository yang sebenarnya setelah project dipublikasikan.

## Contoh Commit
- `feat: add responsive navigation`
- `feat: add technology and cybersecurity pages`
- `feat: add dark light mode`
- `style: improve responsive layout`
- `docs: update project README`
