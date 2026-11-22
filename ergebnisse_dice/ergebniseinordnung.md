3 Versuchsreihen, 29 Testfälle, 5 Suchseeds und 3 Bedingungen ergeben 1305 protokollierte Suchen mit festem Budget von 20000 Kandidatenzeilen je Suche.

Der Random Forest erreicht im zurückgehaltenen Testset eine Accuracy von 77,5 % und eine Balanced Accuracy von 65,8 %.

Der Recall für bad / 1 beträgt 36,7 %. Dieser Wert zeigt separat, welcher Anteil der bekannten ungünstigen Fälle erkannt wird. Eine gültige gegenfaktische Erklärung verbessert diese Klassifikationsleistung nicht automatisch.

**R0: Ausgangsdesign:** Erfolgsrate A: frei 100,0 % (mit 1 Änderung: 39,3 %); B: Merkmale fest 100,0 % (mit 1 Änderung: 34,5 %); C: zusätzlich Bereiche 100,0 % (mit 1 Änderung: 17,9 %). Gemeinsam erfolgreiche Fall-Seed-Paare: 145.

**R1: nur Kreditkonditionen veränderbar:** Erfolgsrate A: frei 100,0 % (mit 1 Änderung: 39,3 %); B: Merkmale fest 100,0 % (mit 1 Änderung: 33,1 %); C: zusätzlich Bereiche 74,5 % (mit 1 Änderung: 4,8 %). Gemeinsam erfolgreiche Fall-Seed-Paare: 108.

**R2: Sicherheitsabstand p(good) ≥ 0,8:** Erfolgsrate A: frei 100,0 % (mit 1 Änderung: 1,4 %); B: Merkmale fest 76,6 % (mit 1 Änderung: 1,4 %); C: zusätzlich Bereiche 44,1 % (mit 1 Änderung: 0,0 %). Gemeinsam erfolgreiche Fall-Seed-Paare: 62.