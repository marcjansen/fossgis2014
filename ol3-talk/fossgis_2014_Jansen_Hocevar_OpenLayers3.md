# OpenLayers 3 – Einführung, Verwendungsbeispiele und technische Highlights
## Marc Jansen & Andreas Hocevar

OpenLayers ist eine OpenSource JavaScript Kartenbibliothek mit sehr großer Verbreitung, sowohl innnerhalb von OSGeo-Projekten als auch in privaten wie öffentlichen Webseiten und Internet-/Intranet-Applikationen. Die 2.x-er Versionen der Software werden bis zum heutigen Tage weiterentwickelt und gepflegt. Doch natürlich nagt der Zahn der Zeit auch an OpenLayers: Entwickler und Anwender haben 2014 verständlicherweise andere Ansprüche an digitale Kartenbibliotheken, als dies vor 8 Jahren der Fall war.
Bereits seit einiger Zeit wird daher von der Entwicklergemeinde an OpenLayers 3 gearbeitet, zum Zeitpunkt der Einreichung dieses Artikel ist die aktuellste Version 3.0.0.beta.1.

### Was ist neu bei OpenLayers3?

OpenLayers3 (ol3) wurde von Grund auf neu entwickelt und daher ist de facto alles neu an der Bibliothek.

Das neue ol3 basiert auf der Funktionalität der JavaScript-Bibliothek Google Closure (https://developers.google.com/closure/library/), die auch in zahlreichen Google Produkten verwendet (etwa Gmail oder Google Maps) wird. Closure wird in ol3 vor allem verwendet, um das Klassensystem bereitzustellen, wiederkehrende Aufgaben (wie etwa HTML-Elementerzeugung, Eventhandling und DOM-Manipulation) zu lösen und um von der stärkestmöglichen Kompression des Tools Google Closure zu profitieren. Insbesondere der letzte Punkt garantiert eine sehr kleine Dateigröße der ol3-JavaScript-Datei. Die finale ol3-Bibliothek ist aber natürlich auch ohne Google Closure zu benutzen. Bereits in der Entwicklung wurde wert darauaf gelegt, dass ol3 unproblematisch auch mit anderen JavaScript-Frameworks oder Bibliotheken einzusetzen ist.

Die sicherlich bemerkenswerteste Neuerung von ol3 ist die zusätzliche Unterstützung von WebGL als Rendering Engine. WebGL erlaubt es, in modernen Browsern hardwarebeschleunigte 3D-Grafiken darzustellen und dies ohne zusätzliches Plugin.
Unterstützung für WebGL ist in den aktuellen Versionen der Browser Google Chrome, Chromium, Opera, Firefox & Internet Explorer 11 bereits integriert. Mit WebGL-Unterstützung in ol3 ist es nunmehr möglich, mit einer Bibliothek sowohl hochperformante 2D Karten im web darzustellen, als auch virtuelle Globen zu erstellen, die im Browser bedient werden. Hier wird insbesondere mit den Entwicklern der Cesium Bibliothek eng zusammengearbeitet. Mit der aktuellen Version von ol3 (beta.1), Ist die Erstellung von virtuellen Globen derzeit nicht möglich, die grundsätzliche Funktionalität und Architektur ist jedoch bereits implementiert. 

OpenLayers 2 wurde lange vor dem Boom des mobilen Internets, auf welches via Smartphones und Tablets zugegriffen wird, entwickelt. Die Unterstützung mobiler Endgeräte wurde zwar nachgerüstet und ist funktional, doch ol3 unterstützt mobile Endgeräte von Anfang an. Hierbei wurden stets die besonderen Limitierungen (langsame/instabile Netzverbindung, kleiner Arbeitsspeicher, vergleichsweise kleiner Bildschirm etc.) und zusätzlichen Möglichkeiten (MultiTouch-Bedienung, Rotation des Gerätes, HTML5-APIs etwa zur Geolokalisierung) mobiler Geräte beachtet.

Zwei größere Kritikpunkte an OpenLayers 2 waren die z.T. fragmentierte und unvollständige Dokumentation und die Schwierigkeit, eine spezielle Version von OpenLayers zu erzeugen, die nur enthält, was man wirklich benötigt (custom build). Hier möchte ol3 besser sein: Bereits heute ist es möglich, die Bibliothek so zu nutzen, dass ein minimaler build einfach zu erzeugen ist. Geplant sind hier weitere Tools und/oder Applikationen, die diese Anpassungen noch einfacher für Endanwender und Programmierer machen. Bei der Dokumentation setzt ol3 auf das Programm jsdoc3 (http://usejsdoc.org/), welches bereits hervorragende, komplette und konsistente Dokumentation produziert. Hier sind sicherlich noch weitere Anpassungen seitens der ol3-Entwickler vorzunehmen, aber wir sind sicher, die Qualität der Dokumentation hoch zu halten.

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
