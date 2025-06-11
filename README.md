# KSP Manager - Data Kredit Peminjam

Aplikasi manajemen data kredit peminjam untuk Koperasi Simpan Pinjam.

## Cara Download dan Menjalankan Aplikasi

1. Clone repository ini:
```bash
git clone <repository-url>
cd ksp-manager
```

2. Install dependencies:
```bash
npm install
```

3. Jalankan aplikasi:
```bash
npm run dev
```

4. Buka browser dan akses:
```
http://localhost:8000
```

## Teknologi yang Digunakan

- Next.js 15
- Tailwind CSS
- Shadcn UI Components
- TypeScript
- Lucide Icons

## Fitur

- Dashboard dengan ringkasan data
- Data Anggota
- Data Pinjaman
- Pembayaran
- Laporan
- Tampilan jatuh tempo mingguan
- Riwayat transaksi terbaru

## Struktur Project

```
src/
├── app/
│   ├── layout.tsx
│   ├── page.tsx
│   └── globals.css
├── components/
│   ├── DashboardCard.tsx
│   ├── DueThisWeekTable.tsx
│   ├── LatestTransactionsTable.tsx
│   └── Sidebar.tsx
└── lib/
    └── utils.ts
```

## Requirements

- Node.js 18.0 atau lebih baru
- NPM 8.0 atau lebih baru

## Lisensi

MIT License
