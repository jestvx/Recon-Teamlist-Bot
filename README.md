# 🤖 Teamlist Bot für Discord

Ein einfacher Discord-Bot, der automatisch eine Teamliste als Embed-Nachricht in einem bestimmten Channel anzeigt und aktualisiert. Ideal für Community- oder Roleplay-Server!

## 🔧 Funktionen

- Zeigt eine Embed-Teamliste basierend auf Rollen
- Unterstützt benutzerdefiniertes Design (Farben, Titel, Footer, etc.)
- Manuelles Aktualisieren per Befehl `!update`
- Rechteüberprüfung für Update-Befehl
- Bild und Autorinformationen im Embed

---

## 📥 Bot herunterladen

> **Der Bot steht über Discord zur Verfügung.**  
> Erhalte Zugriff auf den Download über unseren [Support-Discord](https://discord.gg/DEININVITE).

---

## 📦 Installation (Node.js)

1. **Dateien vom Discord herunterladen und entpacken**

2. **Abhängigkeiten installieren**
   Stelle sicher, dass du [Node.js](https://nodejs.org/) installiert hast:

   ```bash
   npm install
   ```

3. **Konfiguration anpassen**
   Bearbeite die `config.json` Datei:

   ```json
   {
     "botToken": "DEIN_BOT_TOKEN",
     "licensekey": "RECON-XXX",
     "guildId": "DISCORD_SERVER_ID",
     "channelId": "CHANNEL_ID",
     "messageId": "MESSAGE_ID_FÜR_TEAMLISTE",

     "rollen": [
       "ROLLEN_ID_1",
       "ROLLEN_ID_2"
     ],

     "embedTitle": "📋 Aktuelle Teamliste",
     "embedColor": "#00D8C0",
     "embedFooter": "Zuletzt aktualisiert:",
     "embedImage": "URL_ZUM_BILD",
     "embedAuthorName": "Recon Service",
     "embedAuthorIcon": "URL_ZUM_ICON",

     "updateCommand": "!update",
     "noPermissionMessage": "🚫 Keine Rechte dafür!",
     "updateSuccessMessage": "🔁 Teamliste wurde aktualisiert!",
     "noMembersText": "• Niemand"
   }
   ```

4. **Bot starten**
   ```bash
   node index.js
   ```

---

## 🛠 Befehle

- `!update` – aktualisiert die Teamliste
  - Nur für Nutzer mit Berechtigung (z. B. Admins)
  - Antwort bei Erfolg oder fehlender Berechtigung wird automatisch gesendet

---


## ❗ Lizenz

Dieser Bot benötigt einen Lizenzschlüssel (`licensekey`). Stelle sicher, dass du einen gültigen Key hast, bevor du den Bot einsetzt.

---

## 📬 Support

Bei Fragen oder Problemen melde dich im [Support-Discord](https://discord.gg/reconservice) oder öffne ein Issue.

---
