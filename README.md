# Quick Convert

Lille valutaomregner til arbejdsbrug: ét felt pr. valuta (USD, DKK, EUR og GBP som udgangspunkt) – skriv i ét, og de andre regnes om live.
Kurser hentes én gang om dagen fra [Frankfurter](https://www.frankfurter.app) (ECB-referencekurser).

## Brug som desktop-widget (Windows, uden installation)

1. Åbn siden i Edge og tryk *Installér som app* nederst på siden (eller menu (…) → Apps → *Install this site as an app*). Sæt flueben ved *Fastgør til proceslinje*, når Edge spørger.
2. Pin app'en til proceslinjen, fx som nr. 3, så `Win+3` fokuserer den.
3. PowerToys → Always On Top (`Win+Ctrl+T`) holder vinduet øverst.
4. Vinduet lægger selv markøren i det øverste felt, hver gang det får fokus. Skriv beløbet, aflæs kurserne. `Esc` rydder.

## Taster

- `Tab` flytter markøren til næste valutafelt (`Shift+Tab` går baglæns). Feltet med markøren er det, der omregnes fra.
- `Ctrl+Tab` skifter mellem omregner og lommeregner.
- Når vinduet får fokus igen, starter det altid i det øverste felt med det gamle beløb markeret, så næste tast overskriver det.

## Valutaer

Tryk på ⚙ i bunden for at tilføje, fjerne og flytte valutaer. Den øverste er standard og får markøren, når vinduet åbnes eller får fokus igen. Opsætningen gemmes i browserens localStorage på den enkelte pc. Kurser for alle ECB-valutaer hentes samlet én gang i døgnet.

Ikonet (`icon.svg`, `icon-*.png`) og `manifest.json` bruges af den installerede Edge-app.
