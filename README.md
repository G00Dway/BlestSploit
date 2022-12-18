# Yeni sürüm geliyor!
```
- Dil desteği
- Birçok hata düzeltmesi
- Birçok yeni modül
- Modül düzeltmeleri
- Ve daha fazlası!

Yeni sürüm: 1.5.32
```
# BlestSploit Framework
BlestSploit Framework, Exploits, Payloads, Posts ve Daha Fazlası gibi yayınlanmış modüllerle bir framework!
# Kurulum / Kaldırma
### Kurulum (root)
```
git clone https://github.com/G00Dway/BlestSploit
cd BlestSploit
bash install-framework.sh
btconsole
```
### Kaldırma
BlestSploit'i sisteminizden kaldırmak için sadece çalıştırın: `bash uninstall-framework.sh`
# Credits
Krediler gider: `Leatrix`, `Fux Walker`, `Kenn`
# Sorunlar, hatalar
Herhangi bir hata bulduysanız, lütfen bunları şu adrese bildirin: <a href="https://github.com/G00Dway/BlestSploit/issues">Bug Reports, Issues</a>
# Kendi modülü nasıl eklenir?
* İlk olarak, "/usr/share/blest-framework/src/data/core/module/data/" adresine gidin ve "modules.json" adlı bir dosya göreceksiniz, onu favori düzenleyicinizle açın
ardından belirtilen kodu dosyanın sonuna ekleyin
```
"bir numara":{
            "author": "Ad",
            "name": "Modülün dosya adı ama .py, .sh, ve.s olmasın",
            "prefix": "Modülün prefixleri, Vb: -t $1 -p $2", # $1 - AYAR1, $2 - AYAR2, $2-ni $3 etseniz AYAR2 yinede seçilecek AYAR3 olsada
            "options": { # Modülün ayarları
                  "AYAR1": ["AYAR HAKKINDA", ""],
                  "AYAR2": ["AYAR HAKKINDA", ""],
                  "AYAR3": ["AYAR HAKKINDA", ""] # sonsuz ayar koyabilirsiniz
            }
 }
 ```
 * ve modülünüzü "/usr/share/blest-framework/src/data/modules/exploit" dizinine eklemeyi unutmayın!
# Başlıklar
* bu arada "BlestSploit" gibi başlıklar istiyorsanız "config.ini"deki "official"yi "true" olarak değiştirin, ve "unofficial" ifadesini "false" olarak değiştirin
# Uyarı
BlestSploit ile yaptığınız işlemlerden sorumlu DEĞİLİZ, lütfen bu aracı yalnızca eğitim amaçlı kimi kullanın!
