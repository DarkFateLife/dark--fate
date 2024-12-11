# Eliza 🤖

<div align="center">
  <img src="./docs/static/img/darkfate_banner.jpg" alt="Eliza Banner" width="100%" />
</div>

<div align="center">
  
  📖 [Dokümantasyon](https://DarkFateLife.github.io/darkfate/) | 🎯 [Örnekler](https://github.com/thejoven/awesome-darkfate)
  
</div>

## ✨ Özellikler

-   🛠️ Tam donanımlı Discord, Twitter ve Telegram bağlantıları
-   🔗 Tüm modeller için destek (Llama, Grok, OpenAI, Anthropic, vb.)
-   👥 Çoklu-ajan ve oda desteği
-   📚 Belgelerinizi kolayca içe aktarın ve etkileşime geçin
-   💾 Geri çağrılabilir hafıza ve belge deposu
-   🚀 Yüksek düzeyde genişletilebilir - kendi eylemlerinizi ve istemcilerinizi oluşturun
-   ☁️ Birçok modeli destekler (yerel Llama, OpenAI, Anthropic, Groq, vb.)
-   📦 Hemen çalışır!

## 🎯 Kullanım Alanları

-   🤖 Sohbet Botları
-   🕵️ Otonom Ajanlar
-   📈 İş Süreçleri Yönetimi
-   🎮 Video Oyun NPC'leri (Oyuncu Olmayan Karakter)
-   🧠 Alım Satım

## 🚀 Hızlı Başlangıç

### Gereksinimler

-   [Python 2.7+](https://www.python.org/downloads/)
-   [Node.js 23+](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
-   [pnpm](https://pnpm.io/installation)

> **Windows Kullanıcıları İçin Not:** WSL gereklidir

### .env Dosyasını Düzenleyin

.env.example dosyasını .env olarak kopyalayın ve uygun değerleri doldurun

```
cp .env.example .env
```

### Karakter Dosyasını Düzenleyin

1. Varsayılan karakteri değiştirmek için `src/core/defaultCharacter.ts` dosyasını açın

2. Özel karakterleri yüklemek için:
    - `pnpm start --characters="path/to/your/character.json"` komutunu kullanın
    - Birden fazla karakter dosyası aynı anda yüklenebilir

### Eliza'yı Başlatın

.env dosyasını ve karakter dosyasını ayarladıktan sonra, botu aşağıdaki komutla başlatabilirsiniz:

```bash
pnpm i
pnpm build
pnpm start

# Proje hızlı gelişiyor, projeye geri döndüğünüzde bazen projeyi temizlemeniz gerekebilir
pnpm clean
```

#### Ek Gereksinimler

Sharp'ı yüklemeniz gerekebilir. Başlatma sırasında bir hata görürseniz, aşağıdaki komutla yüklemeyi deneyin:

```
pnpm install --include=optional sharp
```

### Topluluk ve İletişim

-   [GitHub Issues](https://github.com/DarkFateLife/darkfate/issues). Buna uygundur: Eliza kullanırken karşılaştığınız hatalar ve özellik önerileri.
-   [Discord](https://discord.gg/DarkFateLife). Buna uygundur: Uygulamalarınızı paylaşmak ve toplulukla vakit geçirmek.

## Katkıda Bulunanlar

<a href="https://github.com/DarkFateLife/darkfate/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=DarkFateLife/darkfate" />
</a>

## Yıldız Geçmişi

[![Star History Chart](https://api.star-history.com/svg?repos=DarkFateLife/darkfate&type=Date)](https://star-history.com/#DarkFateLife/darkfate&Date)