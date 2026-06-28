# Kod Yazma Aracı (Code Writing Tool)

## 📋 Genel Bakış

Bu proje, geliştiricilere kod yazma süreçlerinde yardımcı olmak için tasarlanmış bir araçtır. Modern yazılım geliştirme pratiklerini destekleyerek, kod kalitesini artırmayı ve geliştirme süresini kısaltmayı hedefler.

## 🎯 Özellikler

- **Akıllı Kod Tamamlama**: Bağlam aware kod önerileri
- **Çoklu Dil Desteği**: Python, JavaScript, TypeScript, Java, C++, Go ve daha fazlası
- **Kod Analizi**: Statik analiz ve best practice kontrolleri
- **Otomatik Refactoring**: Kod iyileştirme önerileri
- **Test Üretimi**: Birim test otomasyonu
- **Dokümantasyon**: Otomatik docstring ve comment generation

## 🚀 Kurulum

```bash
# Repository'yi klonlayın
git clone <repository-url>
cd kod_yazma_araci

# Bağımlılıkları yükleyin
pip install -r requirements.txt

# Aracı yapılandırın
cp config.example.yaml config.yaml
```

## 📖 Kullanım

### Temel Kullanım

```bash
# Kod yazma modu
python main.py write --file example.py --prompt "Bir REST API endpoint'i oluştur"

# Kod analizi
python main.py analyze --file example.py

# Test üretimi
python main.py test --file example.py
```

### Konfigürasyon

`config.yaml` dosyasını düzenleyerek:
- Desteklenen programlama dilleri
- Kod stil tercihleri
- AI model ayarları
- Çıktı formatları

yapılandırılabilir.

## 🏗️ Proje Yapısı

```
kod_yazma_araci/
├── src/                    # Ana kaynak kodları
│   ├── core/              # Çekirdek mantık
│   ├── generators/        # Kod üretim motorları
│   ├── analyzers/         # Kod analiz araçları
│   └── utils/             # Yardımcı fonksiyonlar
├── tests/                 # Test dosyaları
├── docs/                  # Dokümantasyon
├── examples/              # Örnek kullanımlar
├── config.yaml            # Yapılandırma dosyası
├── progress.md            # Geliştirme ilerleme durumu
├── cloude.md              # Cloud entegrasyon notları
└── .cloudeignore          # Cloud sync için ignore dosyası
```

## 🔧 Geliştirme

### Gereksinimler

- Python 3.8+
- Node.js 16+ (opsiyonel, web arayüzü için)

### Test Çalıştırma

```bash
# Birim testler
pytest tests/unit

# Entegrasyon testleri
pytest tests/integration

# Kod coverage
pytest --cov=src tests/
```

## 📄 Lisans

MIT License - detaylar için [LICENSE](LICENSE) dosyasına bakınız.

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Commit yapın (`git commit -m 'Add amazing feature'`)
4. Push edin (`git push origin feature/amazing-feature`)
5. Pull Request açın

## 📞 İletişim

- Issue tracker: GitHub Issues
- Email: info@kodyazmaaraci.com

## 🙏 Teşekkürler

Bu proje aşağıdaki açık kaynak projelerden ilham almıştır:
- [GitHub Copilot](https://github.com/features/copilot)
- [Tabnine](https://www.tabnine.com/)
- [Amazon CodeWhisperer](https://aws.amazon.com/codewhisperer/)
- [Sourcegraph Cody](https://sourcegraph.com/cody)

---

**Not**: Bu proje aktif geliştirme aşamasındadır.