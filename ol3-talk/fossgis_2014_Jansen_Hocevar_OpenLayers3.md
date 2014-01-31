# OpenLayers 3 – Einführung, Verwendungsbeispiele und technische Highlights
## Marc Jansen & Andreas Hocevar

OpenLayers ist eine OpenSource JavaScript Kartenbibliothek mit sehr großer Verbreitung, sowohl innnerhalb von OSGeo-Projekten als auch in privaten wie öffentlichen Webseiten und Internet-/Intranet-Applikationen. Die 2.x-er Versionen der Software werden bis zum heutigen Tage weiterentwickelt und gepflegt. Doch natürlich nagt der Zahn der Zeit auch an OpenLayers: Entwickler und Anwender haben 2014 verständlicherweise andere Ansprüche an digitale Kartenbibliotheken, als dies vor 8 Jahren der Fall war.
Bereits seit einiger Zeit wird daher von der Entwicklergemeinde an OpenLayers 3 gearbeitet, zum Zeitpunkt der Einreichung dieses Artikel ist die aktuellste Version 3.0.0.beta.1.

### Was ist neu bei OpenLayers3?

OpenLayers3 (ol3) wurde von Grund auf neu entwickelt und daher ist de facto alles neu an der Bibliothek.

Architektur, closure
neue renderer
mobile from start
Was noch

### Was bleibt gleich?

Auch wenn der Code neu geschrieben wurde, so sind doch die Ziele hinter OpenLayers unverändert:

1. Vielseitig: Die Bibliothek soll zahlreiche Verwendungsmöglichkeiten erlauben
2. Modern: html5 apis, webGl, css3
3. Performant: filesize, internal code
4. Erweiter- und anpassbar:
5. Harmonische API
6. Standardkonform: OGC
7. Cross-Browser: IE 9+
8. Cross-Platform: mobile und desktop
9. Verlässlich: Getestet & stabil
10. Gut dokumentiert: 

### Verwendungsbeispiele

* Beispiel: super simple (API!)
* Beispiel: igc (50.000 vertizes)
* Beispiel: drag drop image (formate & interaktiv)

* OpenGeoSuite (pluggable + standards + Product ready)

* swisstopo (realworld)
  * Code https://github.com/geoadmin/mf-geoadmin3
  * URL http://map.geo.admin.ch/
  * ol3, Angular JS + Bootstrap

### Technische Highlights

* Layer spy + layer swipe
  * Events und Canvas2D
  * postcompose
  * precompose

* d3 example
  * ol.layer.Image
  * Zusammenspiel mit 3rd party

* layergroup
  * gemeinsame API
  * Bildmanipulation WebGL


### Kontakt zu den Autoren:

Marc Jansen<br/>
terrestris GmbH & Co. KG<br/>
Pützchens Chaussee 56<br/>
53227 Bonn<br/>
+49 228 – 962 899 53<br/>
jansen@terrestris.de

Andreas Hocevar<br/>
Boundless<br/>
222 Broadway, 19th Floor<br/>
New York, NY 10038, USA<br/>
+1 877 – 673-6436<br/>
ahocevar@boundlessgeo.com


### Literatur

todo
