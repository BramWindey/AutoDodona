# AutoDodona


-Gebruiksaanwijzingen-

Voorlopig moet dit programma worden uitgevoerd in een IDE, bijvoorbeel PyCharm. Zorg dat de volgende bestanden zich in dezelfde map bevinden:
-main.py
-webscraper.py
-code_assemble.py
-API-token.txt
-program.txt

Zorg bij een eerste gebruik dat u een API-token genereert in Dodona, en dit in dit tekst bestand kleeft. Lees hier hoe waar u dit token kan genereren: https://docs.dodona.be/nl/guides/creating-an-api-token/
Na deze eerste keer zal dit niet meer nodig zijn.

Bij een eerste keer zal u ook de volgende modules moeten installeren:
-requests
-bs4
-itertools
-pyperclip
In PyCharm kan dit door in webscraper.py en code_assembly over de overeenkomstige namen van de modules te "zweven" en op de link "install module" te klikken. 

Na dit beginnersongemak bent u klaar om het programma te gebruiken. Voer main.py uit, en volg de instructies van het programma. 


-Programma-instructies-

Bij het plakken van de link moet u opletten, u moet de correcte link kleven. 
Deze link krijgt u als volgt:
-navigeer naar de oefening op Dodona
-dien deze leeg in
-als niet alle testcases fout zijn, dien dan 'print("foo")' in als programma, sla anders deze stap over
-boven het rode kruis met "Fout" klikt u nu op '#1', dit nummer kan verschillen
-u zit nu op de juiste pagina, kopieer de link bovenaan uw browser, en plak deze in het programma, en druk op enter

Hierna wordt u het aantal outputs gevraagd. Kijk hiervoor terug naar de Dodona-resultatenpagina die u hierboven verkreeg, en tel hoeveel verschillende outputs (per input) er onder de categorie "Verwachte uitvoer" staan. Gewoonlijk is dit een getal tussen de 1 en 5. Geef in in het programma en druk op enter.

Hierna bent u klaar. Wanneer het programma meldt dat de code op het klipbord staat, betekent dit dat het klaar is met werken (normaalgezien duurt dit maximum een paar seconden), en kan u terug naar de oefening op Dodona gaan. Op de plaats waar de programmacode terechtkomt kan u onmiddelijk de gegenereerde code kleven. Mocht dit niet het geval zijn, dan staat de gegenereerde code in "program.txt". Open dit bestand en kopieer de inhoud.


-Beperkingen-

Voorlopig kan het programma nog geen code genereren die enkel uit een functie bestaat. Dit wordt later nog toegevoegd.

Het kan gebeuren dat bij het indienen van de code Dodona de melding geeft dat de code te groot is. Hier kan ik jammergenoeg niets aan doen, het is dan aan u om de oefening al redenerend uit te werken. 

U moet het aantal verwachtte outputs opgeven, niet ideaal, maar ik zag nog geen simpele oplossing voor dit probleem. Hopelijk wordt dit opgelost in verdere updates.

Het programma moet uitgevoerd worden binnen een IDE, verre van ideaal. Graag zou ik in een toekomstige update dit veranderen naar een losstaand executable bestand dat gebruik maakt van een GUI (tkinter module). 


-License-	MIT-license

Copyright 2022 Windey Bram

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
