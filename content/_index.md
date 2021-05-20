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
    - u.a. GeoServer, OL, MapProxy, react-geo, QGIS, SHOGun, GDAL
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

- <p class="shadow">maßstabsübergreifendes Kartenwerk<p/> als Referenz und Orientierungshilfe
- unaufdringliches, modernes und frisches Kartenbild
- Farbwahl und Kontrast lässt Raum für thematische Inhalte

---
#### Anforderungen an Basiskarten

<img src="img/6.1.jpg" class="plain" width="80%"/>

---
#### Anforderungen an Basiskarten

<img src="img/6.2.jpg" class="plain" width="80%"/>

---
#### Anforderungen an Basiskarten

<img src="img/6.3.jpg" class="plain" width="80%"/>

---
#### Anforderungen an Basiskarten
- <p class="shadow">maßstabsübergreifendes Kartenwerk</p> als Referenz und Orientierungshilfe
- unaufdringliches, modernes und frisches Kartenbild
- Farbwahl und Kontrast lässt Raum für thematische Inhalte
- für <p class="shadow">Bürger</p> und auch <p class="shadow">Fachanwender</p>
- zur Verwendung im <p class="shadow">städtischen Geoportal</p> und anderen GIS-Systemen

---

#### Basemaps auf der FOSSGIS/FOSS4G
<style type="text/css">
.tg  {border:none;border-collapse:collapse;border-spacing:0; width:100% !important}
.tg td{font-size: 20px !important;border-style:solid;border-width:0px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;
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
    <th class="tg-1wig">Autor(en)</th>
    <th class="tg-1wig">Fokus</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax"><a href="https://media.ccc.de/v/fossgis2020-2988-map-editor-fr-individuelle-amtliche-vektorkarten">Map Editor für individuelle amtliche Vektordaten</a></td>
    <td class="tg-tf2e">Sebastian Ratjens</td>
    <td class="tg-tf2e">VectorTiles, AdV MapEditor</td>
  </tr>
  <tr>
    <td class="tg-0lax"><a href="https://media.ccc.de/v/fossgis2019-567-osm-und-ffentliche-verwaltung-wie-geht-das-">OSM und öffentliche Verwaltung – Wie geht das?</a></td>
    <td class="tg-tf2e">Johannes Terwyen</td>
    <td class="tg-tf2e">ALKIS und OSM Daten</td>
  </tr>
  <tr>
    <td class="tg-0lax"><a href="https://media.ccc.de/v/fossgis2019-558-vektortiles-hinter-den-kulissen#t=12">Vektortiles hinter den Kulissen</a></td>
    <td class="tg-tf2e">Thomas Skowron</td>
    <td class="tg-tf2e">VectorTiles</td>
  </tr>
  <tr>
    <td class="tg-0lax"><a href="https://media.ccc.de/v/fossgis2020-3082-osm-daten-mit-vektortiles-erfolgreich-nutzen#t=340">OSM-Daten mit Vektortiles erfolgreich nutzen</a></td>
    <td class="tg-tf2e">Robert Klemm</td>
    <td class="tg-tf2e">OpenMapTile, VectorTiles</td>
  </tr>
  <tr>
    <td class="tg-0lax"><a href="https://media.ccc.de/v/fossgis2020-3126-weniger-ist-mehr-zur-auswahl-darzustellender-elemente-in-der-digitalen-kartographie">Weniger ist mehr - zur Auswahl darzustellender Elemente in der digitalen Kartographie</a></td>
    <td class="tg-tf2e">Christoph Hormann</td>
    <td class="tg-tf2e">OSM-Carto, Kartographie</td>
  </tr>
  <tr>
    <td class="tg-0lax"><a href="https://media.ccc.de/v/bucharest-245-standing-up-a-osm-clone-with-geoserver-and-css">Standing up a OSM clone with GeoServer and CSS</a></td>
    <td class="tg-tf2e">Andrea Aime</td>
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

---
#### Workflow
<img src="img/technische_umsetzung.svg" width="50%" class="plain" />

---
#### Anforderungen an die Ausgangsdaten
- in den kleinen Maßstäben die <p class="shadow">topografischen Zusammenhänge</p> darstellen und den Eindruck der Bebauungsstruktur vermitteln  
- in den großen Maßstäben <p class="shadow">lagetreue Darstellung</p> der Einzelgebäude aus dem Liegenschaftskataster  
- <p class="shadow">Aktualisierungszyklus</p> der Karte

---
#### Anforderungen an die Ausgangsdaten
- Als Datenquellen stehen uns zur Verfügung:
    <img src="img/LGL-StadtS-OSM-Logos.png" width="80%" class="plain" />
- amtliche Inhalte
- OSM-Straßennetz
- Topologie
- Labeling

---

<section data-background-iframe="ol2.html" data-background-interactive>
</section>
<section>
<h4>Labeling</h4>

<pre><code data-trim data-line-numbers>
                <ogc:Function name="Categorize">
                  <!-- Categorize label size according to scale -->
                  <ogc:Function name="env">
                    <ogc:Literal>wms_scale_denominator</ogc:Literal>
                  </ogc:Function>
                  <ogc:Literal>22</ogc:Literal>
                  <ogc:Literal>780</ogc:Literal>
                  ...
                </ogc:Function>
	</code></pre>
<pre><code data-trim data-line-numbers>
   <VendorOption name="followLine">true</VendorOption>
   <VendorOption name="maxDisplacement">50</VendorOption>
   <VendorOption name="repeat">300</VendorOption>
   <VendorOption name="group">yes</VendorOption>
</code></pre>
<pre><code data-trim data-line-numbers>
            <Geometry>
              <ogc:Function name="centroid">
                <ogc:PropertyName>geom</ogc:PropertyName>
              </ogc:Function>
            </Geometry>
</code></pre>
</section>
<section>
<h4>Straßennetz</h4>
<pre><code data-trim data-line-numbers>
        <sld:VendorOption name="sortBy">layer</sld:VendorOption>
        <sld:VendorOption name="ruleEvaluation">first</sld:VendorOption>
        <sld:VendorOption name="sortByGroup">roads</sld:VendorOption>
</code></pre>
<img src="img/roads-no-group.png" class="plain" height="60%" />
</section>

---
#### Potenziale
- <b>VectorTiles</b>
  - geringere Datenmengen
  - höhere  <p class="shadow">Flexibilität</p> beim Stylen (Symbologie, Labeling)
  -  <p class="shadow">Interaktivität</p> mit den Daten  
- <b>GeoStyler</b>
  - Eine UI für alle Style
  - Massenkonvertierung mit der GeoStyler-CLI
- <b>GeoSynchronicer</b>

---
#### Fazit
- Reibungsloses Zusammenspiel der etablierten <p class="shadow">FOSS-Tools</p> und OGC-Standards

- <p class="shadow">ODbL</p> ermöglicht viele Freiheiten

- zahlreiche Attribute bieten <p class="shadow">viel Flexibilität</p> bei Auswahl/Filtern

- Herausforderungen liegen in der maßsstabsübergreifenden Darstellung

- Workflow übertragbar auf andere Städte/Kommunen

---
{{< slide class="title-slide" background="#fee08b" >}}
### Vielen Dank für das Interesse!
<br/>
<br/>
Fragen?<br/>
blitza@terrestris.de | christian.fremd@gmail.com
