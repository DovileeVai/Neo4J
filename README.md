# Neo4J
Nereliacinių duomenų bazių užduotis – „Flight Search Service“, realizuota naudojant Python Flask ir Neo4J. <br >
Platformoje saugoma informacija apie skrydžius tarp dviejų miestų. Naudojantis platforma klientai gali rasti geriausią pasiūlymą skrydžių pasiūlymą į bet kurią veitą.

### Funkcionalumas:
- Miestų registracija: miesto pvadinimas, šalies pavadinimas.
- Oro uostų registracija: kodas, pavadinimas, terminalų skaičius, adresas.
- Skrydžių registracija: skrydžio numeris, išvykimo miestas, atvykimo miestas, skrydžio kaina, trukmė, operatorius.
- Skrydžių tarp dveijų miestų paieška (nerodomi skrydžiai su duagiau nei 3 persėdimais).
