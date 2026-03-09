# Project Kebijakan Privasi

Project ini berisi halaman kebijakan privasi yang dibuat dengan HTML dan CSS.

## Struktur Project

```
privacy-policy/
├── index.html      # File HTML utama
├── style.css       # File CSS untuk styling
└── README.md       # Dokumentasi project
```

## Cara Menjalankan Project

### Metode 1: Membuka langsung di browser

1. Buka File Explorer
2. Navigasi ke folder `D:\Shelter\privacy-policy`
3. Klik dua kali pada file `index.html`
4. Halaman akan terbuka di browser default Anda

### Metode 2: Menggunakan Live Server (disarankan untuk pengembangan)

Jika Anda menggunakan Visual Studio Code:

1. Buka folder project di VS Code
2. Install ekstensi "Live Server" dari marketplace
3. Klik kanan pada file `index.html`
4. Pilih "Open with Live Server"
5. Halaman akan terbuka di browser dengan auto-reload saat ada perubahan

### Metode 3: Menggunakan Python HTTP Server

1. Buka Command Prompt atau PowerShell
2. Navigasi ke folder project:
   ```
   cd D:\Shelter\privacy-policy
   ```
3. Jalankan server:
   ```
   python -m http.server 8000
   ```
4. Buka browser dan akses: `http://localhost:8000`

### Metode 4: Menggunakan Node.js dan http-server

1. Install http-server secara global:
   ```
   npm install -g http-server
   ```
2. Navigasi ke folder project:
   ```
   cd D:\Shelter\privacy-policy
   ```
3. Jalankan server:
   ```
   http-server
   ```
4. Buka browser dan ases URL yang ditampilkan (biasanya `http://localhost:8080`)

## Fitur

- Design responsif yang bekerja di desktop, tablet, dan mobile
- Animasi halus untuk pengalaman pengguna yang lebih baik
- Struktur HTML yang semantik dan SEO-friendly
- CSS yang terorganisir dengan baik dan mudah dikustomisasi

## Kustomisasi

### Mengubah Informasi Perusahaan

1. Buka file `index.html`
2. Ubah "Nama Perusahaan" dengan nama perusahaan Anda
3. Ganti informasi kontak di bagian "Hubungi Kami"
4. Perbarui tanggal di bagian "Terakhir diperbarui"

### Mengubah Warna Tema

1. Buka file `style.css`
2. Ubah variabel warna di bagian:
   - `#2c3e50` untuk warna header dan footer
   - `#3498db` untuk warna aksen dan link
   - `#f8f9fa` untuk warna background

### Menambah/Mengubah Konten

1. Buka file `index.html`
2. Tambahkan atau ubah bagian `<section>` sesuai kebutuhan
3. Pastikan untuk menggunakan struktur heading yang konsisten (h2, h3, dst.)

## Browser Support

Project ini kompatibel dengan browser modern:
- Chrome (versi terbaru)
- Firefox (versi terbaru)
- Safari (versi terbaru)
- Edge (versi terbaru)

## Lisensi

Project ini dilisensikan di bawah MIT License. Anda bebas menggunakan, memodifikasi, dan mendistribusikan kode ini sesuai kebutuhan.