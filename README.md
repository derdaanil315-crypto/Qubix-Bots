🤖 Qubix Bot v2.0.7

> Qubix; Jubbio için geliştirilmiş AI sohbeti, sunucu mimarı, moderasyon ve koruma botudur.

🚀 Öne Çıkan Özellikler
• Çoklu AI (Gemini, Groq, OpenRouter) ve rota yedekleme
• Doğal dille sunucu odası, rol ve yapılandırma kurma
• Gelişmiş moderasyon (!sustur, !yasakla, !sil, !kilit, !uyar)
• Anti-link, anti-spam ve mod-log koruma sistemleri

🛠️ Gereksinimler & Hızlı Kurulum (PowerShell)
1. Node.js v20+ kurulu olmalıdır.
2. Proje klasöründe terminali açıp çalıştırın:
   npm ci
   Copy-Item .env.example .env
   notepad .env
3. .env dosyasına BOT_TOKEN değerini ve en az bir AI anahtarını girin (Örn: GEMINI_API_KEY_1).
4. Sağlayıcı testi ve başlatma:
   npm run check:providers
   npm start

⚙️ Jubbio Ayarları
1. Geliştirici portalından bot oluşturup tokenı .env'ye ekleyin.
2. Botu sunucuya ekleyip sohbet/yönetim izinlerini verin.
3. Message Content erişimini açın ve bot rolünü yöneteceği rollerin üstüne taşıyın.

💬 Kullanım Örnekleri
• AI Sohbeti & Mimar: 
  @Qubix Kuantum fiziği nedir?
  !soru <sorunuz> (veya !ai, !q, !mimar)
  @Qubix yazılım topluluğu sunucusu kur
• Moderasyon: 
  !sustur @üye 10m [sebep] | !susturkaldir @üye
  !at @üye [sebep] | !yasakla @üye [sebep]
  !sil 10 | !kilit | !kilitaç | !koruma

🛠️ Geliştirici ve Yayın Komutları
• npm start : Botu başlatır
• npm run check:providers : AI kotasını ve bağlantıları test eder
• npm test : Kod sözdizimi denetimi yapar
• npm run prepare:release : .env, data/ ve node_modules/ hariç temiz release/ çıktısı üretir

📜 Lisans & İletişim
• Lisans: ISC
• Geliştirici: Derda Açıkgöz
• Jubbio İletişim: @perry37
• Destek Sunucusu: https://jubbio.com/invite/I3YZVTYj
