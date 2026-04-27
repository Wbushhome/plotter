# TRT Plotter v5

Wersja v5 poprawia zawyżanie pików testosteronu widoczne w v4.

## Główne zmiany

- Cmax z danych farmakokinetycznych jest traktowany jako testosteron całkowity, a nie jako sam wkład egzogenny.
- Przy kalibracji Omnadren/Sustanon model odejmuje naturalny testosteron startowy od docelowego Cmax.
- Supresja osi HPTA jest teraz stanem dynamicznym, a nie prostą funkcją aktualnego poziomu T.
- Dodano parametr: czas 50% odbicia osi.
- Wykres jest gładszy, bo uwalnianie estrów liczone jest modelem podobnym do krzywej Batemana.
- Poprawiono lewy margines wykresu, żeby opis osi Y nie był ucinany.
- Zachowano moduł anastrozolu, E2, masy, wzrostu, tkanki tłuszczowej, Nebido i Prolongatum.

## Ważne

To nadal jest model poglądowy. Nie służy do ustalania leczenia ani dawkowania.
