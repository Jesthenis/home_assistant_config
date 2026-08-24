# Home Assistant Configuration

Willkommen in meinem Repository für meine Home-Assistant-Infrastruktur. Hier dokumentiere ich meine Konfigurationen, Automatisierungen und Dashboards.

## 🛠 Hardware & Systeminfrastruktur

* **Host-Hardware:** Dell Wyse 5070 Thin Client
  * **Prozessor:** Intel Celeron J4105 (4 Cores @ 1.50 GHz / Burst 2.50 GHz)
  * **Arbeitsspeicher:** 16 GB DDR4 RAM (2x 8 GB Samsung Dual-Channel)
  * **Speicher:** 256 GB M.2 SATA SSD (Aufgerüstet)
* **Betriebssystem:** Home Assistant OS (HAOS) – Native Bare-Metal Installation
* **Netzwerk & Infrastruktur:**
  * **Router / Modem:** Telekom Speedport Smart 4 Plus (Glasfaser)
  * **Switch:** TP-Link Omada SG105E / ES205G (Managed Switch)
  * **Network Management:** TP-Link Omada Controller (gehostet als Add-on auf HAOS)
  * **Netzwerk-Segmentierung:** Dedizierte VLANs für IoT-Geräte und Smart-Home-Komponenten
* **Wallpanel:** Amazon Fire HD 8 via Fully Kiosk Browser & Kiosk Mode

## 📁 Repository-Struktur

* **`automations.yaml`** – Logiken, Trigger und Bedingungen für Smart-Home-Abläufe
* **`configuration.yaml`** – Haupteinstellungen, Systeminfrastruktur, Logging und Custom Sensors
* **`secrets.yaml.example`** – Vorlage für Umgebungsvariablen und Platzhalter
* **`.gitignore`** – Ausschlussfilter für sensible Systemdaten und Token

## 🔒 Datenschutz & Sicherheit
Aus Sicherheitsgründen sind alle IP-Adressen, API-Keys, Passwörter und Geodaten aus diesem Repository entfernt und in eine nicht-öffentliche `secrets.yaml` ausgelagert.

## 🖥 Wallpanel Dashboard
![Wallpanel Screenshot](Dashboard_Wallpanel_Anfang.jpg)
