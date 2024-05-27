# bht-softwaretechnik
Aufgabe Versionskontrolle 

Einige Zwischenschritte beim Sammeln von ersten Erfahrungen mit Git und Github: 

1. Versuch "push" ist schiefgegangen: Ich musste mich erst authentifizieren.
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/607a2769-0031-4fcd-be50-c132a3db5e13)

2. Versuch "push ist schiefgegangen: Ich musste ein zuvor auf Github erstelltes Repository erst clonen.
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/dac9b628-24cc-4208-b357-df583d0ecde5)

Gelernt: Der Befehl "mv" bezieht sich anscheinend nicht auf Dateien außerhalb von Git. 
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/048bc771-bf67-438b-99a3-73e3a63ce4eb)

Nächste Challenge: 
Ich habe in diesem README.md die Beschreibungen und Screenshots hinzugefügt. Das ist aber im Branch "alternative-color", 
in dem ich in der CSS-Datei eine Farbe geändert habe, die ich wieder rückgängig machen will. Also habe ich mich gefragt: 
Wie bekomme ich nur die Änderungen in der README in den main-Branch, nicht andere commits in der CSS? 
-> da musste ich erstmal aufgegeben, das habe ich leider noch nicht hinbekommen... 

# Zeitreisen
Dann wollte ich mit "revert" arbeiten auf dem Branch "alternative colors". Da stand mir erst ein conflict wegen unmerged files
im Weg, aber danach hat es funktioniert und ich habe einen vorherigen Stand des Branches hergestellt. 
Ich habe auch "reset" ausprobiert und dabei ein bisschen ausprobieren müssen, wann push und pull aufgerufen werden muss. 
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/372b9201-aed2-4d3a-8783-31e05bb45d2c)
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/5a8f9d25-8b0c-414a-b07d-2dd884c1612a)

