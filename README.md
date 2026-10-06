# MatBeckis
Hitta närmsta lunchen på Beckis.

En karta över restauranger, snabbmatsställen och kaféer inom **1 mil** från Kopparbacken 22, Spånga.

## Kom igång
Öppna `index.html` i en webbläsare, eller slå på GitHub Pages för repot. Ingen byggprocess behövs.

- **Restaurangerna** hämtas gratis och direkt från OpenStreetMap (Overpass API).
- **Betyg** kommer från Google Places. Lägg in en egen API-nyckel under ⚙︎ (Places API (New) måste vara aktiverat). Betygen hämtas när du öppnar ett ställe, eller med "Hämta betyg (topp 20)", och sparas i webbläsaren i 30 dagar så att det blir få anrop.

## Funktioner
- Markörer i olika färger efter betyg och grupperade (klustrade) för att 1 mil ger tusentals ställen. Ringar visar 1, 3, 5 och 10 km.
- Radie går att ställa in mellan 0,5 och 10 km. Listan kan sorteras på avstånd, betyg eller betyg × popularitet.
- Filter: typ, kök, öppet nu, lunchläge (öppet vardag 11:30–13:30), vegetariskt, favoriter och lägsta betyg.
- 🎲 **Slumpa lunch**: väljer ett öppet ställe med bra betyg. Närmare ställen väger tyngre.
- ❤️ Favoriter sparas i webbläsaren.
- Uppskattad gång- eller cykeltid, länk till vägbeskrivning och hemsida eller meny.
- Dra 🏠 för att flytta startpunkten, eller välj "Använd min position" under ⚙︎.
- Fungerar i mobilen och har mörkt läge.
