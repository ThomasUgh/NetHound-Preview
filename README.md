# 🐺 NetHound v2.6

<div align="center">

**Professional Network & Security Reconnaissance Suite**

Eine umfassende Desktop-Anwendung für Security Checks und Penetration Tester.  
Gebaut mit Electron für Windows, Linux & macOS.

![NetHound Banner](https://img.shields.io/badge/Version-2.6-00d9ff?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey?style=for-the-badge)

**⚠️ Private Project - Preview Only**

</div>

---

## 📸 Preview

<table>
<tr>
<td width="50%">

### Tool-Übersicht
![NetHound Tools Overview](https://i.ibb.co/BV4t7j1T/323232332.png)
*62+ Tools in 8 Kategorien organisiert*

</td>
<td width="50%">

### Tool-Details
![Tool Cards](https://i.ibb.co/cSgDMpWV/23r3.png)
*Jedes Tool mit Beschreibung und Kategorisierung*

</td>
</tr>
<tr>
<td width="50%">

### Subdomain Finder in Aktion
![Subdomain Finder](https://i.ibb.co/QFKxNTHd/dddw.png)
*DNS Enumeration mit Brute-Force und Web-Scraping*

</td>
<td width="50%">

### Einstellungen & Anpassung
![Settings](https://i.ibb.co/v4v51mK8/13133.png)
*Multi-Language, Dark/Light Mode, Kategorieverwaltung*

</td>
</tr>
</table>

---

## ✨ Eigenschaften - v2.6

🌍 **Multi-Language Support** - Vollständig auf Deutsch & Englisch  
🌓 **Dark & Light Mode** - Neon-Theme mit Farbakzenten  
⭐ **Favoriten-System** - Schnellzugriff auf häufig genutzte Tools  
📊 **Flexible Ergebnisanzeige** - Formatiert, JSON oder Raw  
💾 **Export-Funktionen** - JSON, CSV, TXT  
🚀 **Custom Tools** - Eigene Tool-Entwicklung möglich  
🔌 **Hybrid-Architektur** - Eigene REST-Endpoints + Browser-basierte Suche + Externe APIs

---

## 🏗️ Architektur

NetHound nutzt einen **hybriden Ansatz** für maximale Flexibilität:
```
┌─────────────────────────────────────────────────┐
│           NetHound Frontend (Electron)          │
│  ┌──────────────────────────────────────────┐   │
│  │   React UI + Tailwind CSS + Lucide      │   │
│  └──────────────────────────────────────────┘   │
└──────────────┬──────────────────────────────────┘
               │
        ┌──────┴──────┬──────────────┬─────────────┐
        │             │              │             │
  ┌─────▼─────┐ ┌────▼────┐  ┌──────▼──────┐ ┌───▼────┐
  │  Eigene   │ │ Browser │  │  Externe    │ │ Direct │
  │   REST    │ │ Scraper │  │    APIs     │ │  DNS   │
  │ Endpoints │ │         │  │             │ │ Lookup │
  └───────────┘ └─────────┘  └─────────────┘ └────────┘
       │             │              │              │
       └─────────────┴──────────────┴──────────────┘
                         │
              ┌──────────▼──────────┐
              │  Ergebnis-Parser    │
              │  & Formatierung     │
              └─────────────────────┘
```

---

## 🎯 Features im Detail

### ⭐ Favoriten-System
Markiere häufig genutzte Tools als Favoriten für Schnellzugriff

### 📊 Ergebnis-Formate
- **Formatted** - Übersichtliche Tabellen und Karten
- **JSON** - Maschinenlesbar für Weiterverarbeitung
- **Raw** - Unveränderte API-Antworten

### 💾 Export-Optionen
- JSON für Automation
- CSV für Excel/Sheets
- TXT für Reports

### 🔧 Custom Tools
Erstelle eigene Tools durch Kombination bestehender Funktionen


---

## 📜 License

MIT License - **Thomas U.**
```
Made with ❤️ by Thomas U. • NetHound v2.6
```

---

<div align="center">

**NetHound** - *Sniffing out the truth, one packet at a time* 🐺

</div>
