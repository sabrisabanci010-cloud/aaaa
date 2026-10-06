# Dosya 9/9: Behlül Kataş, "How to Write an Equity Research Report" (CFA Society Istanbul, 31 Ekim 2020)

Yapı Kredi Invest kıdemli analisti. 11 slayt. Bilgilendirme sunumu, puanlamıyorum.

**Düzeltme:** Önceki mesajlarımda bu sunumu "İşyar'ın (Dosya 2) kardeşi, neredeyse kopyası" diye yazmıştım. Yanlıştı. Başlık ve puan tablosu aynı, ama içerik tamamen farklı: İşyar raporun iskeletini anlatıyor, Kataş **yalnızca Valuation ve Financial Analysis** bölümlerini anlatıyor ve doğrudan DCF, WACC ve finansal analiz kontrol listesi veriyor. Slayt metni Logo'ya göre yazılmış (CCI ve Logo örnekleri), ama kuralların çoğu her şirkete uygulanıyor. Bu yüzden bu dosya bizim için Dosya 2'den çok daha uygulanabilir.

---

## 1. Bu dosyadan öğrenmen gerekenler

**Değerleme için kurallar**

1. **Yöntemi neden seçtiğini yaz** (DCF mi, emsal mi). Emsal karşılaştırması her zaman iyi bir yaklaşım değil: farklı şirket beklentileri, ülke riskleri ve analist tahmini eksikliği yüzünden.
2. **Rakamlarını defalarca kontrol et.** "Nakit akışlarını doğru iskonto ettin mi?" ve en sert cümle: **"Any mistake in numbers may cost you the whole section (and probably the competition)."** Yani değerlemedeki tek bir sayısal hata bölümün tamamını (20 puan) ve yarışmayı götürebilir.
3. **DCF tablosunu Valuation bölümünde göster, appendix'te değil.**
4. **Danışmanlarınla (özellikle sektör danışmanları) sürekli iletişimde ol.**
5. **Değerleme bölümü kısa bir açılışla başlasın:** yöntem, hedef fiyat, tavsiye, getiri potansiyeli. Sunumun örnekleri: "DCF yaklaşımıyla Coca-Cola İçecek için hedef özsermaye değeri 8,4 milyar TL, hisse başı 33,1 TL. **Sınırlı %10 getiri potansiyeli nedeniyle HOLD veriyoruz.**" ve "DCF ile 2.850 milyon TL özsermaye değeri, hisse başı 8,50 TL, **%37 yükseliş potansiyeli**."

**DCF varsayımları: her biri için "neden" ve "nasıl"**

| Varsayım | Kural |
|---|---|
| Gelir | Tahmin dönemi için CAGR nedir ve neden? |
| FAVÖK | Marj genişleyecek mi, sabit mi, neden? |
| Capex | Önemli yatırım ihtiyacı var mı? Logo'da aktifleştirilen Ar-Ge'yi capex olarak nakit akışından düş. |
| Vergi oranı | Teşvikler önemli. Şirket yetkililerinden beklenen efektif vergi oranını öğren. |
| İşletme sermayesi | Operasyon büyürken işletme sermayesi artar. Tutarlı ol. İyileşme bekliyorsan nedenini yaz. |
| Terminal büyüme | Makul bir temele otur. **"Bir şirket sonsuza kadar GSYH'den hızlı büyüyemez."** |

**WACC varsayımları**

1. **Betayı kendin hesapla.** Borçluluk düşükse borçsuz (unlevered) beta kullanılabilir.
2. **Risksiz oran:** 10 yıllık Türk devlet tahvilinin güncel faizi.
3. **Risk primi:** Damodaran'ın yaklaşımına bak.
4. **Borç maliyeti:** dipnotlardan türet, stabil mi, artacak mı, azalacak mı karar ver. **"Cost of debt > risk free."**
5. **D/(D+E):** her yıl farklıysa WACC de buna göre yıldan yıla değişir.

**Duyarlılık analizi:** zorunlu. Valuation bölümünde bir iki cümle, tablo appendix'te. WACC değişimi ve bir iki temel operasyonel varsayım (terminal büyüme, satış büyümesi) için.

