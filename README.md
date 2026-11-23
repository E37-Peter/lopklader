# Löpkläder

Klädförslag för löpning utifrån vädret där du är. Appen lär sig hur du fungerar genom att du svarar på hur passet kändes.

**Prova den:** https://e37-peter.github.io/lopklader/

## Så funkar den

- Svaret står som en affisch: plaggen i stor kursiv stil, och under den ligger kläderna utlagda ovanifrån. Alla plagg ritas i samma skala, så att jacka, tights, mössa och strumpor har rätt storlek mot varandra. Lager under jackan syns som konturer, och mössa, buff och handskar är röda. Det som redan står i affischen får inget namn under plagget, bara en undertext när den tillför något.
- Vädret syns över kläderna: skuggor i sol (längd och riktning efter solens höjd), droppar i regn, snö som lägger sig och plagg som blåser snett i blåst.
- Plaggen läggs ut ett i taget vid start, och när förslaget ändras rör sig bara de plagg som är nya.
- Under kläderna står en notis i den röst du väljer (Saklig, Peppig eller Torr).
- En tidslinje visar temperatur, regn, mörker och den bästa tiden de närmaste tolv timmarna. Dra för att välja när du springer.
- Efter passet frågar startsidan själv hur det kändes.

- Hämtar prognos timme för timme (och kvartsvis för den närmaste tiden) från [Open-Meteo](https://open-meteo.com), gratis och utan nyckel.
- Räknar fram en upplevd temperatur med vindavkylning, sol, nederbörd och typ av pass, och föreslår kläder för huvud, överkropp, ben, händer och fötter.
- Varnar när vädret slår om de närmaste två timmarna: regn, kyla, vind, mörker och risk för halka.
- Ortnamnet för din position slås upp med [BigDataCloud](https://www.bigdatacloud.com/free-api/free-reverse-geocode-to-city-api), en gratis tjänst som anropas direkt från webbläsaren.
- Föreslår en bättre tid inom de närmaste sex timmarna när vädret blir klart bättre, till exempel uppehåll eller svagare vind.
- Efter passet kan du säga var du frös eller blev för varm. Svaren sparas med vädret, så de väger mest när vädret liknar det du svarade i.
- Inställningar under "Om dig" (fryser lätt, kalla händer, shorts eller tights) och svaren efter passen justerar förslagen. Allt sparas bara i webbläsaren.

## Filer

- `index.html` - hela appen (HTML, CSS och JavaScript i en fil)
- `manifest.webmanifest`, `sw.js`, ikoner - gör att den kan läggas på hemskärmen som en app

Lägg till på hemskärmen: öppna sidan i mobilen, välj Dela och sedan Lägg till på hemskärmen.

## Ikoner

Ikonerna kommer från [Lucide](https://lucide.dev) (ISC). Animationerna bygger på [lucide-animated](https://lucide-animated.com) (MIT) och är omsatta till CSS. Se [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md).
