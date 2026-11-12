# useEffect-gissningen

En övning i att läsa React-kod. Sidan har 10 komponenter som ser nästan likadana ut: samma lista, samma API och samma knapp. Men knappen gör olika saker i varje komponent. Din uppgift är att lista ut vilken kodsnutt (A–J) som hör till vilken komponent.

## Så gör du

1. Testa varje komponent. Klicka flera gånger, vänta en stund och titta på flikens namn.
2. Läs kodsnuttarna A–J till höger.
3. Välj din gissning i rullgardinsmenyn under varje komponent.
4. Klicka på **Rätta** för att se hur många du fick rätt.
5. Klicka på **↺ Återställ komponenterna** för att starta om alla komponenter från början.

## Tips

- Titta på **beroendelistan** (`[]`, `[antal]`, `[sida]` …). Den avgör *när* effekten körs.
- Titta på **cleanup-funktionen** (`return () => …`). Vad städas bort?
- Klicka mer än en gång! Två komponenter kan göra samma sak första gången men olika saker andra gången.
- Vissa komponenter ser exakt likadana ut när du klickar. Skillnaden syns först i Network-fliken.
- Öppna fliken **Network** i DevTools (F12) och se vilka anrop som görs, och när.
- Fusk är inte tillåtet: titta inte i källkoden efter facit!

## Det här övar du på

- Komponenter och props (`Status`, `Lista`, `Knapp`)
- `.map()` och `key` för att rendera listor
- `useState` och event handlers
- Att uppdatera array-state rätt (spread, `filter`, `slice`) och vad som händer om man muterar state
- Villkorlig rendering
- `useEffect` med `[]`, med beroenden och med cleanup
- `fetch` med `.then()` och med `async/await`, felhantering med `try/catch`

## API:er som används

- [JSONPlaceholder](https://jsonplaceholder.typicode.com/) – testdata (användare)

## Kör lokalt

Öppna `index.html` i webbläsaren. React och Babel laddas från CDN, så du behöver internetanslutning.