**Finansal analiz kontrol listesi**
- **Satış:** segment, müşteri, ihracat/yurt içi, para birimi kırılımı; büyüme sürücüleri; beklenen büyüme.
- **Kârlılık:** sürücüler, marj ve FAVÖK trendi, **EPS büyümesi**, marj grafikleri.
- **Kaldıraç:** net borç/FAVÖK, **faiz karşılama oranı**; 3–5 yıl sonra nereye gidiyor; serbest nakit akışı kaldıracı düşürmeye yeter mi; finansal giderler.
- **Döviz pozisyonu:** TL değer kaybı sıcak bir konu, şirketin **önemli bir döviz açık pozisyonu** var mı? Varsa döviz kaybı ya da kazancı tahminini titizlikle hesapla.
- **Temettü:** yakın ve uzun vadeli beklenti. Verim %6–7'nin üstündeyse rapora yaz.
- **Ar-Ge teşvikleri, vergi avantajları, aktifleştirilen Ar-Ge.**
- **Tablo:** büyüme oranları (satış, FAVÖK, net kâr) ve kârlılık oranları (brüt, EBIT, FAVÖK, net marj).
- **ROE ve ROIC grafiği (geçmiş ve tahmin).** ROIC'i WACC ile karşılaştır: **ROIC > WACC ise şirket değer yaratıyor.** ROIC = EBIT × (1 − vergi) / (özsermaye + borç − nakit).

**İşyar ile farklar:** İşyar raporun sırası, ön sayfa, Investment Summary, Industry, Risks ve genel üslubu anlatıyor (Dosya 2). Kataş yalnızca Valuation (açılış cümlesi, DCF varsayımları, WACC, duyarlılık) ve Financial Analysis'e iniyor. İkisi çelişmiyor, tamamlıyor. Ortak olan yalnızca puan tablosu (2020: ESG 5, Industry 15, Summary 20, Valuation 20, Financial 20, Risk 15, Business 5).

---

## 2. Bizim BRSAN raporunda yapacaklarımız

Her kuralı BRSAN'a (`BRSAN_Report_Final_20pages_v5.pdf`, `BRSAN_29.xlsx`) karşı sınadım. Sayılar yeniden hesaplanmış, KAP ile karşılaştırılmadı.

### 2.1 Kural kural durum

