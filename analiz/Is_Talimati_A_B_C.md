# BRSAN: A, B, C kişileri için iş talimatı

Kaynak model: `BRSAN_22_6_1.xlsx` (tek model, herkes bunun üzerinden yürür). Resmi puan tablosu: 2026-27 kuralları, Appendix D. Business Description'ı ben yazıyorum, Financial Analysis bende, Valuation ayrı iki kişide. Aşağıdaki kalan 55 puan üçe bölündü.

| Kişi | Bölüm | Puan | Sayfa (ana metin) |
|---|---|---|---|
| **A** | Investment Summary + ön sayfa | 15 | 1,3 |
| **A** | Industry Overview & Competitive Positioning (**bütün bölüm, bölünmez**) | 10 | 1,2 |
| **B** | Investment Risks | 15 | 1,3 |
| **B** | Excel Değişiklik Listesi'nin birleştirilmesi (aşağıda) | — | — |
| **C** | ESG | 15 | 1,0 |
| **C** | Ortak işler: CFA kapağı, Appendix B (yapay zekâ), atıf/kaynakça, sunum şablonu | — | Appendix |

**Toplam sayfa planı (ana metin 10 sayfa, kapak hariç):** Summary + ön sayfa 1,3 · Business 0,6 (ben) · Industry 1,2 · Financial 2,3 (ben) · Valuation 2,3 (2 kişi) · Risks 1,3 · ESG 1,0 = **10,0**. Resmi sınır en fazla 10 A4 sayfa ana metin + en fazla 10 A4 sayfa appendix; sınırı aşan rapor puan kaybeder. Sayfa payları kesin, taşan metin kısaltılır, Appendix'e atılmaz.

**Appendix planı (en fazla 10 sayfa):** DCF tabloları ve duyarlılık 2,5 · Financial tabloları (gelir, bilanço, nakit akışı, oranlar) 2,5 · Peer tablosu 1 · Risk matrisi ve senaryolar 1 · ESG skor kartı 1 · Industry ek veri 0,5 · Kaynakça 1 · Appendix B yapay zekâ açıklaması 0,5.

**Sayfa biçimi (tek standart, herkes aynı):** A4, kenar boşluğu 1,8 cm, Calibri 10 punto, satır aralığı tek, bölüm başlığı 12 punto kalın, paragraf arası 4 punto. Şekil/tablo yazısı 8 punto. Bir sayfada en fazla 2 şekil/tablo. Kelime sınırları: Summary ≈450, Industry ≈500, Risks ≈450, ESG ≈350 (tablolar ve şekiller dışında; sayfa payının geri kalanı onlara gidiyor). Biçimi ben son birleştirmede uygularım ama sayfa payını aşan metin kabul etmem.

---|---|---|---|
| **A** | Investment Summary + ön sayfa | 15 | ≈1,3 |
| **A** | Competitive Positioning (Industry bölümünün ikinci yarısı) | ≈5 | ≈0,6 |
| **B** | Investment Risks | 15 | ≈1,3 |
| **B** | Industry Overview (Industry bölümünün birinci yarısı) | ≈5 | ≈0,7 |
| **C** | ESG | 15 | ≈1,0 |
| **C** | Ortak işler: CFA kapağı, Appendix B (yapay zekâ), atıf/kaynakça, sunum şablonu | — | Appendix |

Sayfa payları 10 sayfalık ana metne göre. Kalan sayfalar: Financial ≈2,3, Valuation ≈2,3, Business ≈0,6.

---

## 0. Herkes için ortak kurallar (nasıl istiyorum)

