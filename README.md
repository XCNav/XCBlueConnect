# XCBlueConnect – Serial Bluetooth & WiFi Bridge

**Kompakte, leistungsstarke serielle Datenbrücke für die Luftfahrt**  
Gemeinsam entwickelt von [XCNav](https://www.xcnav.de) und Foresight Avionics.

BlueConnect ermöglicht die **drahtlose Übertragung** von z. B. FLARM-NMEA-Daten an moderne Flug-Apps, Navigationssysteme und Displays – ganz ohne Kabelsalat. Gleichzeitig versorgt der integrierte USB-C-Anschluss (max. 0,5 A) Geräte wie XCRemote oder Smartphones mit Strom.

Ideal für Segelflieger, Motorsegler- und Ultraleichtpiloten, die Zuverlässigkeit, einfache Bedienung und maximale Kompatibilität schätzen.

---

## Hauptfunktionen

### Doppelte serielle Schnittstelle
- **Hardware Serial S1** – Primärer serieller Ein-/Ausgang (TCP-Port **4352**)
- **Hardware Serial S2** – Zweiter serieller Ein-/Ausgang oder konfigurierbar als Weiterleitung des S1-Signals (z. B. an FLARM-Display) (TCP-Port **4353**)

### Stromversorgung
- Integrierter **12 V → 5 V** Wandler  
- Max. **0,5 A** über USB-C (z. B. für Handy, XCRemote)

### Drahtlose Übertragungswege
| Protokoll              | Details                                      | Kompatibilität                          |
|------------------------|----------------------------------------------|-----------------------------------------|
| **WiFi TCP**           | Gleichzeitige Weiterleitung von bis zu 2 Quellen (Ports 4352 & 4353) | SeeYou Mobile, XCSoar, Oudie, Naviter u. a. |
| **Classic Bluetooth**  | SPP-Profil „BlueConnect“                     | Android, die meisten Navis              |
| **Bluetooth Low Energy (BLE)** | Nordic UART Service (NUS)               | SeeYou Navigator                        |
| **GDL 90**             | Traffic- + Heartbeat-Sender per UDP Broadcast (Port **4000**) | Garmin Pilot, ForeFlight u. a.         |

### Integrierte Webkonfiguration
Moderne WebApp im Access-Point-Modus mit folgenden Einstellmöglichkeiten:
- Baudrate Serial S1 + S2 (inkl. **Auto-Baud-Erkennung**)
- Pin-Swap & Signal-Invertierung
- Serial S2 als Input oder Weiterleitung der S1-Daten
- Bluetooth-Modus (Aus / Classic / BLE)
- Auto-WiFi nach Timeout
- GDL 90 ein-/ausschalten

### FLARM-Konfigurationsmodus
Vollständige Fernkonfiguration des angeschlossenen FLARM-Geräts über die Weboberfläche:
- Alle **PFLAC**-Parameter lesen und schreiben
- IGC-Flugbuch auflisten und Flüge herunterladen
- **FLARM-Reichweitenanalyse** – Echtzeit-Auswertung empfangener Kontakte (Richtung, Distanz, Höhe) zur Optimierung von Antenne und Reichweite

### Weitere Highlights
- OTA-Update-fähig (Firmware + Webdateien über die WebApp)
- Unterstützt **FLARM Classic** und **PowerFLARM**
- Automatische Baudratenerkennung
- Konfigurierbare WiFi-Passwörter
- Sehr geringer Stromverbrauch
- Kompakte Bauform

---

## Einsatzbereiche
- Segelflug
- Motorsegler
- Ultraleichtflug
- Motorflug (mit FLARM)
- Schulungsbetrieb
- Wettbewerbsfliegerei

---

## Typische Anwendungen
- FLARM → XCSoar / SeeYou / LK8000 / Oudie kabellos
- FLARM-Daten an Garmin Pilot / ForeFlight (via GDL 90)
- Versorgung von XCRemote oder Tablet über USB-C
- Paralleler Betrieb eines FLARM-Displays über Serial S2
- Fernkonfiguration und IGC-Download vom FLARM

---

## Technische Daten (Kurzübersicht)

| Eigenschaft              | Wert                          |
|--------------------------|-------------------------------|
| Serielle Schnittstellen  | 2 × Hardware RS232 (S1/S2)   |
| TCP-Ports                | 4352 (S1), 4353 (S2)         |
| GDL 90                   | UDP Broadcast Port 4000      |
| Stromversorgung          | 12 V Eingang → 5 V / 0,5 A USB-C |
| Bluetooth                | Classic SPP + BLE (NUS)      |
| WiFi                     | Access Point + TCP Bridge    |
| Konfiguration            | WebApp im AP-Modus           |
| Updates                  | OTA über WebApp              |
| Kompatibilität           | FLARM Classic & PowerFLARM   |

---

## Installation & Inbetriebnahme
1. Gerät an FLARM (oder andere serielle Quelle) und 12-V-Versorgung anschließen.
2. Access Point verbinden und WebApp öffnen.
3. Baudrate, Bluetooth-Modus und weitere Parameter einstellen.
4. Mit gewünschter App (XCSoar, SeeYou Navigator, ForeFlight …) verbinden.

Detaillierte Anleitungen und Handbücher findest du auf der [Produktseite](https://www.xcnav.de/product-page/bt-wifi-serial-adapter-xcvario).

---

## Kauf
**Preis:** 59,99 € (inkl. MwSt., zzgl. Versand)  
→ [Direkt im XCNav-Shop bestellen](https://www.xcnav.de/product-page/bt-wifi-serial-adapter-xcvario)

---

## Entwickelt von
**XCNav** in Zusammenarbeit mit **Foresight Avionics**

---

## Lizenz & Hinweise
Dieses Repository dient der Dokumentation und Community-Unterstützung des Produkts XCBlueConnect.  
Firmware und Hardware sind proprietär. Bei Fragen zum Gerät wende dich bitte an den Hersteller.

---

*BlueConnect verbindet dein FLARM-Gerät kabellos mit der modernen Avionik-Welt – einfach, zuverlässig und zukunftssicher.*
