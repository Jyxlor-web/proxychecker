📜 Python Proxy Checker – Jyxlor Edition


🧠 Ne İşe Yarar? | What Does It Do?
🇹🇷 Bu script, .txt dosyasından proxy IP:PORT listesi alır ve her bir proxy'yi http://httpbin.org/ip adresine bağlanarak çalışıyor mu, bozuk mu diye test eder.
🟢 Çalışanlar OK, 🔴 çalışmayanlar FAIL olarak renkli şekilde terminalde gösterilir.

🇬🇧 This script reads a list of proxy IP:PORT entries from a .txt file, and checks if each one is working by sending a request to http://httpbin.org/ip.
🟢 Working proxies are marked OK, 🔴 non-working ones are shown as FAIL with colored terminal output.

💡 Özellikler | Features
Özellik (TR)	Feature (EN)
Renkli terminal çıktısı	Colored terminal output (via colorama)
http ve https proxy desteği	Supports http and https proxies
Canlı - Bozuk rastgele mesaj sistemi	Random success/failure messages
Hatalı dosya ismi kontrolü	File not found handling
Otomatik bekleme (0.5s)	Automatic 0.5s delay between requests

🔎 Fonksiyonlar | Functions
✅ check_proxy(proxy)
🇹🇷 Verilen proxy'yi test eder.

🇬🇧 Tests the given proxy.

🎨 print_banner()
🇹🇷 Script başında logo / afiş basar.

🇬🇧 Prints the ASCII banner at the top.

🧠 main()
🇹🇷 Kullanıcıdan proxy dosya adını ister, döngüyle tüm proxyleri test eder.

🇬🇧 Asks for the proxy list filename, loops through and checks all proxies.

🚀 Kullanım | Usage
Terminalden çalıştır:


```https://github.com/Jyxlor-web/proxychecker.git```


```cd proxychecker```


```python3 proxychecker.py```

```Pass: uhwauHUIWUIHFAUWIOFNHIOWAH ```


Proxy listesi dosya adini gir (or: proxies.txt):
Dosya örneği (proxies.txt):


```187.190.234.225:8080```


```45.95.96.132:8080```


```91.225.158.233:8080```


📦 Gereksinimler | Requirements

```pip install colorama requests```
📌 Not


http proxylerle çalışır. socks için ek modül gerekir.

Kullanıcıya renkli, dinamik ve eğlenceli bir test çıktısı verir.

