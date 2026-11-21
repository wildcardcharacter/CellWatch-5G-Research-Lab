# Security Research Scope and Lab Safety

[Deutsche Fassung](#deutsch)

## English

CellWatch is a defensive research project. Its scope is limited to owned equipment, dedicated test subscriptions, recorded sample data and environments for which the operator has explicit authorization.

### In scope

- Learning 5G architecture and security concepts.
- Studying SUPI/SUCI privacy protections using synthetic or dedicated lab test identities.
- Reviewing authentication and protocol behavior in the private test network.
- Detecting configuration errors and documenting defensive indicators.
- Building monitoring, parsing and reporting tools for lab-generated data.
- Reproducing findings with documented, controlled experiments.

### Out of scope

- Interacting with, impersonating or disrupting public mobile networks.
- Targeting third-party devices or subscribers.
- Collecting, decoding or retaining real subscriber identities or communications.
- Bypassing authentication or access controls on systems without explicit authorization.
- Transmitting on licensed spectrum without the required authorization.

### RF and regulatory precautions

RF shielding is an engineering containment measure, not a spectrum license. Before any transmission, determine which regulatory requirements and authorizations apply. If authorization is uncertain, do not transmit. Use conducted setups with appropriate attenuation, approved shielded facilities, receive-only measurements or offline recordings instead.

### Data handling

- Use synthetic identities and dedicated test credentials.
- Never commit SIM secrets, private keys, passwords or personal data.
- Keep raw captures private and minimize retention.
- Redact sensitive values from screenshots, logs and issue reports.
- Document the source and authorization basis for every dataset.

## Deutsch

CellWatch ist ein defensiv ausgerichtetes Forschungsprojekt. Der Umfang ist auf eigene Hardware, dedizierte Test-SIM-Karten, aufgezeichnete Beispieldaten und Umgebungen beschränkt, für die eine ausdrückliche Berechtigung vorliegt.

### Zulässiger Projektumfang

- Lernen und Dokumentieren von 5G-Architektur und Sicherheitskonzepten.
- Untersuchung der SUPI-/SUCI-Datenschutzmechanismen mit synthetischen oder eigens für das Labor vorgesehenen Testidentitäten.
- Analyse von Authentifizierungs- und Protokollabläufen im privaten Testnetz.
- Erkennen von Fehlkonfigurationen und Dokumentieren defensiver Indikatoren.
- Entwicklung von Monitoring-, Parser- und Reporting-Werkzeugen für Labordaten.
- Reproduzierbare und kontrollierte Experimente mit nachvollziehbarer Dokumentation.

### Nicht Bestandteil des Projekts

- Interaktion mit, Nachahmung oder Störung öffentlicher Mobilfunknetze.
- Gezielte Untersuchung fremder Endgeräte oder Teilnehmer.
- Erfassen, Dekodieren oder Speichern realer Teilnehmerkennungen oder Kommunikation.
- Umgehen von Authentifizierung oder Zugriffskontrollen ohne ausdrückliche Berechtigung.
- Aussendungen in genehmigungspflichtigen Frequenzbereichen ohne die erforderliche Erlaubnis.

### HF- und Rechtsvorkehrungen

Eine HF-Abschirmung ist eine technische Eindämmungsmaßnahme, aber keine Frequenzgenehmigung. Vor jeder Aussendung müssen die geltenden regulatorischen Anforderungen und erforderlichen Genehmigungen geklärt werden. Bei Unsicherheit wird nicht gesendet. Alternativen sind leitungsgebundene Aufbauten mit geeigneter Dämpfung, zugelassene abgeschirmte Einrichtungen, reine Empfangsmessungen oder Offline-Aufzeichnungen.

### Umgang mit Daten

- Synthetische Identitäten und dedizierte Testzugänge verwenden.
- Niemals SIM-Geheimnisse, private Schlüssel, Passwörter oder personenbezogene Daten committen.
- Rohmitschnitte privat halten und nur so lange wie nötig speichern.
- Sensible Werte aus Screenshots, Logs und Fehlerberichten entfernen.
- Herkunft und Berechtigungsgrundlage jedes Datensatzes dokumentieren.
