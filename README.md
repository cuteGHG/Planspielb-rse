# Planspielbörse

Ein browserbasiertes Depot-Dashboard für das Planspiel Börse.

## Funktionen
- Import von Handelsbuch-Exporten als CSV, XLSX oder XLS
- Lokale Verarbeitung im Browser (Datei wird nicht hochgeladen)
- Erkennung gängiger Spalten für Wertpapier, Ticker/ISIN/WKN, Stückzahl und Kaufkurs
- Berechnung von Depotwert, investiertem Kapital sowie Gewinn/Verlust
- Übersicht aller Positionen und einfache Depotgrafik

## Start
Die Datei `index.html` kann direkt geöffnet oder über GitHub Pages veröffentlicht werden.

## Kursdaten
Die aktuelle Version verwendet die im Handelsbuch enthaltenen Kurswerte bzw. den Kaufkurs als Fallback. Es ist **noch kein Live-Kursanbieter verbunden**. Für echte Echtzeit- oder verzögerte Kurse muss ein Datenanbieter (z. B. mit API-Key) über einen kleinen Backend-Proxy angebunden werden. API-Schlüssel dürfen nicht in den öffentlich sichtbaren Browser-Code geschrieben werden.

## Importformat
Die Erkennung unterstützt u. a. Spalten wie `Name`, `Aktie`, `Wertpapier`, `Ticker`, `Symbol`, `ISIN`, `WKN`, `Stück`, `Anzahl`, `Kaufkurs` und `Aktueller Kurs`. Bei abweichenden Exportspalten muss der Import angepasst werden.

## Hinweis
Das Projekt dient dem Lernen im Planspiel Börse und ist keine Anlageberatung. Angezeigte Werte können von der offiziellen Planspiel-Bewertung abweichen.
