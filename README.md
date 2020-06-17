---
title: Studienleistung 3
author: Martin Kocur
documentclass: scrartcl
classoption:
  - a4paper
header-includes: |
    \usepackage{german}
	\usepackage{xcolor} 
    \usepackage[a4paper,left=2.5cm, right=2.5cm,top=2.5cm, bottom=3cm]{geometry}
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \fancyhf{}
    \rhead{Webtechnologien}
    \lhead{SL3}
    \fancypagestyle{plain}{
      \fancyhf{}
      \rhead{Webtechnologien}
      \lhead{SL3}}


---



## Aufgabe: Visualisierung von Daten

Implementieren Sie in dieser Aufgabe eine kleine Web-Anwendung, die mit Hilfe eines AJAX-Requests eine JSON-formatierte Datei herunterlädt und anschließend aufbereitet in einem Diagramm darstellt.



Es ist Ihre Aufgabe die Anzahl der COVID-19 Fälle der letzten zwei Wochen (01.06.20 bis 14.06.20) in Deutschland darzustellen, um einen Überblick über die Entwicklung der Erkrankung zu erhalten. Sie können die in der Vorlesung besprochene _Fetch API_ und die Bibliothek _Chart.js_ verwenden, um die Daten anzufragen und anschließend zu visualisieren. Unter der URL https://regensburger-forscher.de/data/covid-stats.json können Sie die benötigten Daten herunterladen.



Die folgenden Links sollen Sie dabei unterstützen die Funktionalität zu implementieren:

- [\textcolor{blue}{Hier}](https://www.chartjs.org/) erfahren Sie mehr über Chart.js
- [\textcolor{blue}{Hier}](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API) lernen Sie die Grundlagen der Fetch API


------

*Abgabekriterien:*

Laden Sie Ihre Lösung bis spätestens 5.7.2020 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch.  Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie geeignete Formate:

- Aufgabe 1: Das gesamte Projekt (HTML, JS, CSS)

Der Name der Zip-Datei ergibt sich aus dem Präfix „SL_WT_SS20“, der Nr. der Studienleistung, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **SL_WT_SS20_3_Max_Mustermann.zip**

