# Mobil Bulmaca Oyunu 🎮

Mantık ve strateji seven oyuncular için geliştirilmiş, 6x6'lık bir ızgara üzerinde oynanan bulmaca oyunu.

## 🎯 Oyun Hakkında

Bu bulmaca oyunu, oyuncuların mantık yeteneklerini kullanarak 6x6'lık bir ızgarayı belirli kurallara göre doldurmasını gerektiren bir mobil oyundur. İki farklı sembol (☀️ ve 🎉) kullanarak, verilen ipuçları ve kurallara göre bulmacayı çözmeye çalışırsınız.

## 🛠️ Teknoloji Stack

- **Framework:** React Native
- **Dil:** TypeScript
- **State Yönetimi:** Redux Toolkit
- **UI Kütüphanesi:** React Native Paper
- **Animasyonlar:** React Native Reanimated
- **Test:** Jest & React Native Testing Library
- **Hedef Platformlar:** iOS ve Android
- **Minimum Gereksinimler:**
  - Android 5.0 ve üzeri
  - iOS 11.0 ve üzeri

## 📱 Özellikler

- 6x6 oyun tahtası
- İki farklı sembol (☀️ güneş ve 🎉 parti şapkası)
- Otomatik hata kontrolü
- Süre takibi
- İpucu sistemi
- Sınırsız bulmaca
- Geri alma özelliği
- Offline oynama desteği
- Dokunmatik optimizasyonu

## 🎮 Oyun Kuralları

1. Her satır ve sütunda eşit sayıda güneş ve parti şapkası olmalı (3'er adet)
2. Aynı sembol yatay veya dikey olarak en fazla 2 kez yan yana gelebilir
3. "=" işareti olan komşu kareler aynı sembolü içermeli
4. "×" işareti olan komşu kareler farklı sembolleri içermeli

## 🚀 Kurulum

1. Gerekli araçları yükleyin:

```bash
npm install -g react-native-cli
```

2. Projeyi klonlayın ve bağımlılıkları yükleyin:

```bash
git clone [repo-url]
cd [proje-adı]
npm install
```

3. iOS için pod kurulumu (macOS gerekli):

```bash
cd ios && pod install && cd ..
```

4. Uygulamayı çalıştırın:

```bash
# iOS için
npm run ios

# Android için
npm run android
```

## 🔧 Geliştirme Ortamı Gereksinimleri

- Node.js 14 veya üzeri
- npm veya yarn
- iOS geliştirmesi için:
  - macOS
  - Xcode
  - CocoaPods
- Android geliştirmesi için:
  - Android Studio
  - Android SDK
  - JDK 11 veya üzeri

## 📂 Proje Yapısı

```
src/
├── components/         # Yeniden kullanılabilir bileşenler
│   ├── Board/         # Oyun tahtası bileşenleri
│   ├── Cell/          # Hücre bileşenleri
│   └── UI/            # Genel UI bileşenleri
├── screens/           # Ekranlar
├── store/             # Redux store ve slice'lar
├── hooks/             # Custom hooks
├── utils/             # Yardımcı fonksiyonlar
├── types/             # TypeScript tipleri
└── assets/           # Görseller ve fontlar
```

## 🧪 Test

```bash
# Unit ve entegrasyon testlerini çalıştır
npm test

# Test coverage raporu
npm run test:coverage
```

## 🤝 Katkıda Bulunma

1. Bu repository'yi fork edin
2. Feature branch'i oluşturun (`git checkout -b feature/AmazingFeature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some AmazingFeature'`)
4. Branch'inizi push edin (`git push origin feature/AmazingFeature`)
5. Pull Request oluşturun

## 📝 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakınız.

## 📞 İletişim

Proje Sahibi - [@GithubUsername](https://github.com/username)

Proje Linki: [https://github.com/username/repo_name](https://github.com/username/repo_name)
