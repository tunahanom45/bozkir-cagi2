# Bozkır Çağı — Değişiklik Notları

## v0.14.2 — Gerçekçi nesneler, arkadaşlarla oynama kolaylığı
- **Nesneler gerçekçi oldu:**
  - **Eşyalar:** sandıklar ve variller demir çemberli, dokulu ahşap. Çuval, el arabası, silah rafı, saman okçuluk hedefi, kütük çitler, kova ve bayraklar da yenilendi.
  - **Köy:** kuyu taştan, ahşap çatılı. Tüccar tezgâhı ahşap ve kumaştan, Kor Ocağı taş örgülü ve örsü kütük üstünde. Otacı Ana'nın kazanı demirden. Yurtlar ve çadırlar keçe dokulu. At ağılının bozuk çitleri düzeltildi.
  - **Kara Bataklık:** yeşil kutu gibi duran harabeler yosunlu taş oldu. Su birikintilerinin çamurlu kıyıları ve koyu suyu var.
  - **Kemik Ovası ve Kara Han:** iskeletler kemik dokulu, moloz taşları gerçekçi.
- **Arkadaşlarla oynama:**
  - Sunucu penceresi açılınca **Tailscale adresini** (100.x.x.x) yazar; arkadaşların bu adresle bağlanır.
  - Aynı evdekiler için yerel ağ adresini de gösterir.
- **Eski model paketleri** (varlik_1-3.pck, yaklaşık 175 MB) artık açılışta silinir.

## v0.14.1 — Işınlanma sadece haritalar arası, Kemik Korusu düzeltmesi
- **Işınlanma artık sadece haritalar arasında:** Köy portalından **Gölge Diyarı** (Sv 10) ve **Kuzey Diyarı** (Sv 21) kamplarına gidilir. Kamplardaki Yolculuk Taşı'ndan köye ya da diğer haritaya dönülür. Bölgelerin içindeki dönüş taşları kaldırıldı; harita içinde yürüyerek gidilir.
- **Kemik Korusu ve Kemik Ovası:** çizgi film gibi duran mavi-gri kaya blokları gerçek kaya modelleriyle değiştirildi. Renkli çadırların yerine deri çadırlar geldi. Pembe odun yığınları gerçek kütük yığınları oldu.
- Kamp ateşlerinin taş halkaları gerçekçi taşlarla yenilendi.

## v0.14.0 — Yeni haritalar: Gölge Diyarı ve Kuzey Diyarı
- **Dünya üç haritaya bölündü:**
  - **Bozkır (ana harita):** Ötüken Köyü, Kemik Ovası, Kemik Korusu, Kara Bataklık, Kara Han Mağarası (Sv 1-10).
  - **Gölge Diyarı:** kurak, kızıl bozkır. Ortada **Gölge Kampı**, kuzeydoğuda **Yıkık Kurgan** (Sv 10-14), güneydoğuda **Kızıl Kanyon** (Sv 15-20).
  - **Kuzey Diyarı:** karlı çam ormanları ve kırağılı çayırlar. Ortada **Kuzey Kampı**, güneybatıda **Ayaz Tepeleri** (Sv 21-26), kuzeybatıda **Erlik Kapısı** (BOSS Sv 28).
- **Haritalar arası geçiş:**
  - **Köy portalı:** Yolculuk listesinden istediğin haritanın kampına ya da bölgesine ışınlanırsın.
  - **Kenar kapıları:** Bozkır'ın doğu ucundaki **Gölge Diyarı Kapısı**'na yürüyünce geçersin (Sv 10). Gölge Diyarı'nın doğu ucunda **Kuzey Diyarı Kapısı** var (Sv 21). Her kapının karşı tarafında geri dönüş kapısı da var.
- Gölge ve Kuzey Diyarı'nda ölürsen o haritanın kampında yeniden doğarsın.
- Büyük harita (M) ve mini harita bulunduğun haritayı gösterir.
- Bilge Ata'nın görev metinleri yeni yerlere göre güncellendi.

