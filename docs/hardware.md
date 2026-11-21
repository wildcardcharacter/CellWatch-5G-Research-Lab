# Hardware Overview

[Deutsche Fassung](#deutsch)

## English

### Ettus USRP B210

**Planned role:** Primary SDR platform for suitable 5G laboratory experiments.

Key characteristics relevant to planning:
- 2 transmit and 2 receive channels (2x2 MIMO).
- Up to 56 MHz instantaneous bandwidth.
- Requires a compatible host system, UHD drivers and suitable software configuration.

The B210 is not automatically suitable for every 5G band or channel configuration. Validate frequency range, duplexing mode, bandwidth, clocking, host throughput and software support before designing an experiment.

### HackRF One

**Planned role:** Supplementary RF observation and spectrum-analysis device.

The HackRF One is a half-duplex transceiver with a single channel and a maximum sample rate of 20 MS/s. It is useful for RF learning and selected spectrum experiments, but it is not a substitute for a capable 5G gNodeB radio platform.

### Test equipment

- Owned 5G-capable test devices.
- Test SIM cards and credentials dedicated to the private lab.
- Suitable RF cables, attenuators and terminations for conducted experiments.
- A shielded enclosure or other compliant RF containment solution where appropriate.
- Stable host workstation and storage for logs and experiment records.

### Pre-experiment checklist

- Confirm the experiment is authorized and legally compliant.
- Prefer conducted RF connections or receive-only/offline analysis.
- Verify attenuation, power levels, connectors and termination.
- Confirm that no unintended RF energy can reach public networks.
- Record hardware model, serial-independent lab asset label, firmware and driver versions.

## Deutsch

### Ettus USRP B210

**Geplante Aufgabe:** Primäre SDR-Plattform für geeignete 5G-Laborversuche.

Für die Planung relevante Eigenschaften:
- 2 Sende- und 2 Empfangskanäle (2x2 MIMO).
- Bis zu 56 MHz momentane Bandbreite.
- Benötigt ein kompatibles Hostsystem, UHD-Treiber und eine passende Softwarekonfiguration.

Die B210 ist nicht automatisch für jedes 5G-Frequenzband und jede Kanal-Konfiguration geeignet. Frequenzbereich, Duplexverfahren, Bandbreite, Taktung, Host-Datenrate und Softwareunterstützung müssen vor dem Versuchsaufbau geprüft werden.

### HackRF One

**Geplante Aufgabe:** Ergänzendes Werkzeug zur RF-Beobachtung und Spektrumanalyse.

Der HackRF One ist ein Halbduplex-Transceiver mit einem Kanal und einer maximalen Abtastrate von 20 MS/s. Er eignet sich zum Lernen und für ausgewählte Spektrumanalysen, ersetzt aber keine leistungsfähige 5G-gNodeB-Funkplattform.

### Testausrüstung

- Eigene 5G-fähige Testgeräte.
- Test-SIM-Karten und Zugangsdaten ausschließlich für das private Labor.
- Geeignete RF-Kabel, Dämpfungsglieder und Abschlüsse für leitungsgebundene Versuche.
- Bei Bedarf ein abgeschirmtes Gehäuse oder eine andere geeignete HF-Eindämmung.
- Leistungsfähiger Host-Rechner und Speicherplatz für Logs und Versuchsprotokolle.

### Checkliste vor einem Experiment

- Genehmigung und rechtliche Zulässigkeit des Versuchs prüfen.
- Leitungsgebundene RF-Verbindungen oder reine Offline-Analyse bevorzugen.
- Dämpfung, Pegel, Anschlüsse und Abschlusswiderstände kontrollieren.
- Sicherstellen, dass keine unbeabsichtigte HF-Abstrahlung öffentliche Netze erreicht.
- Hardwaremodell, interne Inventarbezeichnung, Firmware und Treiberversion dokumentieren.
