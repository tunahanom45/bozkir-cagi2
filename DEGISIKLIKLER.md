# Bozkır Çağı — Değişiklik Notları

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
