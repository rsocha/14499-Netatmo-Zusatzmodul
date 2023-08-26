# 14499 Netatmo Zusatzmodul

## Beschreibung 

Der Baustein ist ein Zusatz zum 14497 Netatmo_Basis Baustein und dient zur Kommunikation mit einem Netatmo Zusatzmodul.


## Eingänge

| Nr. | Name                | Initialisierung | Beschreibung                                                                                                                                                                               |
| --- |---------------------| --- |--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1 | Output from (11497) | | Output File vom Baustein 14497 Netatmo Basis                                                                                                                                                |
| 2   | Modul Name          |                   | Name vom Zusatzmodul                                         |
| 3   | Zeitformat 0/1      | 0                 | Soll eine Umwandlung der Zeitausgabe erfolgen. 0=Nein / 1=Ja |
| 4   | Format Datum-Zeit   | %d-%m-%Y %H:%M:%S | Format der Zeitausgabe                                       |


## Ausgänge

| Nr. | Name           | Initialisierung | Beschreibung             |
|-----|----------------|-----------------|--------------------------|
| 1ff | ...            | ...             | Selbsterklärend          |
|     |  |                 |                          |



## Beispielwerte

| Eingang | Ausgang |
| --- | --- |
| - | - |


## Other

- Neuberechnug beim Start: Nein
- Baustein ist remanent: nein
- Interne Bezeichnung: 11499
- Kategorie: Datenaustausch

### Change Log

- v0.3
   - Zeiformat hinzugefuegt
 - v0.2
   - div. Anpassungen
 - v0.1
     - Initial



### Code

Der Code des Bausteins befindet sich in der hslz Datei.

### Devleopment Environment

- [Python 2.7.18](https://www.python.org/download/releases/2.7/)
 


## Licence

Copyright 2023

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
