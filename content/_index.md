+++
outputs = ["Reveal"]
title = "Basiskarte"

+++
{{< slide class="title-slide" background="#fee08b" >}}
### Der Weg zur modernen Basiskarte
#### Potenziale und Herausforderungen von Kartographie und Datengrundlage  

 <font size="4">Hannes Blitza (terrestris), Christian Fremd (Stadtmessungsamt Stuttgart)</font>
<div>
  <img src="img/fossgis_logo.png" width="20%" class="plain" />
</div>

---
{{< slide transition-speed="slow" >}}
#### Gliederung
1. Anforderung an eine Basemap
2. Technische Umsetzung
3. Anforderungen an die Ausgangsdaten
4. Kartenbeispiele
5. Potenziale
6. Fazit, Ausblick und Übertragbarkeit

---
{{< slide class="terrestris" >}}
#### terrestris
<div class="twoSides">
  <div>
    <img src="img/terrestris-logo-normal.svg" width="250px" class="plain" /><br/>
    <div class="iconLine">
      <i class="fa fa-envelope fa-sm"></i>info@terrestris.de
    </div>
    <div class="iconLine">
      <i class="fa fa-github fa-sm"></i><a href="https://www.github.com/terrestris">@terrestris</a>
    </div>
    <div class="iconLine">
      <i class="fa fa-twitter fa-sm"></i><a href="https://twitter.com/terrestrisde">@terrestrisde</a>
    </div>
  </div>
  <div>
    - OpenSource GIS aus Bonn<br/>
    - Entwicklung, Projekte<br/>
    - Support/Schulung<br/>
    - Beratung, Planung, Implementierung & Wartung  <br/>
    - u.a. GeoServer, OL, MapProxy, react-geo, QGIS
  </div>
</div>

---
#### Hannes Blitza
<div class="twoSides">
  <div>
    <img src="img/hbl.jpg" class="plain" /><br/>
    <div class="iconLine">
      <i class="fa fa-envelope fa-sm"></i>blitza@terrestris.de
    </div>
    <div class="iconLine">
      <i class="fa fa-github fa-sm"></i><a href="https://www.github.com/hblitza">@hblitza</a>
    </div>
  </div>
  <div>
    - MSc. Geographie<br/>
    - Mitarbeiter bei terrestris <br/>
    - Front-End Development & Training <br/>
    - MA-Thesis: <em>Agentenbasierte Modellierung von Radverkehr (Open Data gestützter Ansatz)</em>
</div>

---
#### Christian Fremd
<div class="twoSides">
  <div>
    <img src="img/cfremd.jpg" height="200px" class="plain" /><br/>
    <div class="iconLine">
      <i class="fa fa-envelope fa-sm"></i>christian.fremd@gmail.com
    </div>
  </div>
  <div>
    - Dipl.-Ing. (FH) Kartographie und Medientechnik<br/>
    - Mitarbeiter beim Stadtmessungsamt Stuttgart <br/>
    - Kartographie und GIS-Analysen
  </div>
</div>

---
#### Anforderungen an Basiskarten

- maßstabsübergreifendes Kartenwerk als Referenz und Orientierungshilfe
- unaufdringliches, modernes und frisches Kartenbild
- Farbwahl und Kontrast lässt Raum für thematische Inhalte
- für Bürger und auch Fachanwender
- zur Verwendung im städtischen Geoportal und anderen GIS-Systemen

---
#### Basemaps auf der FOSSGIS/FOSS4G

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

---
<section data-background-iframe="ol1.html" data-background-interactive>
</section>

---
<section data-background-iframe="ol1-1.html" data-background-interactive>
</section>

---
#### Technische Umsetzung
<img src="img/gpkg.png" width="116px" class="plain" />  
{{% fragment %}} <img src="img/gs.svg" width="400px" class="plain" /> {{% /fragment %}}  
{{% fragment %}} <img src="img/geostyler-logo-full.svg" width="400px" class="plain" /> {{% /fragment %}}
<!-- - Datenformat
- Vektortiles vs. Rastertiles  
- Kartenrenderer  
- Stilformat
- Ausgabeformat -->

---
#### Workflow
<img src="img/technische_umsetzung.svg" width="50%" class="plain" />

---
#### Anforderungen an die Ausgangsdaten
- in den kleinen Maßstäben die topografischen Zusammenhänge darstellen und den Eindruck der Bebauungsstruktur vermitteln  
- in den großen Maßstäben lagetreue Darstellung der Einzelgebäude aus dem Liegenschaftskataster  
- Datenaktualität Aktualisierungszyklus der Karte

---
#### Anforderungen an die Ausgangsdaten
- Als Datenquellen stehen uns zur Verfügung:
  <div class="normal-lineheight">
    <img src="img/LGL-StadtS-OSM-Logos.png" width="80%" class="plain" />
  </div>
  <div class="data_logo normal-lineheight">
    <div>
      ATKIS
    </div>
    <div>
      ALKIS
    </div>
    <div>
      OSM
    </div>
  </div>

- amtliche Inhalte
- OSM-Straßennetz
- Topologie
- Labeling

---

<section data-background-iframe="ol2.html" data-background-interactive>
</section>

---
#### Potenziale
-- Vectortiles (kurz: Wichtigsten Vorteile nennen)  
-- Geostyler (Konvertieren der Stilregeln, Bsp: Orka-MV (carto -> QGIS qml))  
-- GeoSynchronicer  

---
#### Fazit
- Reibungslose Kombination der etablierten FOSS-Tools und OGC-Standards

- Sowohl unter rechtlichen Aspekten (ODbL ermöglicht viele Freiheiten) als auch unter technischen Aspekten funktioniert das Zusammenspiel gut (hohe Flexibilität der OSM-Datenstruktur)

- Herausforderungen liegen in der maßsstabsübergreifenden Darstellung, jedoch durch hohe Flexibilität der Datengrundlage kompensierbar

---
{{< slide class="title-slide" background="#fee08b" >}}
### Vielen Dank für das Interesse!
