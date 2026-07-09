# 🛡️ STYX BOT — RESMİ GİZLİLİK POLİTİKASI VE VERİ GÜVENLİĞİ

Bu belge, **Styx Bot** ("Bot") için Gizlilik Politikası ve Veri Güvenliği standartlarını açıklar. Botu Discord sunucunuza davet ederek veya onunla etkileşime girerek aşağıda belirtilen şartları kabul etmiş sayılarsınız.

---

## 📊 1. TOPLANAN VE İŞLENEN VERİLER
Styx Bot, yalnızca siber güvenlik, moderasyon ve yapay zeka sohbet özelliklerini eksiksiz yerine getirebilmek adına Discord API'si üzerinden gelen en minimum verileri anlık olarak işler:
* **Kullanıcı Bilgileri:** Kullanıcı adları, benzersiz Discord ID numaraları, profil fotoğrafları ve sunucu içi takma adlar (Nicknames).
* **Sunucu Bilgileri:** Sunucu isimleri, Sunucu ID'leri, kanal adları ve üye sayıları.
* **Mesaj İçeriği:** Sunucularda siber asayişi korumak amacıyla kurulan log sisteminde silinen/düzenlenen mesajların takibi ve belirlenen yapay zeka kanallarında Google Gemini API hattına sorgu gönderilebilmesi amacıyla mesaj içerikleri *sadece anlık işlem bazlı* okunur.

---

## 💾 2. VERİ SAKLANMASI VE GÜVENLİĞİ
* Tüm sunucu yapılandırmaları ve log parametreleri, özel Windows VDS sunucumuz bünyesinde barındırılan yerel ve şifreli bir veri tabanında (`quick.db`) güvenle tutulmaktadır.
* Kullanıcıların mesaj içerikleri kesinlikle harici bir bulut sunucusunda **ÖMÜR BOYU SAKLANMAZ**, üçüncü şahıslarla paylaşılmaz ve reklam/pazarlama amacıyla işlenmez.
* Yapay zeka sorguları, doğrudan resmi Google Gemini API entegrasyonu üzerinden anlık olarak yanıtlanır ve işlem bittiği salise aktif bellekten tamamen temizlenir.

---

## 🔄 3. KULLANICI HAKLARI VE VERİ SİLME TALEBİ
* Sunucu sahipleri botu sunucularından çıkardıkları andan itibaren, o sunucuya ait tüm aktif veri işleme süreçleri saniyeler içinde otomatik olarak durdurulur.
* Herhangi bir kullanıcı veya sunucu sahibi, veri tabanımızda saklanan yapılandırma verilerinin kalıcı olarak kazınmasını resmi **Styx Destek Karargahı** üzerinden bizimle iletişime geçerek manuel olarak talep edebilir. Veriler 24 saat içinde tamamen yok edilir.

---

*Styx Bot, Discord Geliştirici Politikaları uyarınca topluluğunuzun gizliliğini korumayı taahhüt eder. Güvenliğiniz bizim en yüksek önceliğimizdir.*

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 🛡️ STYX BOT — PRIVACY POLICY & DATA PROTECTION

This document outlines the Privacy Policy and Data Security standards for **Styx Bot** ("Bot"). By inviting the Bot to your Discord server or interacting with it, you agree to the terms described below.

---

## 📊 1. COLLECTED AND PROCESSED DATA
Styx Bot only processes minimal data provided via the Discord API to fulfill its security, moderation, and AI chat features:
* **User Information:** Usernames, unique Discord User IDs, avatars, and server nicknames.
* **Server Information:** Server names, Server IDs, channel names, and member counts.
* **Message Content:** Message content is processed *strictly on an instantaneous basis* for two features: delivering prompts to the Google Gemini API in designated AI channels and logging deleted/edited messages within the server's private audit log channel.

---

## 💾 2. DATA STORAGE AND SECURITY
* All server configurations and logging parameters are stored securely inside a local, encrypted database (`quick.db`) hosted on our private Windows VDS server.
* Message contents are **NEVER** stored permanently, logged on external servers, or used for any advertising/tracking purposes. 
* AI queries are passed instantly through the official Google Gemini API framework and are wiped from the active runtime memory immediately after a response is generated.

---

## 🔄 3. USER RIGHTS AND DATA DELETION
* Server administrators can remove the Bot at any time, which immediately ceases all active data processing for that specific guild.
* Any user or server owner can request a manual, permanent wipe of their stored configuration data from our database by contacting the development team directly at the official **Styx Support Fortress** on Discord.

---

*Styx Bot is committed to protecting your community's privacy under Discord's Developer Policies. Your security is our highest priority.*
