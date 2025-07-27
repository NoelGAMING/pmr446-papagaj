# Átjátszó/Papagáj Frekvenciák Térképe - Magyarország

Ez a webalkalmazás egy interaktív térképet jelenít meg Magyarország átjátszó és papagáj frekvenciáiról, csatornáiról, CTCSS kódjairól és adóállomásairól. A felhasználók könnyedén kereshetnek település, frekvencia vagy csatorna alapján, és megtekinthetik az adott helyszín részletes adatait.

---

## Főbb jellemzők

- **Interaktív térkép** Magyarország átjátszó állomásairól.
- **Keresőmező**, mely település, frekvencia vagy csatorna alapján szűr.
- Egyedi, animált marker ikonok a térképen.
- Reszponzív design, amely jól működik mobil eszközökön is.
- Saját pozíció megjelenítése a térképen egy gombnyomással.
- Részletes popup információk minden átjátszóhoz.
- Esri műhold térkép és határvonalak overlay.

---

## Technológiák

- HTML5, CSS3, JavaScript (ES6+)
- [Leaflet.js](https://leafletjs.com/) – nyílt forráskódú JavaScript könyvtár interaktív térképekhez
- OpenStreetMap Nominatim API – geokódoláshoz
- Esri térkép mozaikok (műhold és határok)

---

## Használat

1. Nyisd meg az `index.html` fájlt egy modern böngészőben.
2. A térképen látható marker ikonokra kattintva megtekintheted az adott átjátszó részleteit.
3. A keresőmezőbe beírhatsz települést, frekvenciát vagy csatornát, majd nyomj Entert vagy kattints a keresés ikonra.
4. A „❌” gombra kattintva törölheted a keresést.
5. A jobb alsó sarokban található jelmagyarázat segít az ikonok értelmezésében.
6. A „Saját pozícióm” gomb megmutatja az aktuális tartózkodási helyed (ha engedélyezed a helymeghatározást).

---

## Telepítés fejlesztőknek

A projekt statikus weboldal, így nincs szükség külön backendre.

1. Klónozd vagy töltsd le a projektet.
2. Nyisd meg az `index.html` fájlt böngészőben.
3. Szükség esetén helyi webszervert indíthatsz (például `Live Server` VS Code kiegészítővel).

---

## Adatok

Az átjátszók adatai kézzel kerültek hozzáadásra, beleértve a nevüket, frekvenciájukat, CTCSS kódjukat, csatornájukat, valamint a hozzájuk tartozó földrajzi koordinátákat.

---


## Licenc

Ez a projekt MIT licenc alatt áll. Szabadon használható, módosítható és terjeszthető.

---

## Kapcsolat

Ha kérdésed vagy javaslatod van, keress bizalommal!

---

_Készítette: NoelGAMING 
_© 2025_

