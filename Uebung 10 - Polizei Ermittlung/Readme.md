# Aufgabe 10: Polizei Ermittlung
## Einleitung
Die Polizei hat bei einem Mordfall ein Stück Papier gefunden. Es ist ein wichtiges Beweisstück. Es wurde an einem ganz bestimmten Datum auf einem Farbdrucker ausgedruckt. Durch die Analyse des [ Blatt Papier](printout.png) kann man herausfinden, wann das Blatt und auf welchem Drucker gedruckt wurde.  

![img](rollingprinter.jpg)

## Aufgabe
Wann wurde das Blatt ausgedruckt? [Download Beweismittel](printout.png)

## Lösung
Du kannst die Lösung selbst kontrollieren, indem Du einen md5 hash vom YYYYMMDDHHmm berechnest, dann ergibt dies der folgende Hash `f3e51c6307de25210b6d886181d2283b`

### MD5 Berechnung
Wie berechnest Du den md5 Hash unter Linux?
```
echo "YYYYMMDDHHmm" |md5sum
```

ein Beispiel mit echten Zahlen 
`echo "201812311705" | md5sum`

* Jahr 2018
* Dezember
* 31
* 17:05 Uhr

Wenn Du das echte Datum, Monat, Tag, Stunde, Zeit herausfindest, dann ergibt der Hash den Wert `f3e51c6307de25210b6d886181d2283b`

## Hinweis zur Lösung
Suche bei Google nach **Xerox Machine Identification Code (MIC)** für Color Laser Printers. 

* https://en.wikipedia.org/wiki/Machine_Identification_Code

