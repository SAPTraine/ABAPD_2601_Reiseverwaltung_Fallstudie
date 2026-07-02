# Fallstudie C_ABAPD_2601 – Reiseverwaltung

## ABAP Cloud, CDS, RAP, OData V4 und EML

Diese Fallstudie beschreibt die Entwicklung einer ABAP-Cloud-Anwendung zur Verwaltung von Reisen.

Die Anwendung basiert ausschließlich auf eigenen `Z*`-Objekten und orientiert sich fachlich an den SAP-Demo-Datenquellen:

```text
/DMO/TRAVEL
/DMO/AGENCY
```

SAP-Demo- oder Standardobjekte werden nicht verändert.

---

## Szenario

Sie entwickeln für ein Reiseunternehmen eine kleine Travel-Management-Anwendung.

Die Anwendung soll Reisen:

- anlegen
- ändern
- prüfen
- mit Reisebüro-Stammdaten verbinden
- über einen OData-V4-Service bereitstellen
- in der Fiori Elements Preview anzeigen
- per EML testen

---

## Inhalt der Fallstudie

Die Anwendung umfasst:

- eigene Travel-Tabelle
- Draft-Tabelle
- CDS View Entities
- Association zu Agency-Daten
- Analytics View
- RAP Managed Business Object mit Draft
- OData-V4-Service
- Fiori Elements Preview
- EML-Testklasse

---

## Fachliche Orientierung

Die Fallstudie orientiert sich an:

```text
/DMO/TRAVEL
/DMO/AGENCY
/DMO/CL_DATA_GENERATOR_MANAGED
```

Die Demo-Objekte werden nur als Orientierung verwendet und nicht verändert.

---

## Namenskonvention

Der Platzhalter `##` ist durch eine individuelle Arbeitskennung zu ersetzen.

Beispiel:

```text
ZTRAVEL## → ZTRAVEL01
```

---

## Dokumentation

Der vollständige Teilnehmerauftrag befindet sich unter:

```text
docs/teilnehmerauftrag.md
```

Zusätzlich kann die PDF-Version abgelegt werden unter:

```text
docs/C_ABAPD_2601_Teilnehmerauftrag_Reiseverwaltung.pdf
```

---

## Projektstruktur

```text
ABAPD_2601_Reiseverwaltung_Fallstudie/
│
├── README.md
│
├── docs/
│   ├── teilnehmerauftrag.md
│   ├── C_ABAPD_2601_Teilnehmerauftrag_Reiseverwaltung.pdf
│   └── C_ABAPD_2601_GitHub_Deutsche_Version.pdf
│
├── src/
│   ├── tabellen/
│   ├── cds_views/
│   ├── rap_behavior/
│   ├── klassen/
│   └── service/
│
└── tests/
    └── eml/
```

---

## Ergebnis

Am Ende liegt eine lauffähige ABAP-Cloud-Anwendung vor.

Die Anwendung enthält eine eigene Travel-Tabelle, eine Draft-Tabelle, CDS View Entities, eine Association zu Agency-Daten, eine Analytics View, ein RAP Managed Business Object mit Draft, einen OData-V4-Service, eine Fiori Elements Preview und eine EML-Testklasse.
