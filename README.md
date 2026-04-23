📞 Call-SMS Bomber
Uyarı: Bu araç yalnızca eğitim ve yetkili penetrasyon testleri için tasarlanmıştır. İzinsiz kullanım yasa dışıdır.

✨ Özellikler
📱 SMS bombası | 📞 Call bombası | 💻 Termux/Linux uyumlu

📥 KURULUM KOMUTLARI
🔷 Termux için (arka plan: koyu mavi)
bash
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
🔶 Linux / macOS için (arka plan: koyu turuncu)
bash
sudo apt update && sudo apt install git python3 -y
bash
git clone https://github.com/Heckerandseher/call-smsbomb.git
bash
cd call-smsbomb
bash
pip3 install requests
bash
python3 smscall.py
⚡ TEK SATIRDA KURULUM (Kopyala-Yapıştır)
🟦 Termux tek satır:
bash
pkg update && pkg upgrade -y && pkg install git python -y && git clone https://github.com/Heckerandseher/call-smsbomb.git && cd call-smsbomb && pip install requests && python smscall.py
🟧 Linux tek satır:
bash
sudo apt update && sudo apt install git python3 -y && git clone https://github.com/Heckerandseher/call-smsbomb.git && cd call-smsbomb && pip3 install requests && python3 smscall.py
🔄 GÜNCELLEME KOMUTU
bash
cd call-smsbomb && git pull && pip install requests --upgrade
🗑️ KALDIRMA KOMUTU
bash
cd .. && rm -rf call-smsbomb
⚙️ KULLANIM ADIMLARI
Hedef numarayı girin → +905551234567

Tür seçin → 1 (SMS), 2 (Call), 3 (Her ikisi)



Süre girin → 0 = sonsuz

🛠️ SORUN GİDERME KOMUTLARI
Sorun	Çözüm Komutu
requests modülü yok	pip install requests
Termux izin hatası	termux-setup-storage
SSL sertifika hatası	pkg install ca-certificates
📜 SORUMLULUK REDDİ
Bu araç eğitim amaçlıdır. Hedefin izni olmadan kullanmak YASA DIŞIDIR. Tüm sorumluluk kullanıcıya aittir.

Not: Komutları kopyalamak için üzerlerine tıklayın veya işaretleyip Ctrl+C yapın. Termux'ta uzun basıp "Copy" seçeneğini kullanın.

