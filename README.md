# EndCodeHackathon
# StudentManager Projesi

Bu proje, ICP Testnet üzerinde çalışan bir öğrenci yönetim sistemi oluşturmayı amaçlamaktadır. Proje, öğrencilerin puanlarını yönetmek ve öğrenci bilgilerini tutmak için akıllı sözleşme fonksiyonları içerir.

## Proje Fonksiyonları
- **addStudent**: Yeni bir öğrenci ekler.
- **addPoints**: Mevcut bir öğrencinin puanını artırır.
- **subtractPoints**: Mevcut bir öğrencinin puanını azaltır.
- **getStudentInfo**: Belirli bir öğrencinin bilgilerini getirir.

## Kullanılan Teknolojiler
- **Motoko**: Akıllı sözleşme dili.
- **ICP Testnet**: Internet Computer platformu üzerinde çalışır.

## Projeyi Çalıştırma

### Gerekli Adımlar:
1. Motoko Playground'a girin (https://m7sm4-2iaaa-aaaab-qabra-cai.raw.ic0.app/).
2. Yukarıdaki kodu Motoko Playground'da yeni bir proje olarak ekleyin.
3. `addStudent`, `addPoints`, `subtractPoints` gibi fonksiyonları test edin.
4. Değişiklikleri kaydedip deploy edin.

### Testler:

```bash
# Öğrenci ekleme testi
addStudent("Ali");

# Puan ekleme testi
addPoints("Ali", 10);

# Puan azaltma testi
subtractPoints("Ali", 5);

# Öğrenci bilgisi getirme testi
getStudentInfo("Ali");
