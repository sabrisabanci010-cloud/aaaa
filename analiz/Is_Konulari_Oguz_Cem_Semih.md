# BRSAN: yapılması gerekenler (Oğuz, Cem, Semih)

Model: `BRSAN_29_1.xlsx`. Rapor metni İngilizce. Sayfa sayısı kişi başına toplam, A4, min–max. Hücre adresleri sayfa adıyla birlikte verildi; rakamı Excel'deki **hücreden** al, hücre altındaki yazı notlarından değil (bazıları bayat).

---

# OĞUZ

**Teslim edeceği belgenin toplam uzunluğu: 7–11 sayfa.**

## 1) Investment Summary ve ön sayfa (15 puan)
Yapılacaklar:

- **Ön sayfanın üstüne resmi başlık alanlarını koy:** şirket adı, borsa, ticker, sektör, tavsiye (SELL), güncel fiyat ve tarihi, hedef fiyat ve % değişim. Güncel fiyat 647 TL (`WACC!B34`). Fiyat tarihini kesinleştir, her yerde aynı tarihi kullan.
- **Çarpan tablosu yap:** 2025A / 2026F / 2027F için F/K, EV/FAVÖK, EV/Satış, temettü verimi, FCF verimi. Kaynak: `Peers (Comps)` satır 14 ve 18-24, `Forecast` satır 18-25.
- **Fiyat grafiği çiz:** son 12 ay BRSAN ve BIST 100. Veri Excel'de yok, Fintables/Investing/KAP'tan indir, kaynağını yaz.
- **Piyasa verisi kutusu hazırla:** piyasa değeri (≈91,7 mlr TL, `WACC!B32`), 52 hafta aralığı, halka açıklık, yabancı payı (MKK), günlük hacim, net borç (7,39 mlr TL, `Peers (Comps)` satır 24).
- **Açılış paragrafını yaz:** ilk cümlede tavsiye, hedef fiyat, neden ve bir sayı. Neden = BRSAN 2026F EV/FAVÖK 11,9x ve F/K 28,0x, peer medyanları 9,7x ve 14,9x (`Peers (Comps)` satır 5-10, 14). Yöntem anlatarak başlama.
- **Üç ayaklı tezi yaz** (her biri 2-3 cümle, rakamlı):
  1. Fiyat peer'lerin üstünde: EV/Satış 698, EV/FAVÖK 514, F/K 345, ortalama 519 TL, fiyat 647 TL (`Peers (Comps)` satır 28-33).
  2. 2026 rehberliği (gelir 2,1-2,3 mlr USD, marj %8-10, hacim 1,15-1,25 Mt) ile bizim baz (marj %9,5) farkı (`Segment & Guidance (USD)` satır 26-30, `Forecast` satır 7-8). Hacim 2025'in (1,31 Mt) altında ama gelir artıyor: fiyat/karma etkisini açıkla.
  3. Nakit akışı zayıf: UFCF 2026F -0,65 mlr, 2027F -1,35 mlr TL (`Forecast` satır 33).
- **Hedef fiyat köprüsünü yaz** (2 cümle): peer ortalaması 519 TL ana referans, DCF'ler daha düşük (exit multiple 104, reel 166, USD 230 TL; `Enterprise Value (DCF)` satır 61-74), yani peer yöntemi SELL için muhafazakâr.
- **Katalizör paragrafı ekle (şu an yok):** çeyrek sonuçları, Section 232, Holding blok satışı, JCO hattı (2027), TCMB faiz kararları. Her birinin SELL'i destekleyip bozduğunu yaz, tarih ver.
- **"Son gelişmeler" cümlesi yaz:** H1 2026 gerçekleşen, bizim tahmin, piyasa beklentisi.
- **Tek terim kullan:** "target price". "Value estimate" ve "present-value estimate" yazma.

## 2) Industry Overview and Competitive Positioning (10 puan)
Bu bölüm bütünüyle Oğuz'da.

Yapılacaklar:

