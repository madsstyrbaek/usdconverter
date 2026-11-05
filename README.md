# USD Quick Convert

Lille valutaomregner til arbejdsbrug: ét USD-felt, DKK/EUR/GBP vises live nedenunder.
Kurser hentes én gang om dagen fra [Frankfurter](https://www.frankfurter.app) (ECB-referencekurser).

## Brug som desktop-widget (Windows, uden installation)

1. Åbn siden i Edge → menu (…) → Apps → *Install this site as an app*.
2. Pin app'en til proceslinjen, fx som nr. 3, så `Win+3` fokuserer den.
3. PowerToys → Always On Top (`Win+Ctrl+T`) holder vinduet øverst.
4. Vinduet lægger selv markøren i USD-feltet, hver gang det får fokus. Skriv beløbet, aflæs kurserne. `Esc` rydder.

## Tilføj valutaer

Ret `CURRENCIES` øverst i scriptet i `index.html`, fx `['DKK', 'EUR', 'GBP', 'SEK']`.
