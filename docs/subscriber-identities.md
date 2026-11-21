# Subscriber Identities: SUPI and SUCI

[Deutsche Fassung](#deutsch)

## English

This document introduces identity-protection concepts for study within the private lab. Experiments should use synthetic or dedicated test identities only.

- **SUPI (Subscription Permanent Identifier):** A permanent subscriber identifier used within the 5G system.
- **SUCI (Subscription Concealed Identifier):** A concealed representation designed to protect the SUPI when it is transmitted over the radio interface, according to the applicable protection scheme.
- **Home network:** Holds the subscription context and the key material used by the relevant protection mechanisms.

### Research questions

- What privacy objective does SUCI provide?
- Which protection scheme and parameters are configured in a test environment?
- What metadata remains observable even when the permanent identifier is concealed?
- How should logs and captures be sanitized before publication?

Do not collect or publish identifiers belonging to real subscribers.

## Deutsch

Dieses Dokument führt in die Identitätsschutzkonzepte ein, die im privaten Labor untersucht werden können. Experimente verwenden ausschließlich synthetische oder eigens vorgesehene Testidentitäten.

- **SUPI (Subscription Permanent Identifier):** Eine dauerhafte Teilnehmerkennung innerhalb des 5G-Systems.
- **SUCI (Subscription Concealed Identifier):** Eine geschützte Darstellung, die die SUPI bei der Übertragung über die Funkschnittstelle gemäß dem verwendeten Schutzverfahren verbergen soll.
- **Heimnetz:** Verwaltet den Teilnehmerkontext und das Schlüsselmaterial der entsprechenden Schutzmechanismen.

### Forschungsfragen

- Welches Datenschutz-Ziel verfolgt SUCI?
- Welches Schutzverfahren und welche Parameter sind in der Testumgebung konfiguriert?
- Welche Metadaten bleiben sichtbar, obwohl die dauerhafte Kennung verborgen wird?
- Wie müssen Logs und Mitschnitte vor einer Veröffentlichung bereinigt werden?

Kennungen realer Teilnehmer dürfen weder gesammelt noch veröffentlicht werden.
