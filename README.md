# SIMPONI - Sistem Informasi Monitoring Stunting
## Pemkab Lombok Tengah

![SIMPONI Logo](https://via.placeholder.com/400x100/22c55e/ffffff?text=SIMPONI)

### 🌟 Tentang SIMPONI

SIMPONI adalah sistem informasi monitoring dan pencegahan stunting yang dikembangkan untuk Pemerintah Kabupaten Lombok Tengah. Platform ini menyediakan:

- ✅ **Multi-role Access**: Admin, Staff, Pasien, Dokter
- ✅ **Customer Satisfaction**: Survei kepuasan pelanggan
- ✅ **File Management**: Upload, download, export, import
- ✅ **Professional UI**: Tampilan modern dan responsif
- ✅ **Real-time Updates**: Data ter-update secara real-time
- ✅ **WhatsApp Integration**: Notifikasi melalui WhatsApp
- ✅ **Offline Support**: Dapat berfungsi offline
- ✅ **Secure Authentication**: Sistem login yang aman

### 🚀 Demo Live

**[🌐 Akses SIMPONI Live Demo](https://your-username.github.io/simponi)**

### 👥 Default Login Credentials

| Role | Username | Password |
|------|----------|----------|
| **Admin** | admin | admin123 |
| **Staff** | staff | staff123 |
| **Dokter** | dokter | dokter123 |
| **Pasien** | pasien | pasien123 |

> ⚠️ **Catatan**: Hanya Admin yang memiliki akses penuh untuk mengubah password dan mengelola pengguna.

### 🛠️ Teknologi yang Digunakan

- **Frontend**: React 18, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL
- **UI Components**: Radix UI, Shadcn/ui
- **Icons**: Lucide React
- **State Management**: TanStack Query
- **Authentication**: Passport.js

### 🚀 Deployment ke GitHub Pages

#### 1. Fork Repository
```bash
# Clone repository ini
git clone https://github.com/your-username/simponi.git
cd simponi
```

#### 2. Install Dependencies
```bash
npm install
```

#### 3. Build untuk Production
```bash
npm run build
```

#### 4. Setup GitHub Pages
1. Buka repository di GitHub
2. Pergi ke **Settings** > **Pages**
3. Pilih **GitHub Actions** sebagai source
4. Push code ke branch `main`

#### 5. Akses Aplikasi
Setelah deployment selesai, aplikasi akan tersedia di:
```
https://your-username.github.io/simponi
```

### 🔧 Konfigurasi Environment

Buat file `.env` dari `.env.example`:

```env
NODE_ENV=production
DATABASE_URL=your_database_url
SESSION_SECRET=your_secret_key
WHATSAPP_API_KEY=your_whatsapp_key
```

### 📱 Fitur Utama

#### 1. **Dashboard Monitoring**
- Statistik stunting real-time
- Grafik pertumbuhan anak
- Alert dan notifikasi

#### 2. **Manajemen Data**
- CRUD data pasien
- Upload/download file
- Export ke Excel/PDF
- Import data bulk

#### 3. **Laporan dan Analisis**
- Laporan berkala
- Analisis tren stunting
- Visualisasi data geografis

#### 4. **Customer Satisfaction**
- Survei kepuasan online
- Rating dan feedback
- Analisis kepuasan

#### 5. **Integrasi WhatsApp**
- Notifikasi otomatis
- Reminder jadwal
- Broadcast informasi

### 🔒 Keamanan

- Enkripsi password dengan bcrypt
- Session management yang aman
- Role-based access control
- HTTPS enforced in production
- Input validation dan sanitization

### 📊 Monitoring & Performance

- Health check endpoint: `/api/health`
- Performance monitoring
- Error logging
- Uptime monitoring

### 🤝 Kontribusi

1. Fork repository
2. Buat feature branch (`git checkout -b feature/fitur-baru`)
3. Commit perubahan (`git commit -m 'Tambah fitur baru'`)
4. Push ke branch (`git push origin feature/fitur-baru`)
5. Buat Pull Request

### 📞 Support & Kontak

- **Email**: simponi@lomboktengahkab.go.id
- **WhatsApp**: +62 xxx xxxx xxxx
- **Website**: https://lomboktengahkab.go.id

### 📄 Lisensi

Copyright © 2024 Pemerintah Kabupaten Lombok Tengah. All rights reserved.

---

**SIMPONI** - Membangun Generasi Lombok Tengah yang Sehat dan Bebas Stunting 🌱