- **Kendi büyüme tahminimizi yaz** (dış kaynak cümlesini bununla değiştir): "ABD'de gaz boru hattı kapasite artışının üçte ikisinden fazlası Permian'dan geldiği için, BRSAN'ın ABD altyapı gelirinin 2026'da X%, 2027'de Y% büyüyeceğini tahmin ediyoruz". Kaynaklar: EIA, Baker Hughes sondaj sayısı, BRSAN faaliyet raporundaki sipariş defteri.
- **Büyüme sürücülerini** numaralı liste yap, her biri tek cümle ve kaynaklı.
- **Sipariş defteri çelişkisini çöz:** raporda "en az 2,6 mlr USD", SWOT'ta "yaklaşık 3,0 mlr USD" geçiyor. Birini seç, faaliyet raporu sayfasını yaz, diğer yerde düzelt.
- **İhracat düşüşünü anlat:** ihracat geliri 465 mn USD (2022) → 219 mn USD (2025) (`Segment & Guidance (USD)` satır 18-20). Büyüme ABD yerel üretimden geliyor. Çubuk grafik yap.
- **Fiyat döngüsünü anlat:** Enerji/OCTG geliri 2023'te 721 mn USD zirve, 2024'te 389 mn USD, FAVÖK marjı çöküşünü açıklıyor (`Segment & Guidance (USD)` satır 22-24).
- **Rakip tablosu yap:** BRSAN, Tenaris, Vallourec, Jindal SAW, Maharashtra Seamless, Ereğli. Sütunlar: ürün tipi, EV/Satış, EV/FAVÖK, F/K, net borç/FAVÖK (`Peers (Comps)` satır 4-14). Üç cümle yorum: BRSAN kaynaklı büyük çaplı boru ağırlıklı, en yakın emsal Jindal SAW, Ereğli düz çelik, yalnızca ülke referansı.
- **Segment paylarını yaz:** Altyapı %44, Enerji %22, Sanayi %23, Otomotiv %11 (`Segment & Guidance (USD)` satır 13-16).
- **Kapasite (1,7 Mt) ve ABD pazar payını** kamuya açık kaynaktan doğrula. Bulamazsan "not disclosed" yaz, uydurma.
- **Temizlik:** "assembler's assessment" etiketlerini kaldır, "the team's SWOT" cümlelerini "we" sesine çevir.

## 3) Industry ek veri (appendix)
- İhracat/ithalat tablosu (TÜİK), sondaj sayısı serisi, proje listesi.

## 4) Oğuz'un ayrıca teslim edeceği belgeler

- **Kanıt tablosu.** Rapordaki her rakam için satır: iddia, değer, Excel adresi veya kaynak ve sayfa.
- **Soru-cevap.** Summary için 5, Industry için 5 soru; cevaplar 2-3 cümle, rakamlı.
- **Kaynak listesi: 1 sayfa** (Harvard).
- **Excel Değişiklik Raporu.** Fiyat serisi, ön sayfa çarpanları, rehberlik satırı için Excel'de ne değişmeli.

**Oğuz toplam.**

---

# CEM

**Teslim edeceği belgenin toplam uzunluğu: 6–7 sayfa.**

## 1) Investment Risks (15 puan)
SELL'de riskler yukarı yönlüdür (hisse yükselirse neden?). Bunu ilk cümlede söyle.

Yapılacaklar:

- **Faiz indirimi riskini ekle (şu an raporda yok):** politika faizi yaklaşık %37, 10 yıllık tahvil %32,6 (`WACC!B5`). Piyasa indirimi fiyatlıyor, SELL gerekçemiz yüksek faize dayanıyor. 500 baz puan indirimin (WACC %32,1 → %27,1) hedef fiyata etkisini `Sensitivity` satır 6-10'dan oku, Valuation'dan doğrulat.
- **Marj riskini yaz:** `Forecast` satır 49-54: gelir büyümesi %22,5'te marj %8 → net kâr 2,33 mlr, %9 → 2,96 mlr, %10 → 3,59 mlr TL. Çarpan bazlı hedef etkisi (±1 puan marj ≈ ±42 TL) Valuation'dan doğrulanacak.
- **Peer çarpanı riskini yaz:** peer çarpanları %5,5 artarsa hedef 550 TL (HOLD eşiği), %23 artarsa fiyata eşit; Ereğli'siz değer 481 TL. Hepsi Valuation'dan doğrulanacak.
- **Hammadde riski:** sıcak haddelenmiş bobin satışların %83-93'ü.
- **Section 232 / ABD tarife riski:** kamuya açık kaynakla.
- **Kur riski:** şirket USD raporluyor, model TL (`Enterprise Value (DCF - Real)` satır 11, enflasyon %28/15/9/6).
- **Sipariş defteri / proje gecikmesi riski.**
- **Risk matrisi yap:** satırlar risk; sütunlar yön (hisse için yukarı/aşağı), olasılık (düşük/orta/yüksek), hedef fiyata etkisi (TL ve %), izleme göstergesi ve tarihi. En az 6 satır.
- **Küçük duyarlılık tablosu koy:** `Forecast` satır 49-54'ten 3×3 (marj 8/9,5/10 × büyüme 12,5/22,5/32,5).
- **"Tezi güçlendiren riskler" paragrafı yaz:** bunlar SELL için ek koruma, risk listesine karıştırma.
- **Etiketi düzelt:** Risk #1'de %9,2 (şirket USD marjı) ve %8,9 (KAP TL marjı) iki farklı rakam, hangisinin ne olduğunu yaz.
- **İzleme takvimi ekle** (4-5 satır): gösterge, tarih, yön (TCMB toplantıları, çeyrek sonuç tarihleri, Section 232 kararı).
- **Yapma:** beş ayrı mini şekil koyma, "may/could" ile risk anlatma (olasılık ve TL etkisini yaz).

## 2) Risk matrisi ve bear/bull senaryolar (appendix)
- Ayrıntılı risk matrisi (12-15 satır).
- Bear/bull tablosu (`Forecast` satır 86-117): bear = büyüme -10 puan ve marj -2 puan, bull = +10 / +2. Gelir, FAVÖK, UFCF ve değer.

