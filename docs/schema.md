# Metadatenschema für KI-Recherche-Tools

## Pflichtfelder
- id
- name
- cost_type
- data_basis
- libkey
- url
- last_checked

## Optionale Felder
- data_basis_url
- category
- short_description
- notes

## Feldbeschreibung

### name
Name des Tools.

### cost_type
Kostentyp, z. B.:
- kostenlos
- teilweise kostenlos
- kostenpflichtig
- Freemium

### data_basis
Welche Datenbasis das Tool verwendet, z. B.:
- Semantic Scholar
- Open Web
- eigene Indexdaten
- gemischt

### data_basis_url
- URL zur Datenbasis

### category
- KI-Suche (Literatur finden)
- KI-Analyse & Extraktion (Verknüpfungen entdecken)
- KI-Visualisierung (Literatur vergleichen)
- KI-Zusammenfassung (Mit PDFs chatten)

### libkey
Ob LibKey-Anbindung vorhanden ist:
- `true`
- `false`

### url
Offizielle URL des Tools.

### last_checked
Datum der letzten Prüfung im Format `YYYY-MM-DD`.
