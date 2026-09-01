# HomeLab Splunk SIEM

Project homelab ini merupakan kelanjutan dari HomeLab SOC Analyst (Wazuh), fokus pada implementasi **Splunk Enterprise** sebagai SIEM untuk deteksi serangan, analisis log, dan incident response.

---

## 👤 Tentang Saya

Saya seorang IT enthusiast dengan background Network Engineer, sedang memperdalam security operations. Project ini bagian dari perjalanan belajar mandiri saya untuk menguasai berbagai platform SIEM yang umum dipakai di industri.

- **LinkedIn:** [Mhd Iqbal](https://www.linkedin.com/in/mhd-iqball/)
- **Email:** mhdibll17@gmail.com

---

## 🎯 Tujuan Project

- Mengimplementasikan Splunk Enterprise sebagai SIEM kedua setelah Wazuh
- Konfigurasi log forwarding dari Windows & Linux endpoint
- Melakukan simulasi serangan MITRE ATT&CK dan menganalisis deteksinya
- Membuat custom alert, dashboard, dan report
- Melatih skill Splunk SPL (Search Processing Language)

---

## 🏗️ Arsitektur

- **Splunk Indexer:** Ubuntu 22.04 — 192.168.20.60
- **Dashboard:** http://192.168.56.x:8000
- **Forwarder:**
  - Windows Server (192.168.20.10)
  - Windows 11 (192.168.30.10)
  - DVWA (192.168.20.40)
- **Attacker:** Kali Linux (192.168.10.100)

---

## 🛠️ Tools

| Kategori | Tools |
|----------|-------|
| SIEM | Splunk Enterprise 9.x |
| Log Forwarder | Splunk Universal Forwarder |
| Endpoint | Sysmon, Windows Event Log |
| Simulasi Serangan | Kali Linux (Nmap, Hydra, Metasploit, Mimikatz) |
| Framework | MITRE ATT&CK |

---

## 📂 Struktur Project

| Folder | Deskripsi |
|--------|-----------|
| `01-splunk-setup` | Instalasi & konfigurasi Splunk |
| `02-detection-engineering` | Simulasi serangan & analisis deteksi |
| `03-incident-response` | Case management & laporan |
| `diagrams` | Diagram arsitektur |

---

## 🚀 Progress

- [ ] Setup VM Splunk
- [ ] Install Splunk Enterprise
- [ ] Konfigurasi Forwarder
- [ ] Simulasi 6 case serangan
- [ ] Custom alert & dashboard
- [ ] Dokumentasi

---

## 📌 Catatan

Project ini dibangun untuk pembelajaran di lingkungan lab terisolasi. Seluruh konfigurasi telah disamarkan.