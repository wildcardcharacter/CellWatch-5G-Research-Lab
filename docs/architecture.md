# CellWatch Lab Architecture

[Zur deutschen Fassung springen](#deutsch)

## English

### Purpose

This document describes the intended high-level architecture of the CellWatch 5G Research Lab. It is a design baseline, not a claim that all components are already installed or operational.

### Main building blocks

1. **User Equipment (UE):** Owned 5G test phones and test SIM profiles.
2. **Radio Access Network:** srsRAN Project provides the software RAN/gNodeB component.
3. **SDR hardware:** Ettus USRP B210 is the primary planned radio platform, subject to band, bandwidth and configuration compatibility.
4. **5G Core:** Open5GS provides core-network functions for the private test environment.
5. **RF analysis:** HackRF One is a supplementary receive/analysis platform. It is not treated as a standalone 5G base station.
6. **CellWatch:** A planned collection, normalization, analysis and reporting layer for lab-generated observations.
7. **Storage:** SQLite for an initial lightweight prototype; PostgreSQL may be introduced as requirements grow.

### Data flow

Lab observations may include configuration metadata, application logs, protocol traces and RF measurements. Data should be collected only from the lab's own equipment and authorized test environment. The CellWatch layer will normalize selected observations, attach timestamps and experiment identifiers, and store derived results for review.

### Design principles

- Keep the test network isolated from public mobile networks.
- Separate RF measurement tools from RAN and core-network services.
- Record experiment configuration and software versions for reproducibility.
- Minimize stored data and avoid collecting real subscriber information.
- Prefer offline analysis of recorded test data where live RF transmission is unnecessary.
- Keep secrets, SIM credentials and private keys out of Git.

## Deutsch

### Zweck

Dieses Dokument beschreibt die geplante Gesamtarchitektur des CellWatch 5G Research Lab. Es dient als technische Ausgangsbasis und bedeutet nicht, dass bereits alle Komponenten installiert oder betriebsbereit sind.

### Zentrale Komponenten

1. **User Equipment (UE):** Eigene 5G-Testtelefone und dafür vorgesehene Test-SIM-Profile.
2. **Radio Access Network:** Das srsRAN Project stellt die Software-RAN-/gNodeB-Komponente bereit.
3. **SDR-Hardware:** Die Ettus USRP B210 ist als primäre Funkplattform vorgesehen. Die konkrete Eignung hängt von Frequenzband, Bandbreite und Konfiguration ab.
4. **5G Core:** Open5GS stellt die Kernnetzfunktionen für die private Testumgebung bereit.
5. **RF-Analyse:** Der HackRF One dient ergänzend zum Empfang und zur Analyse. Er wird nicht als alleinige 5G-Basisstation betrachtet.
6. **CellWatch:** Eine geplante Ebene zur Erfassung, Normalisierung, Analyse und Darstellung von Beobachtungen aus dem Labor.
7. **Datenspeicherung:** Zunächst SQLite; bei wachsenden Anforderungen kann PostgreSQL hinzukommen.

### Datenfluss

Laborbeobachtungen können Konfigurationsmetadaten, Anwendungslogs, Protokollmitschnitte und RF-Messwerte umfassen. Erfasst werden ausschließlich Daten aus eigener Hardware und autorisierten Testumgebungen. CellWatch soll ausgewählte Beobachtungen vereinheitlichen, mit Zeitstempeln und Experimentkennungen versehen und für die spätere Auswertung speichern.

### Entwurfsgrundsätze

- Das Testnetz bleibt von öffentlichen Mobilfunknetzen isoliert.
- RF-Messwerkzeuge werden von RAN- und Core-Diensten getrennt betrachtet.
- Konfigurationen und Softwareversionen werden für reproduzierbare Experimente dokumentiert.
- Daten werden minimiert; echte Teilnehmerdaten werden nicht gesammelt.
- Wo keine Live-Funkaussendung erforderlich ist, wird aufgezeichnetes Testmaterial offline analysiert.
- Zugangsdaten, SIM-Geheimnisse und private Schlüssel gehören nicht ins Git-Repository.
