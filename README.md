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

*Zeitreisen*
Dann wollte ich mit "revert" arbeiten auf dem Branch "alternative colors". Da stand mir erst ein conflict wegen unmerged files
im Weg, aber danach hat es funktioniert und ich habe einen vorherigen Stand des Branches hergestellt. 
Ich habe auch "reset" ausprobiert und dabei ein bisschen ausprobieren müssen, wann push und pull aufgerufen werden muss. 
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/372b9201-aed2-4d3a-8783-31e05bb45d2c)
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/5a8f9d25-8b0c-414a-b07d-2dd884c1612a)

Ich habe die Befehle *diff, remove* angewendet: 
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/b630c8e4-8aba-4403-8d12-9268a64452c2)


ERGÄNZUNG vom 26.06.---------------------------------------------------------------------------

Ich habe noch einen weiteren Branch erstellt namens "new feature". Darin habe ich Code in der css-Datei verändert. 
Den Branch habe ich diesmal nicht mit der Kommandozeile, sondern in Githubs Web Interface über einen Pull Request gemerged. 
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/466d464f-d16e-48a4-9451-69b70c503d07)
Mit merge habe ich aber auch schon vorher herumprobiert: 
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/609f3348-8e1e-4443-a5db-dbc4bd9dbbe5)

Um mich noch weiter mit den "Zeitreise"-Möglichkeiten zu beschäftigen, wollte ich ausprobieren, wie man einen neuen Branch basierend auf einem
commit aus der Vergangenheit erstellt, den man bearbeiten kann, während man die vorhandenen aktuellen Branches aber behält. 
Dafür habe ich zuerst einen früheren commit mit Angabe des Hash-Werts ausgecheckt und dann einen neuen Branch erstellt. 
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/4c10a811-cb89-4207-96d1-71d0d0542cde)

In diesem alten Stand des Repositories war nur die html-Datei und noch nicht die CSS-Datei vorhanden: 
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/14d944e9-80bb-4933-8da8-5bf6823869f6)

Als nächstes wollte ich diesen Branch wieder löschen, ohne ihn zu mergen, also einfach verwerfen. 
Dazu habe ich ihn zuerst lokal gelöscht: 
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/e7e57329-c094-4cd4-b913-1d4feda6595f)

Und dann auch remote: 
![grafik](https://github.com/hannah-fitz/bht-softwaretechnik/assets/170937973/c5071eda-401c-4b8e-bd81-978371f13c3a)

