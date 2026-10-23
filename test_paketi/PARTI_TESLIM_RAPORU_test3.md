# Parti Teslim Raporu — TEST PAKETİ (3 video)

Tarih: 2026-10-23 · Ses: **voice-10** (kadın, bu oturumdaki gerçek kimlik) · Hız: 1.0x, dönüşüm yok

| Video | Dosya | Süre | Kelime/dk | Byte | Durum |
|---|---|---|---|---|---|
| ORN_V001 | ORN_V001_ses.mp3 | 31.54 sn | 124 | 126.381 | teslim |
| ORN_V002 | ORN_V002_ses.mp3 | 32.18 sn | 117 | 128.973 | teslim |
| ORN_V003 | ORN_V003_ses.mp3 | 31.94 sn | 122 | 128.013 | teslim |

Tamamlanan: **3 / 3**. Her dosyanın yanında `*_ses_bilgisi.json` var. Format: MP3, 24 kHz, mono, 32 kbps.

## Doğrulama
- 3 metnin SHA-256 değeri paketteki beyanla **birebir eşleşti**.
- Dosyalar decode edildi; süre/örnekleme/kanal/bit hızı ölçüldü, dosya SHA-256 kaydedildi.
- Dinleme ve transkripsiyon **yapılmadı** (ses dinleme yeteneğim yok) — telaffuz/ton doğrulaması sende.

## Sorunlar
1. **Tempo**: istenen 165–175 kelime/dk, ölçülen 117–124. Sentez aracında hız parametresi yok; atempo/time-stretch uygulanmadı (talimat gereği). Metin kesilmedi.
2. **Ses karakteri**: prompt 30–40 yaş, sıcak-sakin kadın istiyor; atanmış ses voice-10 genç influencer tonunda. Değişiklik talimatı gelmediği için aynı ses korundu. İstenirse başka sesle yeniden üretilir (3 üretim daha, parti limiti 8 içinde).
3. "Ve unutma..." için yarım kalan ton ve "bunu kaydet" öncesi duraklama kontrol edilemedi.
