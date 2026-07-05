# mod-middle-earth

Struktura danych i zasobow moda "Srodziemie" (total conversion LOTR dla KaM Remake),
utworzona w zad. 0.8 planu (`plan_moda_srodziemie.md`), po zaliczeniu Bramki 0.

Katalogi:

- `assets-src/` - zrodlowe pliki grafiki/animacji (PNG, projekty), poza pipeline'em silnika.
- `assets-build/` - skonwertowane paczki spritow gotowe do zaladowania przez silnik (RX/RXX itp.).
- `data/` - definicje frakcji, jednostek, budynkow, balans (pliki danych, nie kod silnika).
- `maps/` - mapy skirmish dla moda.
- `tools/` - skrypty pipeline'u: konwertery, walidatory formatow.
- `docs/` - dokumentacja formatow, decyzji (ADR), balansu, raporty bramek dot. samego moda.

Ta struktura zyje wewnatrz forka silnika (`kam_remake`, branch `mod/middle-earth-r6720`),
obok kodu silnika, zgodnie z planem (zad. 0.8). Zawartosc poszczegolnych katalogow
zacznie powstawac od Fazy 1 (research formatow i architektura moda).
