# DTM SoSe 2026

## EP01 | Dasymetrische Chloroplethenkarten

<img width="1055" height="742" alt="Berlin" src="https://github.com/user-attachments/assets/d1bbd573-1f33-432c-a38b-b695b21828e0" />
In dieser Aufgabe wurden drei verschiedene Methoden zur Darstellung der Bevölkerungsverteilung in Berlin erstellt und miteinander verglichen. Dazu zählen eine absolute und eine relative Choroplethenkarte sowie eine dasymetrische Choroplethenkarte. Während die absolute Darstellung die Gesamtzahl der Einwohner pro Gebiet zeigt und die relative Darstellung die Bevölkerungsdichte (Einwohner pro km²) abbildet, verteilt die dasymetrische Darstellung die Bevölkerungszahlen ausschließlich auf tatsächlich bewohnte bzw. bebaute Flächen. Dadurch werden unbewohnte Gebiete wie Wälder, Gewässer oder große Grünflächen nicht in die Darstellung einbezogen. Anschließend wurden alle drei Karten in einem gemeinsamen Layout nebeneinander angeordnet, um die Unterschiede der Darstellungsformen direkt vergleichen zu können. So wird deutlich, wie sich die Wahl der Darstellung auf die Interpretation der Bevölkerungsverteilung auswirkt und welche Methode ein realistischeres Bild der tatsächlichen Siedlungsstruktur Berlins vermittelt.

## EP.02 | Gitterchoroplethenkarten
Für die zweite Arbeitsaufgabe wurde das Thema Gitterchoroplethenkarten anhand einer rasterbasierten Karte auf Grundlage eines Datensatzes über Kirschbäume in Berlin visualisiert. Um die räumliche Verteilung unabhängig von administrativen Grenzen darzustellen, wurden die einzelnen Standorte der Kirschbäume in einem 500m-Hexagongitter zusammengefasst. Hexagone ohne Baumbestand (Wert 0) wurden dabei aus der Darstellung entfernt. Die Farbgebung der verbleibenden Hexagone gibt entsprechend der Legende Auskunft über die absolute Anzahl der Kirschbäume pro Rasterzelle. Durch das gleichmäßige Gitter werden städtische Muster und Dichte-Hotspots präzise sichtbar gemacht, wobei die Methode fehlerhafte Interpretationen durch unterschiedlich große Verwaltungseinheiten vermeidet und somit ein räumlich vergleichbares Bild der Baumverteilung liefert.

<img width="2382" height="1684" alt="kirschbaeume_neue_karte_v2" src="https://github.com/user-attachments/assets/9cafbd5a-9a65-489d-bf5a-11e781f7e78b" />

## EP03 | Punktrasterkarten
Bei dieser Darstellung handelt es sich um eine gestalterische Erweiterung der ursprünglichen Hexagonkarte. Bei identischer Datengrundlage und unveränderter Klassifizierung der Baumanzahl wurde die Kartografie angepasst: Anstelle der Hexagone visualisieren nun themenbezogene Kirschblütensymbole die Daten. Durch das gewählte Dark-Mode-Layout kommen die abgestuften Rottöne der Symbole besonders stark zur Geltung.

<img width="921" height="759" alt="karte_blau_gelb" src="https://github.com/user-attachments/assets/f90b4a11-4f3c-4022-9e3e-2ec03a88f9c5" />

## EP 04 | Value-by-alpha-mapping
Neben den einzelnen Choroplethenkarten für Fidesz und Tisza kombiniert eine Value-by-Alpha-Karte beide Wahlergebnisse: Die Farbe zeigt die stärkste Partei im Bezirk, die Deckkraft spiegelt die Deutlichkeit des Sieges wider. Je größer der Abstand zwischen den Parteien, desto kräftiger erscheint der Farbton.

<img width="4960" height="3507" alt="Ungarn_Wahlen_2026_Layout" src="https://github.com/user-attachments/assets/dadeb954-6d90-46c6-b219-b39d97c5e70c" />

## EP05 | Ursprung Ziel Karten
Für das Thema der Ursprung-Ziel-Karten wurden zwei Darstellungen auf einer Globusprojektion erstellt. Die erste Karte beschäftigt sich mit den Fluchtbewegungen aus der Ukraine im Jahr 2025, während die zweite Karte dieses Konzept aufgreift und bezieht sie auf den Internationalen Studentenaustausch an der BHT. Deshalb die beiden gewählten Zentren Kyjiw und BHT. Von diesen Zentren führen Verbindungslinien zu den jeweiligen Zielländern. Zusätzlich sind die Zielländer mit Punkten markiert, wobei die Farbgebung und Dicke der Linien und Punkte entsprechend der Legende die Anzahl der geflohenen Personen repräsentieren. Ein großer Vorteil dieser Methodik liegt darin, dass räumliche Bewegungsströme und globale Vernetzungen anschaulich und intuitiv dargestellt werden können. Ein Nachteil ist jedoch das visuelle Durcheinander, bei sehr vielen Zielorten überlagern sich die Linien stark um das Ursprungsland herum, wodurch einzelne Verbindungen unübersichtlich werden und genaue Zahlenwerte schwer abzulesen sind.

