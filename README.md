echo "# Exchange Global Cold Wallet

Exodus tarzı, çoklu blockchain destekli, masaüstü (Electron.js) soğuk cüzdan uygulaması.

## Özellikler

- HD cüzdan (BIP39/BIP44), AES-256 ile şifreleme, seed phrase güvenliği
- Bitcoin, Ethereum, BSC, Solana, Tron, Avalanche desteği
- Electron.js + React ile masaüstü arayüzü
- Rust backend ile güvenli cüzdan motoru

## Ekran Görüntüleri

![Cüzdan Dashboard](https://i.imgyukle.com/2025/05/15/CFrrd6.png)

## Geliştirme

### Bağımlılıklar

- Node.js (v18+)
- Electron
- React
- Rust (wallet-engine için)

### Kurulum

```bash
# Ana bağımlılıkları yükle
npm install

# Geliştirme modunda çalıştır
npm run dev
```

### Derleme

```bash
# Uygulamayı derle
npm run build

# Üretim için paketleme
npm run dist
```

## Güvenlik

- Seed phrase güvenliği için AES-256 şifreleme
- Rust ile geliştirilen güvenli wallet-engine
- Tamamen offline çalışabilen güvenli HD cüzdan altyapısı

## Lisans

UNLICENSED - Copyright (c) 2025 Exchange Global" > README.md