## 3) Cem'in ayrıca teslim edeceği belgeler

- **Kanıt tablosu.**
- **Soru-cevap.** 5 soru: "Sizi en çok ne yanıltır?", "Faiz inerse hedefiniz ne olur?", "Section 232 kalkarsa?", "Marj %10 olursa?", "Hangi riski göz ardı ettiniz?"
- **Kaynak listesi.**
- **Excel Değişiklik Raporu.** Senaryo ve risk duyarlılığı için Excel'de eksik hücreler.

**Cem toplam.**

---

# SEMİH

**Teslim edeceği belgenin toplam uzunluğu: 11–15 sayfa.**

## 1) ESG (15 puan)
Yapılacaklar:

- **ESG'yi değere bağla (en büyük açık):** 1x EV/FAVÖK farkı hisse başına yaklaşık 58,7 TL (üç yöntem ortalamasında yaklaşık 19,6 TL). Hücreyi Valuation'dan iste. Sonuç cümlesi: ya "ESG iskontosu uygulamıyoruz, çünkü …" ya da bir iskonto uygula; gerekçeyi rakamla yaz.
- **Önemlilik tablosu yap (3 satır):** risk, ufuk, etki, yanıt.
  - CBAM: ihracat geliri 219 mn USD, gelirin ≈%12'si (`Segment & Guidance (USD)` satır 20 ÷ satır 9). CBAM'a tabi ürün payını faaliyet raporundan doğrula. Önceki taslaktaki "≈%9 / 7,9 mlr TL" rakamının kaynağını bul, bulamazsan sil.
  - Section 232 / ABD ticaret politikası bağımlılığı.
  - Yönetişim: Class A hisse, 8 üyenin 5'i grup bağlantılı, komiteler.
- **Emsal tablosu yap (4-5 satır):** BRSAN, Ereğli, Tenaris, Vallourec: emisyon yoğunluğu, iş kazası oranı, bağımsız kurul üyesi oranı, Sustainalytics skoru. Bulamadığın hücreye "n/d" yaz, bu da bir bulgu.
- **Skor kartını düzelt:** "guidance credibility" yönetişim ölçütü değil, çıkarırsan ortalama 3,1'den 2,9'a iner. Sustainalytics sıralaması 80/155, tam ortada; "High" etiketi yanıltıcı, ESG BRSAN'ı sektöründen ayırmıyor. Bunu yaz.
- **Boş metrikleri doldur:** kaza oranı, çalışan devri, eğitim saati, su, atık: yalnızca kamuya açık sürdürülebilirlik raporundan; bulamazsan "not disclosed".
- **Koru:** yönetişim ağırlığı (doğru önceliklendirme).

## 2) ESG skor kartı (appendix)
- Kriter, ağırlık, puan, kaynak; tam Sustainalytics/CDP tablosu.

## 3) CFA kapak sayfası
- Appendix C şablonunu doldur. Vurgulanmış alanları doldur, logoya ve diğer kısımlara dokunma. Sonucu hocaya onaylat.

## 4) Appendix B, yapay zekâ kullanımı
- Dört kişinin AI notlarını birleştir (her kişi: nerede kullandı, nasıl doğruladı, yanlış çıkan örnek, ne öğrendi). "Team member 1-4" olarak yaz.

## 5) Kaynakça (tüm rapor)
- Herkesin kaynak listesini tek alfabetik Harvard listesinde birleştir, tekrarları sil, sayfa numarası eksik olanı geri gönder. Aynı yazar-yıl iki kaynaksa 2025a, 2025b.

## 6) Sunum iskeleti
- Slayt listesi, her slayt için süre, kim sunacak (herkes konuşmalı). Sunum puanları: Financial 20, Valuation 20, ESG 10, Presentation 20, Q&A 20, Team involvement 5, Materials 5.

## 7) Soru-cevap matrisi
- Oğuz, Cem, Semih ve benim sorularım tek tabloda: soru, cevap veren, destek verecek kişi, cevaptaki ana rakam ve Excel adresi.

## 8) Son tutarlılık raporu
- Rapordaki her rakamı Excel'e karşı kontrol et (hedef fiyat, çarpanlar, WACC, EPS, marj) ve tersini de.
- Aynı rakamın farklı biçimde yazılıp yazılmadığına, terim tutarlılığına (target price, SELL, BRSAN), sayfa toplamına bak.
- Yasak ifade tara: "the team", "draft", "TBD", `[[`.
- Bulguları `sayfa/satır | sorun | düzeltme` tablosuna yaz.

## 9) Semih'in ayrıca teslim edeceği belgeler

- **Kanıt tablosu.**
- **Soru-cevap.** ESG için 5 soru: "ESG hedef fiyatı nasıl etkiliyor?", "CBAM'ın BRSAN'a maliyeti nedir?", "Yönetişim riski nedir?", "Neden iskonto uygulamadınız?", "Skor kartınız nasıl çıktı?"
- **Excel Değişiklik Raporu.** ESG'nin değer köprüsü için Excel'de eksik hücre.

**Semih toplam.**
