# 🎨 Modern Login UI

Dark-themed authentication UI dengan animasi smooth dan desain yang elegan.

![Preview](https://img.shields.io/badge/Status-Production%20Ready-success)
![License](https://img.shields.io/badge/License-MIT-blue)

## ✨ Fitur

- 🌓 **Dark Theme** - Desain modern dengan ambient background
- 🎭 **Dual Form** - Login dan Register dalam satu halaman
- ✍️ **Typewriter Animation** - Efek ketik yang smooth pada judul
- 🎯 **Form Validation** - Validasi real-time dengan error messages
- 💾 **Local Storage** - Simpan data user di browser
- 📱 **Responsive** - Tampilan optimal di semua device
- ♿ **Accessible** - Support reduced motion & focus states
- 🔐 **Password Toggle** - Show/hide password dengan satu klik
- 🍞 **Toast Notifications** - Feedback user yang elegan

## 🛠️ Teknologi

| Technology | Version | Purpose |
|------------|---------|---------|
| [TailwindCSS](https://tailwindcss.com/) | CDN | Utility-first CSS |
| [Lucide Icons](https://lucide.dev/) | Latest | Icon library |
| [Geist Font](https://vercel.com/font) | Latest | Typography |
| Vanilla JavaScript | ES6+ | Interactivity |

## 🚀 Cara Penggunaan

### 1. Clone Repository
```bash
git clone https://github.com/nathggn/modern-login-ui.git
cd modern-login-ui
```

### 2. Buka di Browser
Cukup buka file `index.html` di browser modern (Chrome, Firefox, Edge, Safari)

```bash
# Atau gunakan live server jika ada
npx serve .
```

### 3. Test Fitur
- **Register**: Klik tab "Daftar" dan buat akun baru
- **Login**: Gunakan username & password yang sudah dibuat
- Data tersimpan di `localStorage` browser

## 🎨 Customization

### Mengubah Warna Theme
Edit CSS variables di bagian `<style>`:

```css
:root {
  --bg: #050505;              /* Background utama */
  --card: rgba(255, 255, 255, 0.02);  /* Card background */
  --accent: #e4e4e7;          /* Warna accent */
  --text: #fafafa;            /* Warna text */
}
```

### Mengubah Font
Ganti import font di `<head>`:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont&display=swap" rel="stylesheet">
```

Lalu update `fontFamily` di Tailwind config.

## 📁 Struktur File

```
modern-login-ui/
├── .gitignore          # Git ignore rules
├── LICENSE             # MIT License
├── README.md           # Dokumentasi
└── index.html          # Main file
```

## 🔒 Security Notes

> ⚠️ **PENTING**: Project ini menggunakan `localStorage` untuk demo purposes saja. 
> **JANGAN** digunakan untuk production tanpa backend authentication yang proper.

Untuk production, ganti dengan:
- Backend API (Node.js, Python, PHP, dll)
- JWT / Session-based authentication
- HTTPS encryption
- Password hashing (bcrypt, argon2)

## 📸 Screenshot

### Login Form
![Login](https://via.placeholder.com/400x500/050505/e4e4e7?text=Login+Form)

### Register Form
![Register](https://via.placeholder.com/400x500/050505/e4e4e7?text=Register+Form)

## 🤝 Kontribusi

Kontribusi selalu diterima! Silakan:
1. Fork repository
2. Buat feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

## 📄 License

Distributed under the MIT License. Lihat `LICENSE` untuk detail.

## 👨‍💻 Author

Created with ❤️ by **nathggn**

---

⭐ **Star this repo** jika kamu suka dengan project ini!
