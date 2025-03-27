## Live Demo
Website ini dapat diakses melalui link berikut:
[Inagata Test - GitHub Pages](https://hakimlutfi46.github.io/inagata-test/public/)

## Struktur Folder
```
/ (root)
│── src/
│   ├── input.css   # File Tailwind CSS sebelum dikompilasi
│   ├── output.css  # File CSS hasil build Tailwind
│── public/
│   ├── index.html  # Halaman utama website
│── tailwind.config.js  # Konfigurasi Tailwind CSS
│── package.json    # Dependencies & script npm
│── README.md       # Dokumentasi proyek
```

## Cara Menjalankan Proyek Secara Lokal
Pastikan kamu telah menginstall **Node.js** dan **npm**.

### 1. Clone Repository
```
git clone https://github.com/hakimlutfi46/inagata-test.git
cd inagata-test
```

### 2. Install Dependencies
```
npm install
```

### 3. Build Tailwind CSS
Jalankan perintah berikut untuk mengompilasi Tailwind CSS:
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

### 4. Jalankan Secara Lokal
Buka file `public/index.html` langsung di browser atau gunakan ekstensi **Live Server** di VS Code.
