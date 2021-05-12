+++
outputs = ["Reveal"]
title = "Basiskarte"

+++
{{< slide class="title-slide" background="#e6f598" transition-speed="slow" >}}
### Der Weg zur modernen Basiskarte
#### Potenziale und Herausforderungen von Kartographie und Datengrundlage  

 <font size="4"> Christian Fremd (Stadtmessungsamt Stuttgart), Hannes Blitza (terrestris) </font>

---
{{< slide background="#66c2a5" transition-speed="slow" >}}
#### Gliederung
- Anforderung an eine Basemap
- Technische Umsetzung
- Anforderungen an die Ausgangsdaten
- Kartenbeispiele
- Potenziale
- Fazit und Ausblick

<footer>
  <div class="footer">
FOSSGIS 2021 - Der Weg zur Modernen Basiskarte. Herausforderungen und Potentiale
  </div>
</footer>

---
#### Anforderungen an Basiskarten

- maßstabsübergreifendes Kartenwerk als Referenz und Orientierungshilfe
- unaufdringliches, modernes und frisches Kartenbild
- Farbwahl und Kontrast lässt Raum für thematische Inhalte
- für Bürger und auch Fachanwender
- zur Verwendung im städtischen Geoportal und anderen GIS-Systemen

<footer>
  <div class="footer">
FOSSGIS 2021 - Der Weg zur Modernen Basiskarte. Herausforderungen und Potentiale
  </div>
</footer>

---
#### Basemaps auf der FOSSGIS

<style type="text/css">
.tg  {border:none;border-collapse:collapse;border-spacing:0;}
.tg td{border-style:solid;border-width:0px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;
  padding:10px 5px;word-break:normal;}
.tg th{border-style:solid;border-width:0px;font-family:Arial, sans-serif;font-size:14px;font-weight:normal;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-1wig{font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
.tg .tg-tf2e{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-1wig">Title</th>
    <th class="tg-1wig">Fokus</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax"><a href="https://media.ccc.de/v/fossgis2020-2988-map-editor-fr-individuelle-amtliche-vektorkarten">Map Editor für individuelle amtliche Vektordaten</a></td>
    <td class="tg-tf2e">VectorTiles, AdV MapEditor</td>
  </tr>
  <tr>
    <td class="tg-0lax"><a href="https://media.ccc.de/v/fossgis2019-567-osm-und-ffentliche-verwaltung-wie-geht-das-">OSM und öffentliche Verwaltung – Wie geht das?</a></td>
    <td class="tg-tf2e">ALKIS und OSM Daten</td>
  </tr>
  <tr>
    <td class="tg-0lax"><a href="https://media.ccc.de/v/fossgis2019-558-vektortiles-hinter-den-kulissen#t=12">Vektortiles hinter den Kulissen</a></td>
    <td class="tg-tf2e">VectorTiles</td>
  </tr>
  <tr>
    <td class="tg-0lax"><a href="https://media.ccc.de/v/fossgis2020-3082-osm-daten-mit-vektortiles-erfolgreich-nutzen#t=340">OSM-Daten mit Vektortiles erfolgreich nutzen</a></td>
    <td class="tg-tf2e">OpenMapTile, VectorTiles</td>
  </tr>
  <tr>
    <td class="tg-0lax"><a href="https://media.ccc.de/v/fossgis2020-3126-weniger-ist-mehr-zur-auswahl-darzustellender-elemente-in-der-digitalen-kartographie">Weniger ist mehr - zur Auswahl darzustellender Elemente in der digitalen Kartographie</a></td>
    <td class="tg-tf2e">OSM-Carto, Kartographie</td>
  </tr>
  <tr>
    <td class="tg-0lax"><a href="https://media.ccc.de/v/fossgis2020-3126-weniger-ist-mehr-zur-auswahl-darzustellender-elemente-in-der-digitalen-kartographie">Standing up a OSM clone with GeoServer and CSS</a></td>
    <td class="tg-tf2e">OSM-Clone, GeoServer, CSS, OpenMapTiles</td>
  </tr>
</tbody>
</table>

<footer>
  <div class="footer">
FOSSGIS 2021 - Der Weg zur Modernen Basiskarte. Herausforderungen und Potentiale
  </div>
</footer>

---
<section data-background-iframe="ol1.html" data-background-interactive>
</section>

<footer>
  <div class="footer">
FOSSGIS 2021 - Der Weg zur Modernen Basiskarte. Herausforderungen und Potentiale
  </div>
</footer>

---
#### Technische Umsetzung
- Datenformat
- Vektortiles vs. Rastertiles  
- Kartenrenderer  
- Stilformat
- Ausgabeformat

<footer>
  <div class="footer">
FOSSGIS 2021 - Der Weg zur Modernen Basiskarte. Herausforderungen und Potentiale
  </div>
</footer>

---
#### Workflow
<img src="img/technische_umsetzung.png" width="60%" class="img" />

<footer>
  <div class="footer">
FOSSGIS 2021 - Der Weg zur Modernen Basiskarte. Herausforderungen und Potentiale
  </div>
</footer>

---
#### Anforderungen an die Ausgangsdaten
- in den kleinen Maßstäben die topografischen Zusammenhänge darstellen und den Eindruck der Bebauungsstruktur vermitteln  
- in den großen Maßstäben lagetreue Darstellung der Einzelgebäude aus dem Liegenschaftskataster  
- Suche nach einem Straßennetz, dass beide Enden dieser Skala bedienen kann --> _OSM:highway_  

<footer>
  <div class="footer">
FOSSGIS 2021 - Der Weg zur Modernen Basiskarte. Herausforderungen und Potentiale
  </div>
</footer>

---
#### Anforderungen an die Ausgangsdaten
- OSM im kleinen Maßstab: Hauptverkehrsstraßen auswählen
OSM im großen Maßstab: viele Details, Einbahnstraßen  
- amtliche Inhalte die in der Karte auftauchen müssen: z.B. Hausnummern  
- Datenaktualität  Aktualisierungszyklus der Karte  
- Topologie: Ebenenreihenfolge Straßennetz  
- Priorisierung bei Labeling-Konflikten  

<footer>
  <div class="footer">
FOSSGIS 2021 - Der Weg zur Modernen Basiskarte. Herausforderungen und Potentiale
  </div>
</footer>

---

<section data-background-iframe="ol2.html" data-background-interactive>
</section>

<footer>
  <div class="footer">
FOSSGIS 2021 - Der Weg zur Modernen Basiskarte. Herausforderungen und Potentiale
  </div>
</footer>


---
#### Potentiale
-- Vectortiles (kurz: Wichtigsten Vorteile nennen)  
-- Geostyler (Konvertieren der Stilregeln, Bsp: Orka-MV (carto -> QGIS qml))  
-- GeoSynchronizer  

<footer>
  <div class="footer">
FOSSGIS 2021 - Der Weg zur Modernen Basiskarte. Herausforderungen und Potentiale
  </div>
</footer>

---
#### Fazit
- Zusammenspiel aus OSM und amtlichen Daten ist möglich und funktioniert gut  
- Zusammenspiel der etablierten OpenSource-Tools funktioniert gut  
(GeoServer, SLD, Geopackage, Rastertiles)  

<footer>
  <div class="footer">
FOSSGIS 2021 - Der Weg zur Modernen Basiskarte. Herausforderungen und Potentiale
  </div>
</footer>

---
Vielen Dank für das Interesse!


