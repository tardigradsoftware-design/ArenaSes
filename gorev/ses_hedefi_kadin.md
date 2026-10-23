# Ses Hedefi — Genç Türk Kadın Influencer

## Amaç

Sosyal medya içeriklerinde kullanılabilecek, genç bir Türk kadın influencer karakterine sahip doğal bir yapay zekâ sesi bulmak.

## Hedef ses karakteri

- **Cinsiyet:** Kadın
- **Dil:** Türkçe (Türkiye Türkçesi, İstanbul ağzı)
- **Yaş algısı:** 20–27 yaşlarında genç bir kadın
- **Ses karakteri:** Genç, canlı, doğal, yumuşak ve hafif ince tınılı
- **Enerji:** Dinamik, pozitif, dikkat çekici ve samimi
- **Konuşma tarzı:** Sosyal medyada takipçileriyle konuşan gerçek bir kadın influencer gibi
- **Doğallık:** Yapay, mekanik, aşırı resmi veya klasik haber spikeri gibi olmamalı
- **Telaffuz:** Net, akıcı ve doğal Türkçe
- **Duygusal etki:** Merak uyandıran, sıcak ve dinlemeye devam etme isteği oluşturan bir karakter

## Uygulama stratejisi

Sistemde pitch, speed, ton veya ses inceliği parametreleri bulunmuyor. Olmayan parametreleri kullanmaya çalışma, desteklenmeyen özelliklerin değiştirildiğini iddia etme.

1. `gender=feminine` kullan.
2. `use_case`: önce `conversational`, ardından `entertainment`, sonra `narration` dene.
3. `language=tr`.
4. `index` değiştirerek farklı adaylar üret.
5. Her aday için aynı test metnini kullan.
6. Her adayın ses ID'sini, ayarlarını ve sonucunu kaydet; denenenleri tekrar üretme.
7. Değerlendirmede gençlik hissi, doğallık, hafif ince tını, enerji, samimiyet, Türkçe telaffuz ve dinleme rahatlığını ayrı ayrı puanla.
8. Yalnızca gerçekten dinleyerek veya ses örneklerini analiz ederek doğrulayabildiğin özellikler hakkında kesin değerlendirme yap.

## Test metni

> Arkadaşlar, size bugün gerçekten çok güzel bir şey göstereceğim! İlk gördüğümde açıkçası bu kadar beğeneceğimi düşünmemiştim. Ama detaylarına baktıkça fikrim tamamen değişti. Özellikle son kısmına dikkat edin, çünkü bence en güzel detay orada!

Metnin kendisini değiştirerek ses karakterini değerlendirmeyi zorlaştırma.

## Sonuç raporu

Her aday için: aday numarası, ses ID'si, kullanılan `gender`/`use_case`/`language`/`index`, doğallık puanı, genç kadın influencer uygunluk puanı, tını uygunluğu, Türkçe telaffuz kalitesi, genel değerlendirme.

Öncelik: en yüksek puanlı ilk üç adayı belirlemek. Gerçek ses örnekleri dinlenemiyorsa bunu açıkça belirt; yalnızca parametrelerden hareketle sesin nasıl duyulduğunu kesin olarak söyleme.

Hedef: en iyi ve tekrar kullanılabilir genç Türk kadın influencer sesini bulmak.