1. **Dil ve ses.** Rapor metni **İngilizce**, "we" sesiyle ("we estimate", "we believe"). "The team", "assembler", "draft", "to be verified" gibi iç not ifadeleri yasak. Talimat ve notlar Türkçe olabilir, teslim edilen metin İngilizce.
2. **Her paragraf bir iddiayla açılır.** İlk cümle sonuç (bulgu), sonraki cümleler kanıt. Yöntem anlatımıyla başlama. Kötü: "We analysed the interest rate environment." İyi: "A 500 bp faster rate cut than our base case would add ≈X TL to our value, the single largest risk to the SELL."
3. **Her sayının bir adresi var.** Metindeki her rakam Excel'de bir hücreden gelecek ya da kamuya açık bir kaynaktan (sayfa numarasıyla). Metnin altında ayrı bir **Kanıt Tablosu** ver: `İddia | Değer | Excel sayfa!hücre veya kaynak + sayfa`. Kanıt tablosu olmayan teslim kabul edilmez. Kataş'ın uyarısı: tek yanlış rakam bölümü götürür.
4. **Rakamları yalnızca hücrelerden al, Excel'deki metin notlarından değil.** Bazı notlar bayat. Metinde değil hücrede olan doğru:
   - `Peers (Comps)` A35: "15,24x vs medyan 8,00x" yazıyor; hücreler BRSAN EV/FAVÖK 11,9x, medyan 9,66x gösteriyor.
   - `WACC` A44, A48 ve `Sensitivity` A11, `Enterprise Value (DCF)` A45: "WACC ≈ %38,6" yazıyor; hücre WACC'ı **%32,1** gösteriyor. `WACC` A58: "reel WACC ≈ %11,9"; hücre **%9,0**.
   - `Enterprise Value (DCF)` A41: "−4,1M → +4,8M" yazıyor; hücreler UFCF 2026F −0,65 mlr TL, 2033F +5,29 mlr TL.
   - `Forecast` A3, `Enterprise Value (DCF)` A76 gibi "team should review", "sync bug fixed" notları iç not: asla alıntılama.
5. **Excel'e dokunma.** Kimse modeli değiştirmez. Hata ya da eksik görürsen `Excel Hata Listesi` adlı ortak dosyaya yaz: `sayfa!hücre | ne yanlış | önerin`. Valuation ve Financial sahipleri düzeltir.
6. **İki aşama.** *Taslak 1 (rakam donmadan):* araştırma, tablo, niteliksel metin, rakam yerine `[TP]`, `[UPSIDE]`, `[EPS26]` gibi yer tutucular. *Taslak 2 (rakamlar donunca):* yer tutucuları doldur, kanıt tablosunu bitir. Rakam bekleyerek başlamayı geciktirme.
7. **Uzunluk.** Aşağıda her bölüm için kelime üst sınırı var, aşma. Şekil ve tablolar sayfa payının içinde. Fazla kalan tablo Appendix'e (en fazla 10 sayfa, hepsi paylaşılıyor).
8. **Şekiller.** Başlık sonucu söylesin ("Peer premium narrows only if Ereğli is excluded"), altında "Source:" satırı (Excel sayfa adı ya da kurum + yıl). Renk: tek ana renk + gri. Excel'den üret, ekran görüntüsü alma.
9. **Atıf.** Harvard: (Yazar, Yıl, s.). Kaynak listesi alfabetik. Yalnızca kamuya açık kaynak: KAP, faaliyet raporu, sürdürülebilirlik raporu, TCMB, TÜİK, EIA, CDP, Sustainalytics vb. Şirkete özel yazışma bilgisini kaynak yapma.
10. **Yapay zekâ kullandıysan** 4 cümle yaz (Appendix B için): nerede kullandın, çıktıyı nasıl doğruladın, ne yanlış çıktı, ne öğrendin. Kişi C birleştirir.
11. **Q&A (20 puan).** Her kişi kendi bölümü için **5 muhtemel jüri sorusu + 2-3 cümlelik cevap** yazar. Sunumda herkes konuşacak (Team involvement 5 puan).

