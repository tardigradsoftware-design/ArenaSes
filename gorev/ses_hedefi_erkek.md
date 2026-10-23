# Ses Hedefi — Genç Türk Erkek Influencer

## Amaç

Sosyal medya içeriklerinde kullanılabilecek, genç bir Türk erkek influencer karakterine sahip doğal bir yapay zekâ sesi bulmak.

## Hedef ses karakteri

- **Cinsiyet:** Erkek
- **Dil:** Türkçe (Türkiye Türkçesi, İstanbul ağzı)
- **Yaş algısı:** 20–30 yaşlarında genç bir erkek
- **Ses karakteri:** Genç, temiz, doğal, hafif tok ama aşırı kalın olmayan, anlaşılır
- **Enerji:** Dinamik, özgüvenli, pozitif ve dikkat çekici
- **Konuşma tarzı:** Takipçileriyle doğrudan konuşan samimi bir erkek influencer
- **Doğallık:** Yapay, mekanik, aşırı resmi veya klasik haber spikeri gibi olmamalı
- **Telaffuz:** Net, akıcı ve doğal Türkçe
- **Duygusal etki:** Merak uyandıran, güven veren ve dinlemeye devam etme isteği oluşturan

Aşırı kalın, yaşlı, sert, monoton veya radyo spikeri gibi olmamalı; aşırı tiz veya yapay bir ses de istenmiyor.

## Mevcut parametreler

- `gender`: feminine / masculine
- `use_case`: narration, conversational, characters, entertainment, educational, advertising
- `language`: tr
- `index`: her çağrıda yeni bir çift aday
- `text`: ifade biçimini dolaylı etkiler

Pitch, hız, ton, perde, incelik veya kalınlık parametreleri **yok**.

## Uygulama

1. `gender=masculine`
2. Önce `use_case=conversational`
3. Ardından `entertainment`, `narration`, `advertising`, `characters` karşılaştır
4. `language=tr`
5. Farklı `index` değerleriyle yeni adaylar üret
6. Her adayın ses ID'sini ve ayarlarını kaydet
7. Tüm adaylarda aynı test metnini kullan
8. Adayları gerçekten dinleyerek değerlendir; dinleme yoksa tahmin yürütme
9. En iyi üç adayı belirle ve karşılaştır

## Sabit test metni

> Arkadaşlar, bugün size gerçekten ilginç bir şey göstereceğim. İlk başta ben de bu kadar dikkatimi çekeceğini düşünmemiştim. Ama detaylarına baktıkça olayın aslında çok daha farklı olduğunu fark ettim. Sonuna kadar izleyin, çünkü en önemli kısmı henüz anlatmadım!

## Değerlendirme (100 puan)

- Genç erkek influencer karakterine uygunluk: 25
- Doğallık ve insan benzeri konuşma: 25
- Türkçe telaffuz ve akıcılık: 20
- Enerji ve dikkat çekicilik: 15
- Ses tınısının hedefe uygunluğu: 15

Puanları gerçekten değerlendirebildiğin ölçüde ver; dinleyemediğin seslere uydurma puan verme.

## Sonuç raporu

Her aday için: aday numarası, ses ID'si, `gender`, `use_case`, `language`, `index`, doğallık, influencer uygunluğu, Türkçe telaffuz, genel puan, en güçlü özellik, tespit edilen eksiklik.

En iyi üç adayı karşılaştır ve hangisinin sosyal medya içeriklerinde kullanılmaya daha uygun olduğunu açıkla.

## Kurallar

- Olmayan ses parametrelerini kullanmaya çalışma.
- `index` değerinin sesi incelttiğini veya kalınlaştırdığını varsayma.
- Metin değişikliğinin ses perdesini kesin olarak değiştireceğini iddia etme.
- Ses ID'lerini ve test sonuçlarını kaybetme.
