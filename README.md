[README.md](https://github.com/user-attachments/files/29838640/README.md)
# 🤖 AI Procurement Assistant (RPA & LLM Entegrasyonu)

Bu proje, şirketlerin satınalma ve stok yönetim süreçlerindeki manuel e-posta trafiğini ve stok kontrollerini otomatize eden **uçtan uca bir RPA ve Yapay Zeka (AI)** çözümüdür.

## 🌟 Öne Çıkan Özellikler
* **E-posta Taraması:** Okunmamış satınalma talebi e-postalarını ve gönderen bilgilerini otomatik yakalar.
* **AI Metin Analizi:** Serbest metin halinde gelen talepleri LLM/AI modelleri ile analiz ederek yapılandırılmış veri formatına dönüştürür.
* **Dinamik Stok Kontrolü:** Excel/Veritabanı üzerindeki stok verilerini ve kritik eşik değerlerini anlık olarak okur.
* **A/B Senaryo Yönetimi:**
  * **Senaryo A:** Talep sahibine özel detaylı stok durum raporu hazırlar.
  * **Senaryo B:** Kritik eşiğin altına düşen ürünler için satınalma ekibine otomatik uyarı oluşturur.
* **Otomatik Yanıt:** Hazırlanan yanıtı doğrudan talebi ileten kişinin e-posta adresine dinamik olarak iletir.

## 🛠️ Teknolojiler
* **RPA:** UiPath Studio (Windows / VB.NET)
* **Veri Yönetimi:** DataTables, Dynamic Arguments, Excel Automation
* **Entegrasyonlar:** AI Prompts / Web API, SMTP Mail Automation

## 🚀 Kurulum & Çalıştırma
1. Bu depoyu klonlayın: `git clone https://github.com/KULLANICI_ADIN/AI-Procurement-Assistant.git`
2. UiPath Studio ile `project.json` dosyasını açın.
3. `input/stock.xlsx` dosyasındaki test verilerini kendi senaryolarınıza göre düzenleyin.
4. `Main.xaml` dosyasını çalıştırın.