<img width="3507" height="2480" alt="image" src="https://github.com/user-attachments/assets/b0539249-5c4e-4f85-8c7a-1894c3d816ec" />

<img width="813" height="824" alt="image" src="https://github.com/user-attachments/assets/fc317fe7-1282-41bf-b1cb-19af540b1112" />

## EP06 | Tilemaps
Die folgenden Karten zum Thema Tilemaps zeigen das Höhenrelief Berlins sowie das Höhenrelief Deutschlands im Lego-Stil. Hierfür wurde die jeweilige Region mit einem gleichmäßigen Hexagongitter abgedeckt, wobei die einzelnen Kacheln durch Noppen mit der Beschriftung „BHT“ optisch wie Lego-Bausteine gestaltet wurden. Die Farbgebung der Hexagone gibt dabei entsprechend die durchschnittliche Höhe innerhalb des jeweiligen Rasterfeldes wieder. Diese Karten zeichnen sich durch eine stark vereinfachte Visualisierung aus, welche komplexe Topografien intuitiv und ansprechend vermittelt. Durch das einheitliche Raster bleiben die Einheiten zudem räumlich perfekt vergleichbar. Diese starke Generalisierung macht die Karte zwar sehr anschaulich, führt jedoch dazu, dass feine Details wie einzelne Erhebungen oder Täler verloren gehen. Um solche Details abzubilden, wären sehr kleine Hexagone nötig, wodurch die Übersichtlichkeit verloren ginge. Dies macht die Methodik für präzise geografische Analysen ungeeignet.

<img width="851" height="748" alt="Berlin_Lego" src="https://github.com/user-attachments/assets/294d68e4-dc4b-45a9-b96f-eabf1ef67a6d" />

<img width="2000" height="2814" alt="Deutschland_Klemmbausteine_Karte" src="https://github.com/user-attachments/assets/65595e32-8e3d-4eb4-843c-8fc201c01348" />

## EP.07 | Animation in QGIS
In dieser Aufgabe haben wir eine zeitbasierte Animation zur Darstellung von Meteorbeobachtungen erstellt. Auf Grundlage von Daten des Global Meteor Network wurden die einzelnen Meteore als leuchtende Streifen mit Kometenschweif-Effekt minutengenau auf einer dunkel gehaltenen Karte Frankreichs dargestellt. Hierbei wurde der räumliche Ausschnitt gezielt eingegrenzt, um die Datenmenge zu reduzieren, da höhere Datenmengen zu technischen Problemen führten. Der große Vorteil von Kartenanimationen liegt in der anschaulichen Darstellung zeitlicher und räumlicher Dynamiken, so lassen sich Bewegungen und Richtungen der Sternschnuppen wesentlich intuitiver erfassen als in einer statischen Karte. Der Nachteil besteht jedoch im hohen Rechen- und Speicheraufwand sowie in der fehlenden dauerhaften Übersicht. So müssen Betrachter die Animation aufmerksam verfolgen, da Informationen im Zeitverlauf immer wieder auftauchen und verschwinden.
<img width="1364" height="1006" alt="geminiden_frankreich" src="https://github.com/user-attachments/assets/16f00196-c2f8-4ede-aa79-2987aa07fc8d" />


## EP08 | Mesh-Daten

## EP09 | 3D-Gebäudemodelle

## 2,5D
Der erste Ausschnitt zeigt die Ortschaft Trefurt in einer 2,5D-Darstellung. Hierbei werden 2D-Gebäudegrundrisse anhand von Höhenattributen vertikal aufgespannt, während die Bezugsfläche flach bleibt. Zusätzlich wurden die Gebäude eingefärbt und teiltransparent gemacht, um die Gebäudestruktur zu verdeutlichen. Dabei ist ein großer Vorteil der 2,5D-Darstellung der geringe Rechenaufwand bei gleichzeitig verbesserter räumlicher Wahrnehmung von Gebäudehöhen und -dichten. Allerdings fehlen dabei echte Geländestrukturen sowie Neigungswinkel.

<img width="920" height="551" alt="TimTim" src="https://github.com/user-attachments/assets/8d60db30-124f-4519-a4eb-4b183ead54a3" />

## 3D
Eine realistisch eingefärbte 3D-Darstellung von Frankenberg verbindet Gebäude mit einem digitalen Geländemodell und Luftbildern, um die Topografie präzise abzubilden. Dank der hohen Anschaulichkeit ist dieses Modell perfekt für Sichtachsen- und Stadtbildanalysen geeignet. 

<img width="900" height="658" alt="timtim3D2" src="https://github.com/user-attachments/assets/44929a93-9fe5-43cb-9218-95ce54c20cfe" />


