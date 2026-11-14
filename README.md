# Geoinformationssysteme WS 26/27

## EP. 01 | UE 1 | Einführung in QGIS
### Wo Berlin ungleich ist: Sozialstruktur 2025 nach Planungsräumen

<img width="3507" height="2480" alt="image" src="https://github.com/user-attachments/assets/2bf1c7b3-736a-428d-85ce-eaa5cf74f06a" />

### Verteilung des sozialen Status in der Hauptstadt

Die Karte visualisiert die Berliner Sozialstruktur 2025 auf Basis der 542 Lebensweltlich orientierten Planungsräume (LOR). Durch die Klassifizierung in vier Statusklassen (von „sehr niedrig“ bis „hoch“) wird deutlich, wie ungleiche Lebensverhältnisse räumlich ungleich in der Stadt verteilt sind. Als Grundlage dienen zentrale Indikatoren wie das verfügbare Einkommen, Arbeitslosigkeit, Transferleistungsbezug sowie Kinderarmut.

### Methodischer Ansatz:

Die räumliche Verschneidung und kartografische Aufbereitung erfolgte vollständig in QGIS. Die Einstufung der Planungsräume macht soziale Brennpunkte ebenso wie einkommensstärkere Quartiere auf einen Blick lesbar und zeigt das reale Gefälle innerhalb der Metropole.


## EP. 01 | UE 2 | Datenklassifikation
### Objekt betrachtet? – Bevölkerungsverteilungen in Berlins LOR (2019)

<img width="3507" height="2480" alt="image" src="https://github.com/user-attachments/assets/584cc788-eb41-4c01-865f-44f31174c0e9" />

### Vier Karten, vier Methoden: Wie die Statistik das Bild prägt

Dieselben Rohdaten zur Bevölkerung Berlins erzeugen je nach gewählter Klassifikationsmethode ein völlig anderes optisches und statistisches Ergebnis. Der Vergleich gegenübergestellt sind: absolute Bevölkerungszahlen, die Bevölkerungsdichte nach Jenks (natürliche Brüche), nach Quantilen sowie in gleichen Intervallen.

### Erkenntnis der Methode:

Während absolute Zahlen vor allem dichte Wohnquartiere und große Flächen betonen, offenbaren klassifizierte Dichtekarten ganz unterschiedliche Cluster und Konzentrationen. Die Wahl der Klassengrenzen beeinflusst maßgeblich, welche Stadtteile als „hochbelastet“ oder „dünn besiedelt“ wahrgenommen werden – ein essenzielles Werkzeug für eine objektive raumplanerische Analyse.

## EP. 03 | Standortanalyse
### Konfliktfreier Raum für Großveranstaltungen – Potenzialflächen für ein Open-Air-Festival in Berlin


### Wo in Berlin lassen sich geeignete Flächen für ein lärmintensives Open-Air-Festival finden?

Die Karte identifiziert sechs geeignete Großflächen im Berliner Stadtgebiet (zwischen 13,4 ha und 176,1 ha in Spandau, Reinickendorf, Steglitz-Zehlendorf, Charlottenburg-Wilmersdorf, Mitte und Tempelhof-Schöneberg), die sämtliche Lärmschutz-, Umwelt- und Infrastrukturkriterien erfüllen. Durch die Gegenüberstellung der allgemeinen Freiflächen und der finalen Eignungsstandorte wird deutlich, wie stark besonders die notwendige ÖPNV-Anbindung und Mindestflächengröße das Potenzial eingrenzen.

### Methodischer Ansatz:

Die räumliche Verschneidung und Pufferanalyse erfolgte vollständig in QGIS im metrischen Koordinatensystem ETRS89 / UTM Zone 33N (EPSG:25833) auf Grundlage von OpenStreetMap- und Geoportal-Berlin-Daten. Mittels boolescher Differenz-Operationen wurden Sperrzonen (500 m Abstand zu Wohngebieten, 300 m zu Naturschutzgebieten sowie Wasserflächen) ausgeschlossen und anschließend mit einem 1.000-m-ÖPNV-Einzugsbereich sowie einer Mindestfläche von 2,0 Hektar gefiltert.
