# Bozkır Çağı — Değişiklik Notları

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
