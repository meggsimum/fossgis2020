# Neues vom GeoStyler

Das kartographische Stylen von Geodaten im Web ist seit Jahren ein wiederkehrendes
Thema in der Geoinformatik-Welt. Es existieren verschiedenste Standards –
Offizielle Standards, z. B. OGC Styled Layer Descriptor (SLD) mit OGC Filter Encoding (FE)
sowie Industriestandards, beispielsweise Mapbox Styles und projektbezogene
Styling-Vorschriften, z. B. in QGIS oder OpenLayers.

Es fehlt jedoch eine interaktive webbasierte Software, um Anwender in die Lage zu
versetzen die kartographische Ausgestaltung ihrer Geodaten auf einfache Weise zu erledigen.
Es gibt zwar vereinzelte Lösungen für einzelne der oben genannten Standards.
Eine gesamtheitliche Web-Oberfläche, um u. a. auch Styling-Vorschriften in diverse
Formate zu überführen, fehlte bislang.

Der „GeoStyler“ ist seit 2018 in der Entwicklung und steht mittlerweile in
Version 4 zur Verfügung. Er bietet ein webbasiertes Open Source Werkzeug zur
interaktiven Erstellung von kartographischen Style-Vorschriften für Geodaten.

Aktuell können folgende Formate genutzt werden:

Style-Vorschriften

  - OGC SLD
  - OpenLayers Styles
  - QGIS Styles
  - Mapbox Styles

Geodaten-Formate

  - GeoJSON
  - OGC WFS
  - Shapefile

Zudem wurde der GeoStyler als GeoServer Community Extension veröffentlicht,
sodass Stile direkt im GeoServer mittels graphischer Oberfläche editiert werden können.

Der Vortrag stellt die Weiterentwicklungen seit der FOSSGIS'19 vor, zeigt die
Funktionaltäten von GeoStyler und gibt einen Überblick über zukünftige Entwicklungen.

Quellcode auf github: https://github.com/geostyler/geostyler

Online-Dokumentation: https://geostyler.github.io/geostyler/latest/index.html

Demo: https://www.geostyler.org
