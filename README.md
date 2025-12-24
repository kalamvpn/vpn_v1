<div align="center">

# 🚀 VPN_v1 – Auto Installer VPS (Hysteria)

🔥 **One Click Install • Stable • Powerful** 🔥  

Script auto-installer VPN berbasis **Hysteria** untuk VPS Linux.  
Dirancang untuk **sekali install, langsung online**, cocok untuk personal maupun komersial.

---

⭐ **Fast • Simple • Clean** ⭐

</div>

---

## 🧩 Tentang Project
**VPN_v1** adalah script installer otomatis yang memudahkan deploy VPN Hysteria di VPS.  
Tanpa ribet, tanpa konfigurasi manual berantakan, dan siap dikembangkan ke level **provider VPN profesional**.

---

## ✨ Fitur Unggulan
✅ Auto install Hysteria  
✅ Input domain, port, auth & obfs saat instalasi  
✅ Struktur script modular & rapi  
✅ Menu system siap pakai  
✅ Cocok untuk VPS fresh install  
✅ Mudah dikembangkan (multi user, web panel, dll)

---

## 📁 Struktur Repository
```text
vpn_v1/
├── main.sh                # Entry point installer
├── install-histeria.sh    # Core installer Hysteria
├── menu.zip               # Menu system
├── system.zip             # File system pendukung
└── README.md
---

🖥️ Sistem Operasi Didukung
Ubuntu 20.04
Ubuntu 22.04
Debian 10 / 11
⚠️ Disarankan VPS fresh install
🚀 Instalasi (One Command)
Login ke VPS
Salin kode
Bash
ssh root@IP_VPS
Jalankan Installer
Salin kode
Bash
wget https://raw.githubusercontent.com/kalamvpn/vpn_v1/main/main.sh
chmod +x main.sh
./main.sh
⚙️ Konfigurasi Saat Instalasi
Installer akan meminta:
🌐 Domain
🔢 Port
🔐 Auth Password
🛡️ Obfs Password
📌 Pastikan:
Domain sudah pointing ke IP VPS
Port belum digunakan service lain
🔧 Manajemen Service
Salin kode
Bash
systemctl status hysteria
systemctl restart hysteria
systemctl stop hysteria
🛠️ Roadmap Pengembangan
Web Admin Panel (port 9090)
Login admin (user & password)
Create & manage user VPN
Limit user & bandwidth
Monitoring service
API authentication
📞 Kontak & Support
💬 WhatsApp: +62 858-4699-5601
🔗 https://wa.me/6285846995601
Fast response untuk:
Instalasi
Custom script
Pengembangan fitur
⚠️ Disclaimer
Project ini dibuat untuk edukasi dan administrasi server pribadi.
Segala bentuk penyalahgunaan di luar tanggung jawab author.
👤 Author
kalamvpn
⭐ Dukung Project
Jika project ini membantu:
⭐ Star repository
🍴 Fork & kembangkan
🤝 Pull Request sangat diterima
🔥 Build your VPN like a pro 🔥
