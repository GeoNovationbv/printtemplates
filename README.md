# printtemplates
Print templates voor KaartViewer 

Dit kan direct in de geoserver data dir worden gebruikt.

Aanpassingen in config.yaml
De templates beginnen met de domeinnaam en dan het formaat en afdrukstand (bijvoorbeeld: KAARTVIEWER_A4L). Om het template te laten werken met de eigen kaartviewer installatie moet KAARTVIEWER worden vervangen door de eigen subdomein naam. Dit moet gebeuren voor alle formaten (A4 t/m A4 en afdrukstanden (portrait en landscape)

Aanpassing in KaartViewer
In KaartViewer Admin moet onder configuratie bookmark de layouts voor het printen worden uitgebreid zodat ook A2, A1 en A0 beschikbaar worden.
A4L:A4 Landscape;A4P:A4 Portrait;A3L:A3 Landscape;A3P:A3 Portrait;A2L:A2 Landscape;A2P:A2 Portrait;A1L:A1 Landscape;A1P:A1 Portrait;A0L:A0 Landscape;A0P:A0 Portrait

In map www/printing zit bestand logo.svg dit moet worden aangepast naar een bestand met een eigen logo. Als de bestandsnaam anders wordt moet dit in config yaml bestand worden bijgewerkt. 
