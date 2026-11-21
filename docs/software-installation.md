# Software Installation Plan

[Deutsche Fassung](#deutsch)

## English

This document tracks the intended software stack. Exact package versions and installation commands will be added after compatibility has been checked against Debian 13 and the selected hardware.

| Component | Intended role | Status |
|---|---|---|
| Debian 13 Trixie | Lab workstation OS | Planned baseline |
| UHD | USRP B210 driver and utilities | To be validated |
| srsRAN Project | 5G RAN/gNodeB software | To be evaluated |
| Open5GS | 5G Core network | To be evaluated |
| GNU Radio | SDR signal-processing environment | Planned |
| Wireshark | Protocol and packet analysis | Planned |
| Python 3 | Automation and analysis | Planned |
| SQLite | Initial local data store | Planned |
| PostgreSQL | Optional scalable data store | Later phase |

### Installation principles

1. Record Debian release, kernel and hardware details.
2. Prefer distribution packages where they meet project requirements.
3. Use upstream documentation for version-sensitive components.
4. Avoid mixing incompatible repositories or driver versions.
5. Record commands, versions and configuration changes in lab notes.
6. Never place credentials or SIM secrets in tracked configuration files.

## Deutsch

Dieses Dokument erfasst den geplanten Software-Stack. Konkrete Paketversionen und Installationsbefehle werden ergänzt, sobald die Kompatibilität mit Debian 13 und der ausgewählten Hardware geprüft wurde.

| Komponente | Aufgabe | Status |
|---|---|---|
| Debian 13 Trixie | Betriebssystem des Laborrechners | Geplante Basis |
| UHD | Treiber und Werkzeuge für USRP B210 | Zu prüfen |
| srsRAN Project | 5G-RAN-/gNodeB-Software | Zu evaluieren |
| Open5GS | 5G-Core-Netz | Zu evaluieren |
| GNU Radio | SDR-Signalverarbeitung | Geplant |
| Wireshark | Protokoll- und Paketanalysen | Geplant |
| Python 3 | Automatisierung und Analyse | Geplant |
| SQLite | Erste lokale Datenbank | Geplant |
| PostgreSQL | Optionale skalierbare Datenbank | Spätere Phase |

### Installationsgrundsätze

1. Debian-Version, Kernel und Hardware erfassen.
2. Distributionspakete bevorzugen, sofern sie die Anforderungen erfüllen.
3. Für versionsabhängige Komponenten die Upstream-Dokumentation heranziehen.
4. Inkompatible Paketquellen und Treiberversionen nicht vermischen.
5. Befehle, Versionen und Konfigurationsänderungen in Laborprotokollen dokumentieren.
6. Zugangsdaten und SIM-Geheimnisse niemals in versionierten Konfigurationsdateien speichern.
