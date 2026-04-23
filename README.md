# 📞 Call-SMS Bomber

## Not

Bu aracın artık düzgün çalışmadığına dair çok sayıda şikayet alıyorum. Servis sağlayıcılar muhtemelen bazı değişiklikler yaptı, ancak ne yazık ki şu anda aracı düzeltmek için zaman veya motivasyonum yok. Eğer birisi bunu düzeltmek isterse, bir pull request gönderebilir. Kodu inceledikten sonra pull request'i memnuniyetle kabul edeceğim.

## Sorumluluk Reddi

Bu araçla ilgili tüm eylemler ve faaliyetler tamamen sizin sorumluluğunuzdadır. Bu aracın kötüye kullanılması, söz konusu kişilere karşı cezai işlem yapılmasına neden olabilir. Kişiler bu aracı kanun çiğnemek için kötüye kullanırlarsa, katkıda bulunanlar hiçbir sorumluluk almayacaktır.

Bu araç, potansiyel olarak zararlı veya tehlikeli materyaller içerir. Bu araca erişmeden, kullanmadan veya başka bir şekilde yanlış şekilde kullanmadan önce eyaletiniz/ülkenizin yasalarına başvurunuz.

Bu Araç yalnızca eğitim amaçları için yapılmıştır. Burada yer alan hiçbir şeyle yasayı çiğnemeye çalışmayınız.

Sadece "SMS/Call bombası nasıl çalışır" gösterir. Bu aracı birini taciz etmek veya rahatsız etmek için kötüye kullanmayınız. Ancak bunu kendi riskiniz altında deneyebilirsiniz.

### Call-SMS Bomber aracı, özel olarak SMS ve çağrı bombardımanı için oluşturulmuş bir araçtır. Bu aracı diğerlerinden üstün kılan nedir?

1) Hem SMS hem de çağrı bombardımanını tek araçta sunar.

2) Sonsuz döngü (0 süre) seçeneği ile kesintisiz gönderim yapabilir.

3) Termux, Linux ve macOS ile uyumludur.

4) Basit tek satırlık kurulum imkanı sunar.

## ✨ Özellikler

📱 SMS bombası | 📞 Call bombası | 💻 Termux/Linux/macOS uyumlu

## Gereksinimler

1. Python 3
2. Git
3. Requests modülü

## 📥 Kurulum Komutları

### 🔷 Termux için

```bash
pkg update && pkg upgrade -y
bash
pkg install git python -y
bash
git clone https://github.com/Heckerandseher/call-smsbomb.git
bash
cd call-smsbomb
bash
pip install requests
bash
python smscall.py
''
### 🔶 Linux / macOS için
```bash
sudo apt update && sudo apt install git python3 -y
bash
git clone https://github.com/Heckerandseher/call-smsbomb.git
bash
cd call-smsbomb
bash
pip3 install requests
bash
python3 smscall.py
⚡ Tek Satırda Kurulum (Kopyala-Yapıştır)
🟦 Termux tek satır:
bash
pkg update && pkg upgrade -y && pkg install git python -y && git clone https://github.com/Heckerandseher/call-smsbomb.git && cd call-smsbomb && pip install requests && python smscall.py
🟧 Linux tek satır:
bash
sudo apt update && sudo apt install git python3 -y && git clone https://github.com/Heckerandseher/call-smsbomb.git && cd call-smsbomb && pip3 install requests && python3 smscall.py
🔄 Güncelleme Komutu
bash
cd call-smsbomb && git pull && pip install requests --upgrade
🗑️ Kaldırma Komutu
bash
cd .. && rm -rf call-smsbomb
⚙️ Kullanım Adımları
Hedef numarayı girin → +905551234567

Tür seçin → 1 (SMS), 2 (Call), 3 (Her ikisi)

Süre girin → enter = sonsuz

🛠️ Sorun Giderme Komutları
Sorun	Çözüm Komutu
requests modülü yok	pip install requests
Termux izin hatası	termux-setup-storage
SSL sertifika hatası	pkg install ca-certificates
📜 Sorumluluk Reddi
Bu araç eğitim amaçlıdır. Hedefin izni olmadan kullanmak YASA DIŞIDIR. Tüm sorumluluk kullanıcıya aittir.

Not: Komutları kopyalamak için üzerlerine tıklayın veya işaretleyip Ctrl+C yapın. Termux'ta uzun basıp "Copy" seçeneğini kullanın.
