---
title: Studienleistung 3
author: David Halbhuber
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



## Aufgabe: Erste Schritte mit SQlite in JavaScript 

In dieser Aufgabe sollen Sie die ersten Schritte im Umgang mit SQlite und JavaScript umsetzen und demonstrieren. 
Für die Bearbeitung der Aufgabe stellen wir Ihnen ein Projekt zur Verfügung das bereits alle nötigen Elemente enthält. 
Das Projekt beinhaltet bereits: 

	- Eine eingebundene SQlite Datenbank 
	
	- Eine Node.Js Umgebung die eine Express App bereitstellt
	
	- Eine Möglichkeit Queries an die eingebundene Datenbank zu senden 
	

Beginnen Sie mit der Entwicklung in der '../resources/js/index.js' Datei. In der 'index.js' initiiert die asychrone Funktion 'initDatabaseConnection' die Verbindung zur Datenbank. Das Datenbankobjekt wird dann in der Variable 'db' gesichert. Durch ein Aufruf der 'runQuery' Funktion können Queries an die Datenbank gesendet werden. Queries werden als String in der Variable 'query' deklariert und dann an 'runQuery' übergeben. Das Ergebnis der Query, falls es eines gibt, wird in der 'response' Variable gesichert. 

Beginnen Sie mit den folgenden Aufgaben nach dem Sie sich mit der Arbeitsumgebung vertraut gemacht haben. Gehen Sie dabei schrittweise vor und erstellen für jede Teilaufgabe ein neues Paar aus Query und Response. Orientierten Sie sich bei der Erstellung an dem mitgelieferten Beispiel.  

	1. Erstellen Sie eine neue Tabelle mit dem Namen Personen in der der Datenbank die die folgenden Informationen abbilden soll: PersonenID, Nachname, Vorname, 		Adresse, Wohnort, Alter .
		1.1 Achten Sie bei der Erstellung auf die Verwendung von korrekten Datentypen (char, varchar, binary, tinyblob,...). 
		1.2 Begründen Sie einem kurzen Kommentar die Wahl Ihrer Datentypen. 
		
	2. Erstellen Sie nun einen neuen Eintrag in der Personen Tabelle mit einem fiktiven Person.
	
	3. Geben Sie den gesamten Inhalt der Personen Tabelle via console.log aus. 
	
	4. Erstellen Sie 






Die folgenden Links sollen Sie dabei unterstützen die Funktionalität zu implementieren:

- [\textcolor{blue}{Hier}]([https://www.chartjs.org/](https://www.w3schools.com/sql/sql_create_db.asp)) erfahren Sie mehr über SQL
- [\textcolor{blue}{Hier}]([https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API](https://www.sqlite.org/docs.html)) erfahren Sie mehr über SQlite


------

*Abgabekriterien:*

Laden Sie Ihre Lösung bis spätestens 26.7.2022 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch.  Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie geeignete Formate:

- Aufgabe: Das gesamte Projekt (HTML, JS, CSS)

Der Name der Zip-Datei ergibt sich aus dem Präfix „SL_WT_SS22“, der Nr. der Studienleistung, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **SL_WT_SS22_3_Max_Mustermann.zip**

