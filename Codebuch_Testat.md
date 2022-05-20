# Codebuch für das Testat - von Lara Zosig (lz035)

Meine Daten stammen aus: https://www.transfermarkt.de/vfb-stuttgart/startseite/verein/79

## Edgelist

from = von welchem Verein kommt der Spieler 

to = ID des Spielers (Rückennummer)

weight = Transfersumme in 100.000 Euro Schritten, gerundet falls abweichend.

season = Transferfenster. Nur erste Jahreszahl des Fensters als JJJJ verwendet.

In der gleichen Edgelist wird außerdem die Nationalität der einzelnen Spieler angegeben (Bei doppelten Staatsangehörigkeiten werden pro Staatsangehörigkeit eine Kante angelegt).

## Nodelist

id = Rückennumer oder Vereinsname

name = Spieler oder Vereinsname

country = Land

type 1 = Spieler, 2 = Verein
