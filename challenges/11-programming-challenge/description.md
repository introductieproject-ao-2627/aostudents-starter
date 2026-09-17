# Car

> ⭐⭐⭐ Moeilijk · ±meerdere uren · **Wat heb je nodig:** een browser en VS Code; je schrijft JavaScript-code in `student.js`

Deze challenge werkt anders dan alle andere: je schrijft echte code, en er is geen `solution.txt` en geen `verify.py`.
Je oplossing wordt dus **niet** gecontroleerd via de testen in VS Code (het fles-icoontje), maar in je browser.

## Hoe begin je?

1. Open `tests.html` in je browser (dubbelklik op het bestand, of sleep het naar een browservenster).
   Links staan 32 oefeningen, van makkelijk (❶) naar moeilijk (❺). In elke oefening moet je een fiets of auto door een stadje naar het groene vakje laten rijden, met instructies zoals `forward(bike)`, `turnLeft(bike)`, `turnRight(bike)` en `sensor(bike)`.
   Klik op een oefening: de uitleg en de opgave staan op de pagina zelf. Bij de meeste oefeningen kan je onderaan ook de oplossing openklappen (**solution**) als je vastzit.
2. Open `student.js` in VS Code. Per oefening schrijf je daarin een functie met *exact dezelfde naam* als de oefening, bijvoorbeeld:

   ```javascript
   function twiceForward(bike) {
       forward(bike);
       forward(bike);
   }
   ```

3. Sla `student.js` op en herlaad de pagina (F5). De pagina voert dan meteen al je functies uit en kleurt per oefening het resultaat groen of rood; onderaan links zie je je totaal (bv. `2 / 32`).
   De play-knop onder de kaart dient enkel om de rit van de geselecteerde oefening te *bekijken*; hij verandert niets aan de score.

Zie je enkel een rode foutmelding op de pagina? Dan bevat `student.js` een fout. De pagina legt uit hoe je de browserconsole opent om de fout te vinden.

## Tips

* Werk de oefeningen in volgorde af; elke oefening bouwt verder op de vorige.
* Deze challenge sluit nauw aan bij wat je in Programming 1 leert. Vind je het te moeilijk? Kom er later in het semester op terug.