**Teslim biçimi:** Google Doc ya da Word, bölüm başına tek dosya: `A_Summary.docx`, `A_Industry.docx`, `B_Risks.docx`, `C_ESG.docx`. Her dosyada sırayla: (1) rapor metni, (2) şekil/tablolar, (3) Kanıt Tablosu, (4) 5 Q&A, (5) AI notu, (6) **Excel Değişiklik Raporu** (aşağıdaki şablon). Excel Değişiklik Raporu zorunludur.

**Karar bekleyen iki şey** (ben hocaya soruyorum, siz yer tutucuyla yazın): hedef fiyat/tavsiye kuralı (şu an `Peers` ortalaması 519,29 TL, fiyat 647 TL, %−19,7) ve şirketle soru-cevap hakkı. Kural PDF'i yalnızca kamuya açık bilgiye izin veriyor; şirkete soru göndermeyin, cevap beklemeyin.

---

## KİŞİ A: Investment Summary + ön sayfa (15) ve Industry Overview & Competitive Positioning (10)

### A-1. Ön sayfa (rakamlar donunca ama şablon hemen)

Resmi kural, ilk sayfada şunları ister: şirket adı, borsa, ticker, sektör, **tavsiye**, **güncel fiyat + tarihi**, **hedef fiyat ve % değişim**. Bunların yanına ekle:

- **Çarpan tablosu**, 2025A / 2026F / 2027F: F/K, EV/FAVÖK, EV/Satış, temettü verimi, FCF verimi. Kaynak: `Peers (Comps)` satır 14 (BRSAN cari), satır 18-24 (2026F NTM: gelir 87,5 mlr, FAVÖK 8,32 mlr, net kâr 3,28 mlr, EPS 23,12 TL), `Forecast` satır 18-25.
- **Fiyat grafiği** (1 yıl, BIST100 endeksine göre) + **52 haftalık aralık**. Fiyat serisi Excel'de yok: Fintables, Investing.com ya da KAP'tan çek, kaynağını yaz. Güncel fiyat Excel'de **647 TL** (`WACC` B34, "canonical" hücre: tek kaynak). Fiyat tarihini ön sayfada yaz.
- **Piyasa değeri** (647 × 141.771.582 hisse = ≈91,7 mlr TL), halka açık oran, yabancı payı (MKK VAP). Net borç Q2 2026: 7,39 mlr TL (`Peers` satır 24).
- **Tek terim:** "target price" kullan. "Value estimate" ya da "present-value estimate" yazma.

### A-2. Investment Summary (≈450 kelime + çarpan tablosu, ön sayfayla birlikte 1,3 sayfa)

Hocaların tek ortak uyarısı: ilk cümlede tavsiye, hedef, **neden**, bir **sayı ya da katalizör**. Yapı:

