# Planen, Vorbereiten u Durchführen von Arbeitsaufgaben.....

# Netzknotenplan


## Übersicht
Ein Netzknotenplan ist eine grafische Darstellung der Netzwerktopologie, die die verschiedenen Netzwerkknoten und deren Verbindungen zeigt.

## Legende
- **Router:** Geräte, die den Datenverkehr zwischen verschiedenen Netzwerken leiten.
- **Switch:** Geräte, die Datenpakete innerhalb eines lokalen Netzwerks weiterleiten.
- **Server:** Computer oder Systeme, die Dienste, Ressourcen oder Daten bereitstellen.
- **Firewall:** Sicherheitsvorrichtungen, die den Datenverkehr überwachen und regulieren, um Netzwerksicherheit zu gewährleisten.

## Netzknotenplan

```plaintext
  +------------+         +------------+
  |   Router   | ------- |   Switch   |
  +------------+         +------------+
         |                      |
         |                      |
  +------------+         +------------+
  |   Server   |         |  Firewall  |
  +------------+         +------------+
  ```

## Details

### 1. **Router**
- **Name:** Router 1
- **IP-Adresse:** 192.168.1.1
- **Verbindungen:** Switch, Internet


### 2. **Switch**
- **Name:** Switch 1
- **Anzahl der Ports:**  24
- **Verbindungen:** Router, Server, Firewall


### 3. **Server**
- **Name:** Server 1
- **IP-Adresse:** 192.168.1.2
- **Dienste:** Web, Datenbank


### 4. **Firewall**
- **Name:** Firewall 1
- **IP-Adresse:** 192.168.1.3
- **Einstellungen:** Inbount / Outbund Traffic, Security Policies