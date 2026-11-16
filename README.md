# Löpkläder

Klädförslag för löpning utifrån vädret där du är. Appen lär sig hur du fungerar genom att du svarar på hur passet kändes.

**Prova den:** https://e37-peter.github.io/lopklader/

## Så funkar den

- Hämtar prognos timme för timme (och kvartsvis för den närmaste tiden) från [Open-Meteo](https://open-meteo.com), gratis och utan nyckel.
- Räknar fram en upplevd temperatur med vindavkylning, sol, nederbörd och typ av pass, och föreslår kläder för huvud, överkropp, ben, händer och fötter.
- Varnar när vädret slår om de närmaste två timmarna: regn, kyla, vind, mörker och risk för halka.
- Inställningar under "Om dig" (fryser lätt, kalla händer, shorts eller tights) och svaren efter passen justerar förslagen. Allt sparas bara i webbläsaren.

## Filer

- `index.html` - hela appen (HTML, CSS och JavaScript i en fil)
- `manifest.webmanifest`, `sw.js`, ikoner - gör att den kan läggas på hemskärmen som en app

Lägg till på hemskärmen: öppna sidan i mobilen, välj Dela och sedan Lägg till på hemskärmen.

## Ikoner

Ikonerna kommer från [Lucide](https://lucide.dev) (ISC). Animationerna bygger på [lucide-animated](https://lucide-animated.com) (MIT) och är omsatta till CSS. Se [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md).
