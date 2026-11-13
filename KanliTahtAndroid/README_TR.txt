KANLI TAHT ANDROID UYGULAMASI

Bu proje https://kanlitaht.com.tr adresini dikey ekranda açan Android WebView uygulamasıdır.

GEREKSİNİMLER
- Android Studio (Giraffe veya daha yeni)
- JDK 17
- Android SDK Platform 35
- Android Gradle Plugin 8.6.1 (Gradle senkronizasyonu sırasında indirilir)

APK OLUŞTURMA
1. Android Studio ile bu klasörü aç.
2. Gradle Sync tamamlanmasını bekle.
3. Build > Build Bundle(s) / APK(s) > Build APK(s) seç.
4. Debug APK şu konumda oluşur:
   app/build/outputs/apk/debug/app-debug.apk

ÖZELLİKLER
- Uygulama başlangıç adresi: https://kanlitaht.com.tr
- Dikey ekran kilidi
- JavaScript ve DOM Storage açık
- Oturum çerezleri etkin
- Kanlı Taht alan adı uygulama içinde kalır; diğer web alanları tarayıcıda açılır
- Geri tuşu WebView geçmişinde geri gider
- Bağlantı hatasında tekrar dene ekranı

ÖNEMLİ
Bu teslim Android Studio kaynak projesidir; bu çalışma ortamında Android SDK ve Gradle kurulu olmadığı için APK burada derlenemedi.
Google Play'e yüklemek için ayrıca release imzası (keystore), gizlilik politikası ve Play Console süreci gerekir.