1. **Açılış paragrafı (3-4 cümle).** "We initiate coverage of BRSAN with a SELL and a 12-month target price of [TP] TL, [UPSIDE]% below the 647 TL close on [DATE], because [en güçlü neden]." Neden = fiyat peer ortalamasının üstünde: BRSAN 2026F EV/FAVÖK 11,9x, global medyan 9,66x; F/K 28,0x, medyan 14,94x (`Peers` satır 14 ve 5-10).
2. **Üç ayaklı tez (numaralı, her biri 2-3 cümle + bir rakam):**
   - *Fiyat çarpanları fazla yüksek:* `Peers` satır 28-33. Üç yöntem: EV/Satış 698 TL, EV/FAVÖK 514 TL, F/K 345 TL, ortalama 519,29 TL.
   - *Beklenti vs şirket rehberliği:* 2026 rehberliği gelir 2,1-2,3 mlr USD, FAVÖK marjı %8-10, satış hacmi 1,15-1,25 Mt (2025'te 1,31 Mt). Bizim baz: marj %9,5. `Segment & Guidance (USD)` satır 26-30, `Forecast` satır 7-8. Hacim rehberliği 2025'in **altında** ama gelir +%22,5 bekleniyor: fiyat/karma etkisi. Bunu açıkça yaz, jüri sorar.
   - *Nakit akışı zayıf:* UFCF 2026F −0,65 mlr, 2027F −1,35 mlr TL; pozitife 2028F'de dönüyor (`Forecast` satır 33).
3. **Katalizör paragrafı (zorunlu, şu an raporda yok).** Tarihli liste: çeyrek sonuçları (rehberlikle karşılaştırma), Section 232 tarifelerinin akıbeti, Holding'in olası blok satışı, JCO hattı devreye alma (2027), TCMB faiz kararları. Her katalizör için "SELL'i doğrularsa / bozarsa" yön yaz.
4. **Hedef fiyat köprüsü (küçük tablo):** peer ortalaması 519 → DCF çapraz kontrolü (exit multiple 104 TL, reel DCF 166 TL, USD DCF 230 TL, nominal Gordon negatif: `Enterprise Value (DCF)` satır 61-74). Mesaj: DCF'ler peer değerinin **çok altında**, yani peer yöntemi SELL aleyhine muhafazakâr. Bunu yönetici özetinde tek cümleyle söyle.
5. **"Hedef fiyatta bile hisse nerede" cümlesi:** 519 TL'de bile hisse hâlâ medyanın üstünde mi altında mı (Valuation sahipleri rakamı verir).
6. **Son gelişmeler satırı:** H1 2026 gerçekleşen / bizim tahmin / piyasa beklentisi.

### A-3. Industry Overview & Competitive Positioning (10 puan, ≈500 kelime, 1,2 sayfa)

**Bu bölüm tek kişide (A).** Rapor sırasında Industry, Summary'den önce gelir; A önce bunu yazar çünkü rakamlara bağımlılığı az.

**Industry Overview kısmı:**

- **Kendi tahminimizi yaz** (dış kaynak cümlesi değil): "Because over two-thirds of US gas pipeline capacity additions originate in the Permian, we expect BRSAN's US infrastructure revenue to grow X% in 2026 and Y% in 2027, driven by …". Kaynakları: EIA (boru hattı kapasitesi), Baker Hughes sondaj sayısı, ABD enerji bakanlığı projeleri, BRSAN'ın faaliyet raporundaki sipariş defteri. Şu an "Grand View ~%6" gibi dış rakam cümlesi var, onu "biz tahmin ediyoruz" cümlesine çevir.
- **Büyüme sürücüleri:** numaralı liste, her biri tek cümle + kaynak.
- **Sipariş defteri çelişkisi:** raporda "en az 2,6 mlr USD", SWOT'ta "yaklaşık 3,0 mlr USD" geçiyor. Birini seç, kaynağını (faaliyet raporu sayfası) yaz, öteki yerde düzelt.
- **Türkiye boru ihracatı** (TÜİK / ilgili dernek verileri): BRSAN'ın ihracat geliri 2022'de 465 mn USD → 2025'te 219 mn USD (`Segment & Guidance` satır 18-20): Türkiye çıkışlı ihracat daralıyor, büyüme ABD yerel üretimden geliyor. Bu önemli bir bulgu, vurgula.
- **Segment dalgası:** Enerji/OCTG gelirinin 2023 zirvesi (721 mn) → 2024 çöküş (389 mn) FAVÖK marjı çöküşünü açıklıyor (`Segment & Guidance` satır 22-24). Tek paragrafta anlat: sektör fiyat döngüsü.

**Q&A (Industry):** "Büyüme tahmininiz nereden?", "ABD'de pay ne?", "Permian yavaşlarsa?", "İhracat neden düşüyor?"

**Competitive Positioning kısmı:**

"BRSAN rakiplere göre nerede" tablosu, 5-6 satır: BRSAN, Tenaris, Vallourec, Jindal SAW, Maharashtra Seamless, Ereğli. Sütunlar: ürün (dikişli/dikişsiz/kaynaklı), EV/Satış, EV/FAVÖK, F/K, Net Borç/FAVÖK, önemli not (`Peers` satır 4-14 doğrudan). Altına 3 cümle: BRSAN dikişsiz OCTG değil kaynaklı büyük çaplı boru ağırlıklı, bu yüzden en yakın emsal Jindal SAW; Tenaris'e prim gerekçesi yok; Ereğli düz çelik, yalnızca ülke çarpanı referansı (`Peers` satır 12, 41). Segment payı: Altyapı %44, Enerji/OCTG %22, Sanayi %23, Otomotiv %11 (`Segment & Guidance` satır 13-16). **Kapasite 1,7 Mt** ve **ABD pazar payı** için kamuya açık kaynak bul (faaliyet raporu s.); bulamazsan "n/a, not disclosed" yaz, uydurma.

**Q&A (Summary):** "Neden SELL, fiyat zaten düşmüş mü?", "519 TL'yi nasıl buldunuz?", "DCF neden bu kadar düşük?", "Katalizörünüz ne?", "Hedefe 12 ayda ulaşılır mı?"

---

## KİŞİ B: Investment Risks (15) ve Excel Değişiklik Raporu birleştirme

### B-1. Risks (≈450 kelime + 1 matris + 1 duyarlılık tablosu, 1,3 sayfa)

SELL tavsiyesinde riskler **yukarı yönlüdür**: yanılırsak, hisse yükselirse neden? (Sezan kuralı.) Yapı:

1. **Matris** (olasılık: düşük/orta/yüksek × etki: TL cinsinden hedef fiyat) ve her satırda: risk, SELL'e etkisi (yukarı/aşağı), hedef fiyata duyarlılık, izleme göstergesi + tarih. Sütun *"hedef fiyata etkisi"* şu kaynaklardan:
   - *Faiz indirimi riski (ekle, şu an yok):* politika faizi %37 civarı, 10 yıllık tahvil %32,6 (`WACC` B5). Her 500 bp faiz indirimi Ke ve WACC'ı düşürür: `Sensitivity` satır 6-10 (WACC × g tablosu) ve `Enterprise Value (DCF)` ile okunur. Rakamı Valuation sahiplerinden iste (WACC 32,1% → 27,1% senaryosu).
   - *Marj riski (FAVÖK marjı):* `Forecast` satır 49-54 (2026F net kâr, gelir büyümesi × FAVÖK marjı). Marj %9,5 → %8 olursa net kâr 2,33 mlr TL, %10 olursa 3,59 mlr TL (gelir büyümesi %22,5 sütunu). Çarpan bazlı hedefe etkisini Valuation'dan iste: ±1 puan marj ≈ ±42 TL (önceki analiz, doğrulansın).
   - *Peer çarpanı riski:* peer çarpanlarında %5,5 artış hedefi 550 TL'ye çıkarıyor (HOLD eşiği), %23 artış fiyata eşitliyor. Ereğli'siz değer 481 TL (Valuation doğrulasın).
   - *Senaryo (bear/bull):* `Forecast` satır 86-117. Bear = büyüme −10 puan, marj −2 puan; bull = +10/+2. Tablo olarak gösterme, bir cümleyle özetle.
   - *Section 232 / ABD tarife riski, hurda-bobin fiyatı riski (satışların %83-93'ü hammadde), kur riski (TL/USD, şirket USD raporluyor), sipariş defteri riski.* Hepsi kamuya açık kaynakla (faaliyet raporu, KAP, Federal Register).
2. **"Tezi güçlendiren riskler"** ayrı kısa paragraf: tez zaten SELL olduğu için bu riskler bizim için "ek koruma", yanlış okunmasın.
3. **Etiket tutarlılığı:** Risk #1'de FAVÖK marjı %9,2 (şirket USD) ve %8,9 (KAP TL) iki farklı rakam geçiyor; hangisinin ne olduğunu açıkça yaz.
4. **Kısa izleme takvimi** (4-5 satır, tarihli): hangi gösterge, ne zaman, hangi yöne.

**Q&A (B):** "Sizi en çok ne yanıltır?", "Faiz inerse hedefiniz ne olur?", "Section 232 kalkarsa?", "Marj %10 olursa?", "Hangi riski göz ardı ettiniz?"

---

## KİŞİ C: ESG (15) ve ortak işler

### C-1. ESG (≈350 kelime + 2 tablo, 1,0 sayfa)

Sunumda da 10 puan: aynı içerik slayta dönecek.

1. **ESG'yi değere bağla** (şu an bağlı değil, en büyük açık): "1x EV/FAVÖK farkı hisse başına ≈58,7 TL" (3 yöntem ortalamasında ≈19,6 TL; Valuation sahipleri hücreyi vermeli). Sonuç cümlesi: "We do not apply an ESG discount; governance alone would justify X." ya da bir iskonto uygula; hangisi olursa gerekçeyle yaz.
2. **Önemlilik tablosu (3 satır):** risk | ufuk | etki | yanıt.
   - CBAM: AB'ye çıkan gelirin payı; ihracat geliri 2025'te 219 mn USD (`Segment & Guidance` satır 20), toplam gelire oranı ≈%12; CBAM'a tabi çelik boru payını faaliyet raporundan doğrula. (Önceki taslaktaki "≈%9 / 7,9 mlr TL" rakamının kaynağını bul, bulamazsan sil.)
   - Section 232 / ABD ticaret politikası bağımlılığı (ABD yerel üretim).
   - Yönetişim: Class A hisse, 8 üyenin 5'i grup bağlantılı, komiteler.
3. **Emsal karşılaştırma tablosu (4-5 satır):** BRSAN, Ereğli, Tenaris, Vallourec: emisyon yoğunluğu (tCO₂/t çelik), iş kazası oranı, bağımsız yönetim kurulu üyesi oranı, Sustainalytics skoru. Hepsi kamuya açık (sürdürülebilirlik raporları, CDP). Bulamadığın hücreye "n/d" yaz.
4. **Skor kartı düzeltmesi:** "guidance credibility" bir yönetişim ölçütü değil, çıkarırsan ortalama 3,1'den 2,9'a iner. Sustainalytics sıralaması (80/155) tam ortada: "High" etiketi yanıltıcı, ESG BRSAN'ı sektöründen ayırmıyor; bunu yaz.
5. **Koru:** yönetişim ağırlığı doğru önceliklendirme.
6. **Boş kalan sosyal/çevresel metrikler** (kaza oranı, çalışan devri, eğitim saati, su, atık): yalnızca kamuya açık sürdürülebilirlik raporundan doldur; bulamazsan "not disclosed" yaz ve bunu da bulgu yap ("disclosure gap").

**Q&A (C):** "ESG hedef fiyatı nasıl etkiliyor?", "CBAM'ın BRSAN'a maliyeti?", "Yönetişim riski nedir?", "Neden iskonto uygulamadınız?", "Skor kartınız nasıl çıktı?"

### C-2. Ortak işler (Appendix ve biçim)

- **CFA kapak sayfası** (Appendix C şablonu) ve Appendix **B (yapay zekâ kullanımı)**: A ve B'nin AI notlarını, kendi notunu ve benim notumu birleştir, tek sayfa.
- **Atıf/kaynakça:** Harvard, alfabetik; tüm kişilerin kanıt tablolarındaki kaynakları tek listede topla, tekrarları sil, eksik sayfa numaralarını kişilere geri gönder.
- **Sunum şablonu:** 20 puanlık Presentation için slayt iskeleti (süre planı + kim hangi bölümü sunuyor) ve **Q&A matrisi** (A, B, C ve benim 5'er sorumuz tek tablo). Sunum puanları: Financial 20, Valuation 20, ESG 10, Presentation 20, Q&A 20, Team 5, Materials 5.
- **Son tutarlılık turu (rakamlar donunca):** raporda geçen her rakamı Excel'e karşı kontrol et ve tersini: Excel'deki ana çıktıların (hedef fiyat, çarpanlar, WACC, EPS) raporda tutarlı geçtiğini doğrula.

---

## Excel Değişiklik Raporu (A, B, C hepsi yazar; B birleştirir)

Excel'e kimse dokunmaz. Her kişi kendi bölümünü yazarken modelde **ne değişmeli** görürse yazar. Rapor ayrı iki bölümdür: **Financial (bende)** ve **Valuation (iki kişide)**. Şablon, her satır:

`Sayfa!hücre | şu an ne var | ne olmalı | neden (kaynak) | hangi rapor bölümünü etkiliyor | öncelik (1 = rakam değişir, 2 = açıklama/etiket, 3 = süs)`

Kurallar: önerini rakamla ver ("margin 9,5% → 8,0%" gibi), sadece "yanlış" yazma. Yeni veri gerekiyorsa kaynağı yaz. Emin değilsen "doğrulanmalı" diye işaretle, uydurma. **B** bu üç raporu birleştirip aynı hücre için gelen çakışan önerileri tek satıra indirir, ben ve Valuation sahipleri o listeyi uygularız.

### Önceden bildiğimiz değişiklikler (kontrol et, doğruysa raporuna yaz, eksik olanı sen ekle)

**Financial (bende):**

| Yer | Sorun / değişiklik |
|---|---|
| `Ratios (DuPont)` satır 15, 18 | 2024 efektif vergi −%259 çıkıyor ve ROIC %15,3 yazıyor; yasal vergiyle ROIC ≈ %3,2 olmalı. |
| `Ratios (DuPont)` H1 2026 sütunu | Yıllıklandırılmamış (ROE %4,1 → ≈%8,3; ROIC %3,7 → ≈%7,3). |
| `Forecast` satır 60-74 | Tahmin bilançosunda dengeleyici kalem (satır 73) 2026F ≈ 0,95 mlr TL → 2033F ≈ 12,5 mlr TL büyüyor; borç sabit (satır 67-68), temettü yok. Ya gerçek bağla (temettü, borç hareketi) ya raporda gösterme. |
| `Forecast` satır 7 | Gelir büyümesi (%22,5 / %20 / %14,4 / %11,3 …) için "neden" yok: hacim × fiyat ayrımı ekle (rehberlik hacmi 1,15-1,25 Mt, 2025'te 1,31 Mt). |
| `Forecast` satır 10 | Finansman gideri gelirin sabit %1,5'i; H1 2026 gerçekleşen ≈%0,9. Borç tutarı sabit tutulurken oran sabit mi olmalı? |
| `Forecast` / `Enterprise Value (DCF - Real)` | TL modeli yılda yalnızca ≈%6-7 TL değer kaybı ima ediyor; enflasyon varsayımı %28 / %15 / %9 / %6 (Real DCF satır 11). Kur varsayım satırı ekle ve tutarlılığı göster. |
| `Forecast` satır 2, 3, 7-15, 81 | "[DRAFT]", "AI-drafted … team should review" gibi iç etiketler kalkmalı. |
| Yeni | Çeyreklik tablo (Q1 2025 – Q2 2026), nakit dönüşümü (işletme nakit akışı / FAVÖK), faiz karşılama (2024: 0,83x; H1 2026: 6,42x), EPS büyümesi (2025A 8,97 → 2026F 23,12 TL), borç ve nakdin para birimi dağılımı (net döviz pozisyonu). |

**Valuation (iki kişide):**

| Yer | Sorun / değişiklik |
|---|---|
| Yeni blok (`Enterprise Value (DCF)` satır 56-74 altı veya yeni sayfa) | Hedef fiyat kuralı: bugünkü değer 519,29 TL, 12 aylık hedef = 519,29 × (1 + Ke %36,4) ≈ 708 TL, beklenen getiri ≈ +%9,5, tavsiye eşiği. Kural kararına göre (AK / BNP ±%10 / ±%15) SELL ya da HOLD çıkıyor. |
| `Peers (Comps)` A35, `WACC` A44, A48, A58, `Sensitivity` A11, `Enterprise Value (DCF)` A41, A45 | Bayat metin notları (yukarıda, madde 4). Hücrelerle uyumlu yeniden yaz. |
| `Peers (Comps)` satır 14, 18-24 | BRSAN cari çarpanlar Fintables TTM, hedef uygulaması 2026F NTM; emsal çarpanlarının da trailing mi forward mı olduğunu etiketle. |
| `Peers (Comps)` yeni satır | Ereğli'siz değer (≈481 TL) ve peer çarpanı ±%5,5 / ±%23 duyarlılığı; iki yönlü prim/iskonto tablosu (BRSAN global 4'e göre EV/FAVÖK +%49, F/K +%98; Ereğli'ye göre −%4 / −%19). |
| `Enterprise Value (DCF)` satır 25-28 | Net borç köprüsünde kira yükümlülüğü (IFRS 16), geri alınan pay ve azınlık payı yok. KAP'tan doğrula (kira yükümlülüğü hedefi yaklaşık −%1,3 / −6,6 TL oynatır). |
| `WACC` satır 5, 27 | Nominal Kd %11,0 < Rf %32,6; TL borç maliyeti kullan ya da gerekçeyi yaz. D/V ağırlığı sabit (%15,5) ama kaldıraç düşüyor: yıl yıl göster ya da gerekçelendir. |
| `Enterprise Value (DCF)` satır 5-32 | Nominal Gordon DCF −16 TL (negatif), exit multiple 104 TL, reel DCF 166 TL, USD DCF 230 TL: dört DCF çok dağınık. Hangisinin ana, hangisinin çapraz kontrol olduğunu ve neden 8 yıl seçildiğini yaz; negatif sonuç raporda açıklanmalı ya da çıkarılmalı. |
| `Enterprise Value (DCF - USD)` | Bull senaryosu 1.230 TL aykırı, bear'de işletme sermayesi artefaktı, stub period eksik. |
| `Sensitivity` satır 6-10 | WACC aralığı yalnızca %24-40; reel WACC ve Ke duyarlılığı yok; negatif hücreler açıklanmalı. FAVÖK marjı ±1 puan = ±42 TL (±%8,1) ve peer çarpanı +%5,5 = 550 TL cümleleri için hücre ekle. |
| Yeni `Scenarios` sayfası | Raporda geçen Figure 47 (634), Figure 48 (143-567), Figure 53'ün dört satırı için hücre yok. |
| `WACC` satır 14-15 | Beta 0,89 kaynağı ve dönemi, ERP / ülke riski kaynağı hücreye yazılmalı (kaynak yoksa jüri sorar). |

Bu tablolar başlangıç listesi: **sen bölümünü yazarken ek bulduğunu ekle.** Örneğin A, fiyat serisi ve cari çarpanlarda Excel'in neyi göstermediğini; B, risk duyarlılıkları için hangi senaryo hücrelerinin eksik olduğunu; C, ESG'nin değer köprüsü için hangi hücrenin lazım olduğunu yazar.

---

## Zamanlama (göreli günler)

| Gün | Ne |
|---|---|
| 1-3 | Taslak 1: araştırma, tablolar, yer tutuculu metin. Bölüm başı kanıt tablosu başlasın. |
| 3-5 | Rakamlar donar (Valuation + Financial). Hata Listesi kapanır. |
| 5-8 | Taslak 2: yer tutucuları doldur, kelime sınırına indir. |
| 5 | Excel Değişiklik Raporları teslim, B birleştirir; ben ve Valuation sahipleri uygular. |
| 8-10 | Çapraz okuma: herkes bir başkasının bölümünü okur; C tutarlılık turunu yapar; ben Business'ı ve son birleştirmeyi yaparım. |

Sormadan önce bu belgeyi ve Excel'deki ilgili sayfayı oku. Takıldığın yerde tahmin yürütme, Hata Listesi'ne ya da gruba yaz.
