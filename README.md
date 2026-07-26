# 🎯 eJPT-Notes (eLearnSecurity Junior Penetration Tester Çalışma Notları) 🐧

![eJPT Study Notes Banner](banner.png)

eJPT (eLearnSecurity Junior Penetration Tester) sınavı hazırlık sürecinde tutulmuş, tamamen düzenli, çalıştırılabilir terminal komutları ve zafiyet analizleri içeren Türkçe çalışma notları deposudur.

---

## 📂 Not İçeriği

Repository içinde yer alan ve ders çalışma sürecini kolaylaştırmak için renkli, bol emojili ve tablolu hale getirilmiş not dosyaları:

### 1. [1.Bash Notes.md](1.Bash%20Notes.md) 💻
Linux komut satırına (CLI) dair tüm temel kavramlar:
* 🧭 Dizin Gezinmesi ve Konum Bilgisi (`pwd`, `ls`, `cd` vb.)
* 📁 Dosya ve Klasör Yönetimi (`mkdir`, `touch`, `cp`, `mv`, `rm` vb.)
* 📝 Dosya İçeriklerini Okuma/Düzenleme (`cat`, `less`, `head`, `tail`, `nano`)
* 🔍 Arama, Filtreleme ve Borulama (`grep`, `find`, `wc`, `|`, `>`, `>>`)
* 🔐 Detaylı Kullanıcı Yetki ve İzin Yapısı (`chmod`, `chown`, `sudo`, Oktal/Sembolik izin mantığı)
* ⚙️ Süreç Yönetimi (`ps`, `top`, `kill`)

### 2. [2.Http Details.md](2.Http%20Details.md) 🌐
HTTP Protokolü ve web güvenliğine giriş:
* 📜 HTTP İstek Yöntemleri (`GET`, `POST`, `PUT`, `DELETE` vb.)
* 🚦 HTTP Durum Kodları (1xx, 2xx, 3xx, 4xx, 5xx aralıkları ve anlamları)
* 📌 En yaygın karşılaşılan kodlar (`200`, `201`, `301`, `302`, `400`, `401`, `403`, `404`, `405`, `500`, `503`)

### 3. [3.Guided Pentest: Web.md](3.Guided%20Pentest:%20Web.md) 💀
Aşama aşama, gereksiz anlatımlardan arındırılmış, pratik bir web sızma testi (RecruitX) walkthrough rehberi:
* 🕵️‍♂️ Bilgi Toplama ve Port Tarama (`nmap`, `curl`, `gobuster`)
* 🔑 IDOR Zafiyeti Tespiti ve Yetkisiz Erişim
* 📤 Dosya Yükleme Kısıtlamalarını Atlatma (File Upload Bypass via `.phtml`)
* ✏️ Web Shell Oluşturma (`nano` adımları dahil) & Uzaktan Kod Çalıştırma (RCE)
* 🔄 Netcat ile Etkileşimli Ters Kabuk (Reverse Shell) Alma

### 4. [4.Nmap.md](4.Nmap.md) 🛡️
Ağ tarama aracı Nmap'in tüm kritik detayları ve soru-cevapları:
* 📋 Tüm popüler Nmap anahtar parametreleri (Switches)
* ⚙️ TCP Bayraklarının (`SYN`, `ACK`, `RST`, `FIN`) anlamları ve el sıkışma mantığı
* 🚦 Tarama Türleri (`-sT`, `-sS`, `-sU`, `-sN`, `-sF`, `-sX`) ve SOC/SIEM sistemlerinde yakalanma/log durumları
* 📊 Tarama türleri karşılaştırma tablosu (Windows uyumluluğu, açık/kapalı port tepkileri)
* 🐍 Nmap Scripting Engine (NSE) kullanımı ve script veritabanı araması
* 📝 TryHackMe Nmap Odası (Görev 14) soru-cevap anahtarı

---

## 💡 Neden Bu Notlar?

* 🎨 **Okunabilirlik:** Karmaşık metinler yerine tablolar, emojiler ve listeler kullanılarak çalışması keyifli hale getirilmiştir.
* 🚀 **Doğrudan Uygulanabilir:** Teorik kısımlar yerine doğrudan çalıştırılabilir terminal komutları ve komut parametreleri açıklanmıştır.
* 🛡️ **Güvenlik Odaklı:** Taramaların sadece nasıl yapıldığı değil, arka planda hangi ağ paketlerini ürettiği ve savunma sistemlerine (IDS/Firewall) nasıl yakalandığı gösterilmiştir.