## v0.13.1 — Kaya ve kütük düzeltmesi
- Haritadaki bazı kayalarda görülen delikler/kopuk parçalar düzeltildi; bozuk büyük kaya modeli sağlam bir kaya ile değiştirildi.
- Dalı üstünde havada duruyormuş gibi görünen devrik kütükler yere tam yatan kütüklerle değiştirildi.

## v0.13.0 — Işınlanma portalı, yeni bölge görünümleri
- **Işınlanma portalı:** Köyde, Otacı Ana'nın karşısında taş bir kemer var. Yanına gidip **E**'ye bas, **Yolculuk** listesinden bölge seç. Seviyen yetmeyen bölgeler soluk görünür ("Sv 15 gerekli" gibi). İki ışınlanma arası 5 saniye bekleme var.
- **Dönüş taşları:** Her bölgenin girişinde mavi rünlü bir taş var. Buradan **Köye Dön** ya da başka bir bölgeye geç. Portal ve taşlar haritada mavi elmasla gösterilir.
- **Bölgeler yenilendi:**
  - **Yıkık Kurgan:** oyulmuş balbal taşları, taş halkalı höyükler, taş bloklu yıkık duvarlar.
  - **Kızıl Kanyon:** kızıl katmanlı yüksek kayalıklar.
  - **Ayaz Tepeleri:** kar artık göz yormuyor (mavi-gri ton, buz ve toprak lekeleri). Çamlar daha koyu yeşil.
  - **Erlik Kapısı:** yanmış ağaçlar, parlak kara obsidyen kristaller, ince lav çatlakları.
  - **Kara Han:** kayalıklarla çevrili mağara ağzı, kemikler ve kafatasları.
- **Canavarların kendi görünümleri var:** Kara Han, Gölge Avcı, Kızıl Mızrakçı, Ayaz Kamı ve Erlik Beyi'nin kendine özgü zırh, boynuz ve süsleri var. 2. bölüm canavarları daha iri.
- **Onay soruları:** Satın alma, satma ve Kor Ocağı'nda yükseltme öncesinde **Evet / Hayır** sorulur. Yükseltmede başarısızlık riski yazar: +4 ve üstünde başarısız olursa eşya bir kademe düşer.
- **Karşılaştırma:** Çantadaki bir eşyaya tıklayınca, aynı yerde kuşandığın eşya yanda açılır. İkisini yan yana karşılaştırabilirsin.

## v0.12.1 — Küçük düzeltmeler
- NPC (Tüccar, Otacı Ana, Kor Ocağı) açıkken eşyaya tıklayınca bilgi penceresi artık NPC listesinin üstüne binmez; envanterin karakter bölümünün üstüne açılır. NPC listesi ve çanta görünür kalır.
- **ESC** ile hedef seçimi kaldırılır (üstteki hedef çubuğu kapanır). Açık pencere ve hedef yoksa ESC menüsü açılır.

## v0.12.0 — 2. Bölüm: Erlik'in Gölgesi
- **Görevler Kara Han'dan sonra devam ediyor!** Kara Han'ı yendikten sonra Bilge Ata yeni bir zincir verir (Sv 10 → 28):
  - **Yıkık Kurgan (doğu, Sv 10-14):** mezar höyükleri ve balbal taşları arasında **Gölge Avcılar**. Görevler: Yıkık Kurgan, Gölge Bezi.
  - **Kızıl Kanyon (güneydoğu, Sv 15-20):** kızıl kaya sütunları arasında **Kızıl Mızrakçılar**. Görevler: Kızıl Kanyon, Kızıl Cevher.
  - **Ayaz Tepeleri (güneybatı, Sv 21-26):** karlı çamlar ve buz kristalleri, uzaktan buz atan **Ayaz Kamları**. Görevler: Ayaz Tepeleri, Ayaz Kristali.
  - **Erlik Kapısı (kuzeybatı, BOSS Sv 28):** kızıl ışıklı kara kapının önünde **Erlik Beyi**. Son görevin ödülü: Gök Tengri silahı, 10 Kor Taşı, 5000 altın.
  - Her bölgenin günlük devriyesi var (bölgenin görevleri bitince kapanır). Yeni malzemeler: Gölge Bezi, Kızıl Cevher, Ayaz Kristali (tüccara iyi fiyata satılır).
