# Emipa WHOIS, SSL ve DNS Sorgu Sistemi / Emipa WHOIS, SSL and DNS Query System


Emipa – PHP İş Yönetim Paneli
-----------------------------

**Emipa**, hosting firmalarında görev yapan teknik destek personellerinin iş süreçlerini kolaylaştırmak için geliştirilmiş kapsamlı bir paneldir. Panel; sorgulama, veri kaydı, mola takibi ve içerik yönetimini bir araya getirerek destek kalitesini artırmayı hedefler.

![](screenshots/tr-1.png)

1\. WHOIS, SSL ve DNS Sorgu Sistemi
-----------------------------------

*   Alan adı WHOIS bilgilerini çeker, bitiş tarihini analiz eder ve yenilenmezse hangi tarihlerde riskli duruma geçeceğini hesaplar
*   SSL sertifikasının kalan gününü gösterir
*   DNS kayıtlarının (A, MX, TXT, CNAME) farklı sunuculardaki durumunu karşılaştırır
*   Hosting firmasına ait özel kayıtları algılar ve renkli uyarılarla bilgilendirir
*   DNS sorgularında firma sunucuları da tanımlanabilir

### Ekran Görüntüsü:

![](screenshots/tr-2.png) 

![](screenshots/tr-3.png) 

![](screenshots/tr-4.png)

* * *

2\. Gerçek Zamanlı Kayıt ve İzleme
----------------------------------

*   Yapılan tüm sorgular kullanıcı bazlı olarak veritabanında saklanır
*   Kullanıcı sadece kendi yaptığı sorgulara ulaşabilir
*   Arayüz üzerinden tarih, domain veya kayıt türüne göre filtreleme yapılabilir

### Ekran Görüntüsü:

![](screenshots/tr-5.png)

* * *

3\. Personel Mola Takibi
------------------------

*   Geri sayımlı mola sistemi ile kullanıcılar molalarını takip edebilir
*   Mobil uyumlu tasarımı sayesinde telefondan da erişilebilir
*   Mola bitişlerinde sesli ve tarayıcı bildirimleri gönderilir
*   Anlık mesajlaşma uygulamasına (örneğin Telegram) canlı bildirim gönderilir
*   Mola geçmişi detaylı biçimde saklanır

### Ekran Görüntüsü:

![](screenshots/tr-6.png)

* * *

4\. Hazır Yanıtlar, Çağrılar ve Notlar Sistemi
----------------------------------------------

*   Zengin metin editörüyle yanıt oluşturulur (metin biçimlendirme, resim ekleme vs.)
*   Görseller doğrudan editöre yapıştırılabilir, base64 olarak saklanır
*   Her yanıt başlık, etiket ve kategori ile kayıt altına alınır
*   “Kullandım” butonuyla kullanım sayısı takip edilir
*   Arama motoru sayesinde filtreleme ve anahtar kelime araması yapılabilir
*   Kullanıcılar sadece kendi içeriklerine erişebilir

### Ekran Görüntüsü:

![](screenshots/tr-7.png)

![](screenshots/tr-8.png)

* * *

5\. Çoklu Kullanıcı ve Güvenlik
-------------------------------

*   Her personele ayrı kullanıcı hesabı oluşturulur
*   Kullanıcılar sadece kendi sorgularını ve yanıtlarını görebilir
*   IP değişikliği, oturum süresi gibi durumlar kontrol edilir
*   Şüpheli durumlarda oturum sonlandırılır
*   Yetkilendirme sistemi ile roller atanabilir

### Ekran Görüntüsü:

![](screenshots/tr-9.png)

* * *

6\. Ek Araçlar
--------------

**Hazır Test Kodları:** Çeşitli testler için hazırlanmış hazır dosyalar.

![](screenshots/tr-10.png)

![](screenshots/tr-11.png)

**Şifre Oluşturucu:** Güçlü, rastgele şifreler üretir

![](screenshots/tr-12.png)

**IDN Çevirici:** Uluslararası alan adlarını ASCII formatına çevirir

![](screenshots/tr-13.png)

**WordPress Hash Üretici:** `wp_hash_password()` uyumlu şifreler üretir

![](screenshots/tr-14.png)

**Base64 Oluşturucu:** Görselleri veya metinleri base64 formatına dönüştürür

![](screenshots/tr-15.png)

---------------------------------

English:

# Emipa WHOIS, SSL and DNS Query System

Emipa – PHP Work Management Panel
---------------------------------

**Emipa** is a comprehensive web-based tool built for technical support agents in hosting companies. It combines domain checks, SSL validation, DNS propagation analysis, internal content management, and break tracking into one smart interface.

![](screenshots/en-1.png)

1\. WHOIS, SSL, and DNS Query System
------------------------------------

*   Retrieves WHOIS data, parses expiration date, and warns about approaching deadlines
*   Shows remaining days for SSL certificate expiry
*   Compares DNS records (A, MX, TXT, CNAME) across multiple name servers
*   Highlights company-specific DNS settings using color-coded feedback
*   Custom DNS servers can be added to query network

### Screenshot:

![](screenshots/en-2.png)

![](screenshots/en-3.png)

![](screenshots/en-4.png)

* * *

2\. Real-Time Logging and History
---------------------------------

*   All queries are stored in a user-specific searchable history
*   Users can view only their own past queries
*   Filter results by date, domain, or record type via interface

### Screenshot:

![](screenshots/en-5.png)

![](screenshots/en-6.png)

* * *

3\. Personnel Break Tracker
---------------------------

*   Countdown-based break tracking system
*   Mobile-friendly interface for on-the-go access
*   Sends browser and sound notifications at break end
*   Sends live updates to an external messaging app (e.g., Telegram)
*   Stores detailed break history per user

### Screenshot:

![](screenshots/en-7.png)

* * *

4\. Predefined Responses, Call Scripts & Notes
----------------------------------------------

*   Create formatted content using a **rich text editor** with:
*   Styling (bold, italic), hyperlinks, lists
*   **Image paste support**, stored as base64 in the database
*   Each entry is saved with a title, tags, and category
*   A “Mark as Used” button increases a usage count
*   Search and filter responses by keyword, tag, or category
*   Each user sees only their own content

### Screenshot:

![](screenshots/en-8.png)

![](screenshots/en-9.png)

* * *

5\. Multi-user & Security System
--------------------------------

*   Separate account for each support agent
*   Users can only access their own data
*   IP and session time are monitored for anomalies
*   Suspicious activity forces session logout
*   Role-based access control is supported

### Screenshot:

![](screenshots/en-10.png)

* * *

6\. Additional Tools
--------------------

**Scripts for Test:** Scripts prepared for various tests.

![](screenshots/en-11.png)

![](screenshots/en-12.png)

**Password Generator** – Generates secure, random passwords

![](screenshots/en-13.png)

**IDN Converter** – Converts internationalized domains to ASCII

![](screenshots/en-14.png)

**WordPress Hash Generator** – Generates wp-compatible hashed passwords

![](screenshots/en-15.png)

**Base64 Converter** – Converts images or text to base64

![](screenshots/en-16.png)