| Kataş kuralı | BRSAN'da | Durum |
|---|---|---|
| Yöntem seçimini gerekçelendir | "Peers primary, DCF cross-check", neden yazılı (üç DCF, geniş aralık, hedefte ağırlık sıfır) | ✓ |
| Emsalin sınırlarını açıkla (ülke riski, analist tahmini yokluğu) | Emsal seti (Tenaris, Vallourec, Jindal, Maharashtra + Ereğli) açıklanıyor; ülke riski notu Excel'de var, raporda kısa | Kısmen |
| Rakamlar tutarlı (Kataş: tek hata bölümü götürür) | Dosya 1–8'de bulunan açık işler (aşağıda 2.3) | **Kısmen** |
| DCF tablosu Valuation'da, appendix'te değil | DCF özeti ve ayarları ana metinde (Figure 39–44), UFCF tablosu ve kurulum Appendix I'de | **Kısmen** |
| Valuation, açılış cümlesi: yöntem + hedef + tavsiye + getiri | "Valuation, risks and ESG in brief" paragrafı var ✓ ama hedefin "bugünkü değer" olduğu yazılı, 12 ay getiri yok | Kısmen |
| Gelir CAGR'ı ve nedeni | 2027F %20'nin nedeni yok (Dosya 2) | ✗ |
| FAVÖK marjı neden genişliyor | Baz %9,5 → %10, ilk taslak %8,0'dan yükseltildi, nedeni yazılı (H1 %8,9) | ✓ |
| Capex | %5,5 → %3,5, JCO hattı notu | ✓ |
| Vergi oranı | %28 → %25 yazılı | ✓ |
| İşletme sermayesi büyümeyle tutarlı | DSO 45, DIO 100, DPO 45 sabit, NWC gelirle büyüyor | ✓ |
| Terminal büyüme makul | Reel %4, USD %4 (nominal GSYH altında) | ✓ |
| Beta kendin | 0,89 (BIST-100'e karşı gözlenen, ilk taslaktaki 1,27 düzeltildi) | ✓ |
| Risksiz oran güncel 10 yıllık tahvil | %32,64 (TL 10 yıllık) | ✓ |
| Risk primi Damodaran | 4,23 olgun + 4,66 ülke (Damodaran Ocak 2026) | ✓ |
| **Borç maliyeti > risksiz oran** | **Nominal Kd %11,0, Rf %32,64** | **✗** |
| **D/(D+E) yıl yıl** | **Ağırlıklar sabit (%84,5 / %15,5)**, oysa net borç/FAVÖK 0,95'ten 2033F'de −0,57'ye (net nakit) iniyor | **✗** |
| Duyarlılık analizi | Var (Figure 45 senaryolar, Figure 48 WACC × büyüme), ama Figure 48'in değerleri Excel'de yok (Dosya 2) | Kısmen |
| Satış kırılımı (segment, müşteri, ihracat, para birimi) | Segment, bölge ✓; müşteri kırılımı yok (yalnızca otomotiv müşteri adları) | Kısmen |
| EPS büyümesi | **Yok** | ✗ |
| Net borç/FAVÖK | ✓ (Figure 32) | ✓ |
| Faiz karşılama oranı | Yalnızca Appendix D'de, metinde yok | Kısmen |
| Serbest nakit akışı kaldıracı düşürür mü | "Deleveraging is an EBITDA-recovery effect" ✓ yazılı; modelde UFCF 2026–27'de negatif | ✓ |
| **Döviz pozisyonu** | **Yok.** Fonksiyonel para birimi USD ve gelirin %89'u yurt dışı yazılı, ama net döviz pozisyonu ve kur farkı tahmini yok | **✗** |
| Temettü | Temettü yok (2022'den beri), verim %0; risklerde yazılı | ✓ |
| Büyüme ve kârlılık tablosu | Appendix D'de | ✓ |
| **ROE ve ROIC grafiği, ROIC vs WACC** | ROIC senaryo grafiği var (Figure 28), **WACC ile karşılaştırma yok** | **✗** |

### 2.2 Bu dosyadan çıkan yeni bulgular

**(a) ROIC tablosunda bir sayısal hata (Kataş: "tek hata bölümü götürür").** Raporun Appendix D'sinde 2024 için "Effective Tax Rate **−259,0%**", NOPAT 6.136.938 ve **ROIC %15,3** yazıyor. 2024'te FAVÖK marjı %5,7'ye çökmüştü (operating profit 1,71 milyar TL), ROIC 2023'ten (%14,9) yüksek olamaz. Hata Excel'deki NOPAT formülünden: NOPAT = operating profit × (1 − efektif vergi), efektif vergi = (vergi öncesi kâr − net kâr) / vergi öncesi kâr. 2024'te vergi öncesi kâr negatif (−63 milyon TL) ve net kâr daha da negatif (−228 milyon TL): oran −2,59 çıkıyor, (1 − (−2,59)) = 3,59 ile çarpılınca NOPAT operating profit'in 3,6 katı oluyor. Yasal vergi %25 ile yeniden hesap (benim hesabım):

| Yıl | Raporda ROIC | %25 vergiyle |
|---|---|---|
| 2021 | %3,6 | %2,4 |
| 2022 | %9,5 | %9,3 |
| 2023 | %14,9 | %13,5 |
| **2024** | **%15,3** | **%3,2** |
| 2025 | %4,3 | %5,1 |

Yani 2024'ün ROIC'i yaklaşık %3,2, rapordaki %15,3'ün beşte biri. Bu, "marj çöktü ama ROIC yükseldi" gibi okunabilecek bir sayı. ROIC senaryo grafiği (Figure 28) tahmin sütunlarını kullanıyor, bu hatadan etkilenmiyor ama tablonun geçmiş sütunu yanlış.

**(b) H1 2026 sütunu yıllıklandırılmamış.** Excel başlığı "2026-06 (Annualized*)" diyor, ama NOPAT 1,857 milyar TL (H1 EBIT × (1 − %29,3)), yani altı aylık. Aynı sütundaki ROE %4,1, ROA %1,8, ROIC %3,7, aktif devir hızı 0,45x de altı aylık (net kâr 1,797 milyar TL / özsermaye 43,4 milyar TL = %4,1). Yıllıklandırılırsa ROE yaklaşık %8,3, ROIC yaklaşık %7,3, aktif devir hızı yaklaşık 0,90x. Net borç/FAVÖK ise doğru biçimde yıllıklandırılmış (0,95x). Aynı satırlarda yıllık ve yarım yıllık rakamlar yan yana duruyor.

**(c) ROIC vs WACC (Kataş: "ROIC > WACC ise değer yaratıyor").** Excel'deki baz tahmin ROIC'i, rapordaki reel WACC (%9,04) ve USD WACC (%11,3) ile:

| Yıl | ROIC (baz) | Reel WACC %9,04'e göre fark | USD WACC %11,3'e göre fark |
|---|---|---|---|
| 2026F | %8,9 | −0,1 puan | −2,4 |
| 2027F | %9,8 | +0,8 | −1,5 |
| 2028F | %10,8 | +1,8 | −0,5 |
| 2029F | %11,7 | +2,7 | +0,4 |
| 2030F | %12,3 | +3,3 | +1,0 |
| 2031F | %12,9 | +3,9 | +1,6 |
| 2032F | %13,6 | +4,6 | +2,3 |
| 2033F | %14,2 | +5,2 | +2,9 |

ROIC, KAP (TMS 29) rakamlarından, yani enflasyona göre düzeltilmiş reel-benzeri bir baz üzerinde hesaplanıyor. Bu yüzden asıl karşılaştırma reel WACC ile. Baz senaryoda ROIC 2026F'de reel WACC'in hemen altında (−0,1 puan), 2027F'de +0,8 puan, ve ancak 2033F'de +5,2 puana çıkıyor. USD WACC'e göre 2029F'ye kadar altında. Yani **şirket, tahmin döneminin büyük kısmında değer yaratmaktan çok sermaye maliyetini zar zor karşılıyor.** Bu, SELL tezimizin "primli çarpan, düşük kalite" ayağına sayısal destek veriyor (yatırılan sermayenin getirisi sermaye maliyetine yakın, ama piyasa 11,9x EV/FAVÖK ödüyor). Dikkat: ROIC 2024 hatası (a) geçmiş sütunu etkiliyor, tahmin sütununu etkilemiyor. Tahmin ROIC'i basitleştirilmiş bilanço rollforward'una dayanıyor (borç sabit, nakit modelden), yani model riski taşıyor (Dosya 2).

**(d) Faiz karşılama oranı (operating profit / faiz gideri)** raporun Appendix D'sinde var ama metinde yok:

| 2021 | 2022 | 2023 | 2024 | 2025 | H1 2026 | 2026F |
|---|---|---|---|---|---|---|
| 1,03x | 2,34x | 3,59x | **0,83x** | 2,19x | 6,42x | 4,47x |

2024'te faiz karşılama 1'in altında (operating profit faiz giderini karşılamadı). H1 2026'da 6,4x'e çıktı. Bu, Kataş'ın "kaldıraç" maddesinin cevabı ve Financial Analysis'teki "deleveraging" paragrafına bir cümleyle girmeli: "Interest coverage was 0.8x in 2024 and 6.4x in H1 2026."

**(e) EPS büyümesi:** 2025A EPS 8,97 TL → 2026F 23,12 TL (**+%158**) → 2027F 28,65 TL (+%24). Net kâr 2026F'de 1,27'den 3,28 milyar TL'ye (+%158). Metinde EPS büyümesi yok, ön sayfaya ve Financial Analysis'e eklenmeli. (+%158 büyük bir sıçrama: 2025A net kârı düşük baz ve 2026F marjı %9,5'e çıkış. Okuyucuya "düşük bazdan" notu gerekir.)

**(f) WACC ağırlıkları sabit, kaldıraç düşüyor.** Kataş: "D/(D+E) farklıysa WACC de yıldan yıla değişir." BRSAN'da WACC ağırlıkları Q2 2026 piyasa değerinden sabit (borç %15,5), oysa modelin kendi bilançosunda net borç/FAVÖK 0,95'ten 2033F'de −0,57'ye (net nakit) iniyor. Nominal WACC hedefte kullanılmıyor (çapraz kontrol) ve DCF zaten "n/m", ama yöntemsel tutarsızlık orada. Bunu bir cümleyle ("capital structure held constant") açıklamak yeterli.

**(g) Borç maliyeti > risksiz oran.** `WACC` sayfası: nominal Kd %11,0 (finansman gideri 1,40 / ortalama borç 12,76 milyar TL), Rf %32,64: Kataş'ın açık kuralına ("Cost of debt > risk free") ters ve Mavi'deki (Dosya 3) hatayla aynı desen. Açıklaması muhtemelen borcun çoğunun döviz cinsinden olması (USD/EUR %11), ama TL nominal WACC'e girince para birimi tutarsız. Düzeltme: nominal TL WACC'de TL borç maliyetini kullan (ya da borç ağırlığını USD WACC'e bırak).

**(h) Döviz pozisyonu.** Kataş TL değer kaybı bağlamında net döviz açık pozisyonunu sorgulamamızı istiyor. BRSAN'ın fonksiyonel para birimi USD, gelirin %89'u yurt dışı. Bilançodaki finansal borcun para birimi dağılımı ve net döviz pozisyonu raporda yok. Finansman gideri modelde gelirin sabit %1,5'i (2026F: 1,31 milyar TL), H1 2026 gerçekleşen yaklaşık %0,9 (Figure 30). **Doğrulanamadı:** net döviz pozisyonu. Şirkete sorulacak soru (Dosya 5 listesine ekle): "Finansal borç ve nakdin para birimi dağılımı nedir? Net döviz pozisyonunuz ne? TL'nin değer kaybı finansman giderinizi nasıl etkiliyor?"

### 2.3 "Tek hata bölümü götürür": 9 dosyadan toplanan açık sayısal işler

Kataş bu uyarıyı özellikle yapıyor. Dosya 1–8'de BRSAN raporu ve modelinde bulduğumuz, düzeltilmesi gereken sayısal ya da etiket sorunları (öncelik sırasıyla):

1. **Hedef fiyat tanımı:** 519 TL "target price", "value estimate", "present-value estimate"; 12 aylık karşılığı 708–715 TL (Dosya 2, 6, 8).
2. **ROIC 2024 hatası** (%15,3 yerine yaklaşık %3,2) ve **H1 2026 yıllıklandırma** (bu dosya).
3. **"SELL orta noktada başlar" cümlesi** (kendi tablomuz orta noktayı HOLD yapıyor) (Dosya 1).
4. **Risk senaryo değerleri (498, 566, 638, 418, 372) ve Figure 47, 48 Excel'de yok** (Dosya 1, 2).
5. **Nominal Kd < Rf** (bu dosya, Dosya 3).
6. **TL/USD modelleri arası kur tutarsızlığı** (TL modeli yılda yalnızca %6–7 değer kaybı ima ediyor, enflasyon %28) (Dosya 2).
7. **Tahmin bilançosunda dengeleyici kalem** (2033F'de 12,5 milyar TL) (Dosya 2).
8. **Bayat Excel notları:** `Peers` A35, A18, A14; `WACC` A58; `Sensitivity` A11 (Dosya 1, 3).
9. **Bear USD DCF'te işletme sermayesi artefaktı** (bear 219 ≈ baz 230) (Dosya 1).
10. **KAP'tan doğrulanacak:** geri alınan pay ve azınlık payı (Dosya 4, 6, 8), kira yükümlülüğü ve IFRS 16 tabanı (Dosya 3, 7), hisse sayısı.
11. **Risk #1'de %9,2 vs %8,9** (şirket USD marjı / KAP TL marjı) etiketi (Dosya 1).
12. **Taslak ve iç not işaretleri:** 7 "the team" cümlesi, 5 doğrulama işareti, Appendix J başlığında "(draft)" (Dosya 2).

---

## 3. Hocaya sorulacak 3 soru

1. Valuation bölümünde DCF tablosunun tam hâli ana metinde mi olmalı? 10 sayfada neyden vazgeçeriz?
2. Nominal TL WACC'de borç maliyetini risksiz oranın altında bırakmak (döviz borcu nedeniyle) kabul edilir mi, yoksa TL borç maliyeti mi kullanılmalı?
3. ROIC'i hangi baz ile (KAP/TMS 29 reel-benzeri mi, USD mi) hangi WACC ile karşılaştırmalıyız?