- **Yeni NPC: Otacı Ana** (köyde, kamp ateşinin batısında, yeşil kazanın başında). İksirler artık ondan alınır: Can ve Ruh İksiri ile yeni **Büyük Can İksiri** (320 can) ve **Büyük Ruh İksiri** (240 mana). **x1 / x10** ile alınır. Çantada büyük iksir varsa 6 / 7 tuşları önce onu kullanır.
- **Kor Ocağı daha pahalı:** her yükseltme denemesi 2,5 kat altın ister (+0→+1: 50, +7→+8: 3200 altın).
- **Canavarlar daha dayanıklı:** canları kademeli arttı (zayıflar %20, güçlüler %70'e kadar). Canavarlardan düşen iksir yarıya indi.

## v0.11.2 — Pencere düzeni
- Tüccar ya da Kor Ocağı açılınca envanter yerinden kaymaz; NPC penceresi envanterin hemen soluna açılır.
- Tüccar listesi uzadığı için kaydırılabilir oldu, artık pencerenin dışına taşmaz.
- Kor Ocağı açıkken eşyaya sol tıklamak artık yükseltme yapmaz; sadece bilgi penceresi açılır. Yükseltme yalnızca **"Kor Ocağı'nda yükselt"** düğmesiyle yapılır.
- NPC açıkken eşya bilgisi NPC penceresinin üstünde açılır, çanta görünür kalır.
- Haritadaki Bilge Ata işareti görev durumuna göre değişir: **!** alınabilir görev, **?** teslim edilecek görev; görev kalmadıysa sadece küçük bir nokta.

## v0.11.1 — Okçu sadaksız ok atamaz
- Okçu artık ok atabilmek için yan el yuvasında **sadak** taşımalı. Sadak yoksa normal saldırı ve ok yetenekleri (Çifte Ok, Zehirli Ok, Ok Yağmuru) çalışmaz, "Okun yok!" uyarısı çıkar. Hız ve Keskin Göz güçlendirmeleri sadaksız da kullanılabilir.
- Yeni okçular Deri Sadak takılı başlar. Hiç sadağı olmayan eski okçulara girişte bir kez Deri Sadak verilir.

## v0.11.0 — Sadak, tek vuruş, devriye düzeni
- **Okçuda hançer yerine sadak:** Yan el eşyaları artık ok kılıfı: **Deri Sadak** ve **Bozkır Sadağı**. Elde bıçak görünmez; sadak sırtta, okları omzunun üstünden görünür. Eski hançerlerin sadağa dönüşür, statları aynı kalır.
- **R tuşu:** Her basışta **tek bir** normal saldırı yapar (hedef uzaktaysa yaklaşıp bir kez vurur). Yetenek kullanmak da artık otomatik saldırıyı başlatmaz.
- **NPC'ler:** Tüccar, Demirci ve Bilge Ata ancak **yanlarına gidince** (3,5 m) E ile açılır. NPC'ye tıklarsan yanına yürürsün.
- **Devriye görevleri bölgeye bağlandı:** Ova Devriyesi İlk Av'dan sonra açılır, **Ovayı Temizle** bitince kalıcı olarak kapanır. Koru Devriyesi Kemik Muskalar'la, Bataklık Devriyesi Ruh Tozu ile kapanır. Açıkken günde en fazla 3 kez yapılabilir. Kara Han'ın tekrar görevi kaldırıldı.

## v0.10.0 — Görevler ve Bilge Ata
- **Yeni NPC: Bilge Ata.** Köyün kuzeyinde, kamp ateşinin başında oturur. Başının üstünde altın **!** varsa alabileceğin görev, **?** varsa teslim edeceğin görev var demektir. Yanına gidip **E** tuşuna bas ya da üstüne tıkla.
- **Görev zinciri (Sv 1 → Kara Han):** İlk Av, Kırık Kemikler, Ovayı Temizle, Kemik Korusu, Kemik Muskalar, Kara Bataklık, Ruh Tozu ve son olarak Kara Han. Her görevin kendi hikâyesi var. Ödüller: TP, altın, iksir, Kor Taşı ve sınıfına uygun eşyalar (başlık, yan el, silah, kolye, yüzük, Ay Kolyesi).
- **Tekrarlanabilir devriye görevleri:** Ova, Koru, Bataklık ve Kara Han devriyeleri bitince yeniden alınabilir.
- Öldürme görevleri otomatik sayılır; toplama görevlerinde malzemeler teslim edince çantadan alınır. Aynı anda en fazla 5 görev.
- **Görev takip listesi:** Ekranın sağında, mini haritanın altında aktif görevlerin ilerlemesi görünür (**L** ile aç/kapat). Mini haritada Bilge Ata sarı **!** ile işaretli.

## v0.9.1 — Daha küçük güncellemeler
- İkonlar, sesler ve arayüz görselleri artık küçük güncelleme paketiyle gelir. 77 MB'lık model paketi yalnızca 3D modeller değiştiğinde yeniden iner; ikon veya ses değişikliği için tekrar indirmen gerekmez.
- "3D modeller indiriliyor" ekranı pencerenin tam ortasında görünür.

## v0.9.0 — Büyücü ve yeni sınıf Şifacı
- **Kam artık Büyücü:** En yüksek hasarı veren sınıf. Saldırısı ve büyü güçleri arttı (Ruh Ateşi, Buz Mızrağı, Gök Gürültüsü). Kendini iyileştiren Şifa yeteneği kaldırıldı, yerine **Alev Halkası** geldi (etrafındaki tüm düşmanları yakar). Şifa'ya verdiğin beceri puanları geri iade edilir, K ile yeniden dağıtabilirsin.
- **Yeni sınıf: Şifacı** (karakter oluştururken seçilir). Gücünün yaklaşık %70'i iyileştirme, hasarı büyücünün yarısı kadar:
  - Işık Oku (Sv 1): hedefe ışık oku.
  - Şifa Işığı (Sv 2): yakındaki en yaralı dostu (ya da kendini) iyileştirir.
  - Toplu Şifa (Sv 6): etrafındaki tüm dostları iyileştirir.
  - Yenilenme (Sv 9): etrafındaki dostlar 8 saniye boyunca her saniye can yeniler.
  - Koruyucu Ruh (Sv 12): etrafındaki dostların savunması artar.
  - Kendine özel eşyalar: Ak Değnek, Umay Değneği, Umay Tılsımı, Ak Takke ve daha fazlası (Tüccar'da ve canavarlardan).
  - Beyaz-altın cübbesiyle büyücüden ayrı görünür.
- Denge (hesap + bot denemesi, Sv 10 ve üstü): Büyücü %100, Okçu ~%70-80, Savaşçı ~%50-60 hasar (savaşçı en dayanıklı), Şifacı ~%50 hasar + güçlü iyileştirme.
- İlk açılışta yeni ikonlar için model paketi bir kez yeniden iner.

## v0.8.0 — Görsel yenilik: büyüler, ikonlar, eşya bilgisi
- **Büyü efektleri yenilendi:** Ruh Ateşi alevli mermi ve patlama, Buz Mızrağı buz kristali ve don sisi, Yıldırım gökten düşen zikzak şimşekler, Zehirli Ok yeşil iz ve zehir bulutu, Şifa yükselen ışık sütunu. Girdap dönen kılıç izleri, Ağır Darbe yerde çatlak ve toz bırakır. Güçlendirmelerde (Kalkan Duvarı, Savaş Narası vb.) süre boyunca karakterin etrafında parçacıklar döner. Vuruşlarda isabet kıvılcımları çıkar.
- **Yeni ikonlar:** Eşya ikonları metal parlaklığı ve kenar ışığıyla daha gerçekçi; yetenek ikonları boyanmış görünümlü, parlayan ve bronz çerçeveli.
- **Yeni skill bar:** Bronz çerçeveli yuvalar, saat yönünde dolan bekleme süresi ve kalan saniye.
- **Eşya bilgisi:** Fareyle üzerine gelince açılan küçük kutu kaldırıldı; bilgi sadece sol tıkla açılır. Panelde artık eşyanın açıklaması, kademesi, statların nereden geldiği (temel / yükseltme / nadirlik / ek), giyili eşyayla karşılaştırma (▲ yeşil daha iyi, ▼ kırmızı daha kötü), silahın saldırı hızı ve menzili, Kor Ocağı'nda bir sonraki yükseltmenin şansı ve fiyatı, tüccar fiyatı görünür.
- **Karakterler:** Daha mat kumaş/deri, parlak metal silah ve zırh, kenar ışığı.
- **Sohbet penceresi:** Skill bar artık sohbetin üstüne binmez. Sohbet başlığındaki ▲ / ▼ ile büyütülür-küçültülür, başlıktan tutup yukarı-aşağı sürükleyerek boyu ayarlanır, — ile kapatılıp açılır. Ayar kaydedilir.
- İlk açılışta yeni ikonlar için model paketi bir kez yeniden iner.

## v0.7.0 — Gerçekçi dünya ve sesler
- **Gerçekçi zemin:** Çimen, kuru ot, orman toprağı, çamur, kaya ve toprak yol gerçek dokularla, daha net görünür.
- **Yeni ağaçlar:** Gerçek kabuk ve yaprak dokulu çam, köknar, yapraklı ve kuru ağaçlar; çalılar, eğrelti otları, devrik kütükler ve gerçekçi kayalar.
- **Ses ve müzik:** Saldırı, isabet, beceri, ölüm, seviye atlama, iksir, sandık, altın, ayak sesi, demirci sesleri ve bölge müzikleri. Ayarlar'da Ana ses / Müzik / Efektler kaydırıcıları.
- **Satış:** Yığın halindeki malzemeler artık tamamı birden satılır; kurt postu, domuz dişi, albastı saçı ve kemik fiyatları yükseldi.
- **NPC pencereleri** ekranın ortasında açılır.
- **Grafik kalitesi** değiştirince anında uygulanır, karaktere yeniden girmek gerekmez.
- **Seviye kontrolü:** Seviyenin yetmediği giyili eşyalar girişte çantaya alınır ve stat vermez.
- **Oyun dosyası kendini günceller:** Arka planda bir kez (~32 MB) iner, bir sonraki açılışta geçerli olur. Açılış ekranının sağ altta kalma sorunu bununla düzelir.
- İlk açılışta yeni modeller için model paketi bir kez yeniden iner.

## v0.6.0 — Eşya nadirliği ve statlar
- **Nadirlik:** Sıradan (beyaz), Nadir (mavi, statlar %15 fazla), Destansı (mor, %35 fazla + 1 ek stat), Efsanevi (turuncu, %60 fazla + 2 ek stat). Canavarların düşürdüğü eşyaların nadirliği rastgeledir; Kara Han'da şans 2 kat. Efsanevi eşya bulunca herkese duyurulur.
- **Her 10 seviyede bir eşya kademesi:** Sv 1, Sv 10, Sv 20 ve yeni **Sv 30 Gök Tengri** seti (Kara Han'dan çok nadir düşer). Seviyen yetmeyen eşyalar kırmızımsı görünür ve giyilemez.
- **Sol tık → eşya stat penceresi:** nadirlik, gereken seviye, sınıf, tüm statlar (ek statlar yeşil), Kor Ocağı seviyesi ve satış fiyatı. Pencereden kuşan / sat / yükselt.
- **Sağ tık → giy / kullan.** Ekipman yuvasında sağ tık → çıkar.
- Eşya çerçeveleri nadirlik rengindedir. Nadir eşyalar daha pahalıya satılır.

## v0.5.2
- **Engel etrafından dolaşma iyileştirildi:** karakter (yere tıklayarak yürürken de) kamp ateşi, ağaç ve kaya gibi engellere takılıp kalmıyor; engelin çevresinden hedefe yakın taraftan dolaşıyor.

## v0.5.1
- "3D modeller indiriliyor" ekranı pencerenin tam ortasına alındı.
- Güncelleme ekranı ("Yeni sürüm bulundu") yeni kurulumlarda tam ortada (bu ekran oyun dosyasının içinde olduğu için mevcut kurulumlarda değişmez; zaten 1-2 saniye görünür).

## v0.5.0 — Hesaplar ve 3D karakter seçimi
- **Hesap sistemi:** giriş ekranında artık hesap adı + şifre. Bir hesapta **3 karaktere** kadar olabilir.
- **3D karakter seçim ekranı:** karakterlerin ekipmanlarıyla kaidelerde yan yana durur. Tıkla → seçilir, öne çıkar ve döner. Altında ad, sınıf, seviye ve boy yazar.
- **Yeni Karakter:** ad, sınıf ve boy seçerken boş kaidede seçtiğin sınıfın canlı 3D önizlemesi görünür.
- **Karakteri Sil:** yanlışlıkla silinmesin diye karakterin adını yazarak onaylanır (sunucuda yedek dosya saklanır).
- **Eski karakterler:** eski karakter adın ve şifrenle giriş yaparsan otomatik olarak hesaba dönüşür, karakterin içinde hazır gelir.
- **ESC → Karakter Ekranına Dön** artık şifre sormadan doğrudan seçim ekranına götürür. **Hesaptan Çık** giriş ekranına döner.

## v0.4.1 — ESC menüsü
- **ESC menüsü:** Oyuna Dön, Ayarlar, Karakter Ekranına Dön, Oyundan Çık.
- **Ayarlar:** grafik kalitesi, tam ekran, kamera (fare) hassasiyeti, tuş yardımını göster/gizle. Ayarlar kaydedilir.
- **Karakter Ekranına Dön** ve **Oyundan Çık** karakterini kaydedip çıkar; tekrar girince kaldığın yerden devam edersin.
- ESC önce açık pencereyi (çanta, beceriler, sandık, harita…) kapatır; açık pencere yoksa menüyü açar. Menü açıkken karakter yürümez.

## v0.4.0 — Beceri puanları ve çarpışma
- **Beceri puanı sistemi:** her seviyede +2 beceri puanı. **K** tuşuyla Beceriler penceresini aç, puanları istediğin yeteneğe ver. Her puan yeteneğin etkisini %6 artırır, yetenek başına en fazla 15 puan.
- **Seviye sınırı 30** (toplam 59 beceri puanı: hepsini doldurmak mümkün değil, seçim yapmalısın).
- **Her sınıfa 5. yetenek ve hız yetenekleri:** Savaşçı — Hücum (hız), Okçu — Keskin Göz (saldırı hızı), Kam — Rüzgar Kanadı (hız). Yetenekler Sv 1 / 3 / 6 / 9 / 12'de açılır.
- **Yetenek çubuğu:** 1-5 yetenekler, 6 can iksiri, 7 mana iksiri, R normal saldırı.
- **Okçunun saldırı hızı arttı** (1,0 sn → 0,8 sn).
- **Çarpışma:** karakter artık ağaçların, kayaların, yurtların, çadırların, tezgâhların ve eşyaların içinden geçmiyor; kenarından kayarak dolaşıyor.
- **Orman seyreltildi:** Kemik Korusu'ndaki ağaç kümeleri tekli ağaçlarla değiştirildi.
- Eski karakterlere seviyelerine göre beceri puanları geriye dönük verildi.

## v0.3.3
- **Gerçek ok:** Okçunun attığı ok artık beyaz top değil, gerçek ok modeli. Uçuş yönüne döner, hafif yay çizer, arkasında iz bırakır; hasar ok hedefe varınca görünür.
- **Çifte Ok** iki ok atar, **Zehirli Ok** yeşil parlar, **Ok Yağmuru**'nda gökten gerçek oklar düşer.
- **Ağaçlar azaltıldı:** haritadaki ağaç sayısı yaklaşık %60 azaltıldı, açık alanlar ferahladı (oyun da biraz daha hızlı çalışır).

## v0.3.2
- **Can çubukları düzeltildi:** can azaldıkça çubuk artık soldan sağa doğru boşalıyor (önce iki yandan birden kısalıyordu).
- **Ölen canavarların ve oyuncuların** üstündeki isim ve can çubuğu artık gizleniyor; dirilince geri geliyor.
- Hoş geldin mesajı yeni tuşlara göre güncellendi.

## v0.3.1 — Güncelleme düzeltmesi
- **Yavaş internette güncelleme takılması düzeltildi.** Güncellemeler artık ikiye ayrıldı: küçük kod paketi (her sürümde, ~200 KB) ve 3D model paketi (sadece modeller değişince, bir kez iner).
- Model paketi indirilirken ilerleme çubuğu görünür; süre sınırı yoktur, bağlantı koparsa 5 kez tekrar dener.
- Oyun paketinden gereksiz ekran görüntüleri çıkarıldı (indirme ~5 MB küçüldü).

## v0.3.0 — Büyük güncelleme: yetenekler, sandıklar, yeni dünya
- **Yeni dünya:** desenli yurtlar, pazar tezgâhı, kamp ateşleri, toprak yollar, ormanlar, nilüferli Kara Bataklık ve harabeleri, kayalarla çevrili Kara Han Mağarası, karlı dağlar, otlar ve çiçekler.
- **Mini harita** (sağ üstte, kamerayla döner) ve **büyük harita (M)**: canavarlar kırmızı, oyuncular mavi, sandıklar sarı.
- **MP (mana)** ve **her sınıfa 4 yetenek** (Sv 1/3/5/7): Savaşçı — Ağır Darbe, Kılıç Girdabı, Kalkan Duvarı, Savaş Narası; Okçu — Çifte Ok, Zehirli Ok, Ok Yağmuru, Rüzgar Adımı; Kam — Ruh Ateşi, Şifa, Buz Mızrağı, Gök Gürültüsü.
- **Yetenek çubuğu:** 1-4 yetenekler, 5 can iksiri, 6 ruh (mana) iksiri, R normal saldırı. Simgeler, bekleme süresi, kilit ve mana uyarısı.
- **Sandık ganimeti:** canavarlar sandık düşürür. Sandığa sol tıkla → karakter yanına yürür ve açar. 3x2 = 6 yuvalı sandık penceresi, tek tek ya da "Hepsini Al".
- **Karakterli envanter (I):** ortada döndürülebilir 3D karakterin, etrafında 6 ekipman yuvası: Silah, Yan El, Başlık, Zırh, Kolye, Yüzük.
- **Eşyalar karakterde görünür:** miğfer, kalkan (yuvarlak / armalı / dikenli), kukuleta, kam börkü, büyü kitabı, hançer, pelerin; zırh seviyesine göre zırh rengi değişir.
- **Yeni eşyalar:** kalkanlar, hançerler, büyü kitapları, miğferler, kukuletalar, börkler, kolyeler, yüzükler, Ruh İksiri. Hepsi Kor Ocağı'nda yükseltilebilir.
- **49 yeni ikon** (eşyalar ve yetenekler).
- **Fare:** yere sol tıkla → oraya yürü (yeşil işaret). Canavara tıkla → hedef. NPC'ye tıkla → konuş.
- **Grafik kalitesi** seçimi (giriş ekranı): Düşük / Orta / Yüksek. Bilgisayarın zorlanırsa Düşük'ü seç.
- Yeni karakterler Deri Zırh ile başlar.
- Görsel modeller: KayKit (Kay Lousberg, CC0).

## v0.2.0 — Gerçek 3D karakterler
- **Animasyonlu 3D karakterler:** Savaşçı (şövalye), Okçu ve Kam artık iskeletli, animasyonlu modellerle geliyor.
- **Elinde gerçek silah:** Savaşçı kılıç + kalkan, Okçu arbalet, Kam değnek/asa taşır. Daha iyi silah kuşanınca eldeki silah değişir (3. seviye: iki elli kılıç, arbalet + hançer, asa + büyü kitabı).
- **Animasyonlar:** bekleme, yürüme, koşma, saldırı, yetenek (Ağır Darbe dönerek vuruş, Çifte Ok seri atış, Ruh Ateşi uzun büyü), darbe alma, iksir içme, seviye atlayınca sevinme, ölüm.
- **Yeni düşmanlar — Erlik Han'ın ordusu:** Erlik Eri, Kemik Savaşçı, uzaktan büyü atan Erlik Kamı ve boss Kara Han. İskeletler ölünce kemiklerine ayrılarak yıkılır.
- Bölge adları: Kemik Ovası, Kemik Korusu, Kara Bataklık, Kara Han Mağarası.
- Tüccar ve Demirci artık animasyonlu; Demirci baltasıyla örsü döver.
- Kamera karaktere daha yakın, ışık ve renkler daha dengeli.
- Boy rengi pelerin rengine yansır (Kurt Boyu mavi, Kartal Boyu turuncu).
- Modeller: KayKit (Kay Lousberg, CC0 lisans).

## v0.1.3
- **Otomatik güncelleme:** Oyun açılırken yeni sürüm olup olmadığına bakar; varsa kendisi indirip kurar. Artık zip indirmek gerekmez.
- Oyun ile sunucunun sürümü farklıysa girişte açık bir uyarı çıkar.
- Sürüm numarası tek bir yerden (surum.txt) yönetiliyor.

## v0.1.2
- Giriş ekranına **Yenilikler** paneli eklendi: her sürümde neyin değiştiği oyunun içinde görünür.
- Değişiklik notları artık her sürümle birlikte tutuluyor (bu dosya).
- Proje gizli GitHub deposuna yedeklendi.

## v0.1.1
- **Sunucuyu artık oyun kendisi açıyor.** Adres 127.0.0.1 iken sunucu kapalıysa oyun onu arka planda başlatır.
- Oyunu kapatınca otomatik açılan sunucu kayıt alıp 20 saniye içinde kendiliğinden kapanır.
- Sunucu zaten açıksa (Sunucu_Baslat.bat) ikinci bir sunucu açılmaz.
- Bağlanamama hatası 30+ saniye yerine ~5 saniyede gelir.

## v0.1.0 — İlk sürüm
- 3D açık dünya: Ötüken Köyü (güvenli bölge), Kurt Ovası, Domuz Korusu, Albastı Bataklığı, Tepegöz Mağarası.
- 3 sınıf: Savaşçı, Okçu, Kam — 2 boy: Kurt Boyu, Kartal Boyu.
- Hedef seçimli savaş (Z / sol tık), otomatik saldırı (R), sınıf yeteneği (1), iksir (2).
- Canavarlar: Kara Kurt, Yaban Domuzu, Albastı ve boss Tepegöz.
- Seviye ve tecrübe, altın, ganimet torbaları, 24 slotluk çanta, silah/zırh kuşanma.
- Tüccar Ayaz (alım-satım) ve Demirci Usta Demirhan'ın Kor Ocağı (+1…+8 yükseltme, eşya yok olmaz).
- Çok oyunculu sunucu, isim + şifre ile giriş, sohbet, karakter kayıt sistemi.
