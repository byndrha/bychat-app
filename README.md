# byChat

Aplikasi mobile untuk platform byChat. Dibangun dengan React Native dan Expo.

---

## Tentang

byChat adalah aplikasi mobile yang memungkinkan tim dukungan pelanggan untuk mengelola percakapan, merespons pesan, dan berkolaborasi — kapan saja, di mana saja.

## Fitur

- Tidak ketinggalan percakapan dari pelanggan baru
- Tindak lanjuti percakapan pelanggan dengan mudah
- Balas cepat menggunakan canned responses
- Terima notifikasi real-time untuk aktivitas sistem
- Berkomunikasi dengan anggota tim melalui catatan privat
- Atur status percakapan
- Dan masih banyak lagi!

## Persyaratan

- **iOS**: 13.4 ke atas
- **Android**: 6.0 (API 24) ke atas

## Teknologi

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [React Navigation](https://reactnavigation.org/)

## Instalasi & Pengembangan

### Prasyarat

- Node.js 18+
- pnpm 10+
- Expo CLI

### Langkah Setup

1. Clone repositori ini:
   ```bash
   git clone https://github.com/byndrha/bychat-app.git
   cd bychat-app
   ```

2. Install dependensi:
   ```bash
   pnpm install
   ```

3. Salin file environment:
   ```bash
   cp .env.example .env
   ```
   Isi nilai yang diperlukan di file `.env`.

4. Jalankan aplikasi:
   ```bash
   pnpm start
   ```

### Build

```bash
# Build Android
pnpm build:android

# Build iOS
pnpm build:ios
```

## Lisensi

Hak cipta © 2024 Byndrha. Seluruh hak dilindungi.
