# Poklad Danielkových – svatební web

Statický web, stačí nahrát celou složku (index.html + img/) na libovolný hosting
(Netlify, GitHub Pages, Vercel, webhosting přes FTP…). Žádný build, žádný server.

- `index.html` – celá hra na jedné stránce bez rolování: 9 obrazovek, striktně po sobě (tlačítko Pokračovat se odemkne až po splnění úkolu obrazovky); úkoly, zámky a hádanka se otevírají v panelech přes scénu.
- `img/` – ilustrace z původního Canva webu, zmenšené figurky a klíče.
- Úkoly na LearningApps a kvíz na Faabulu se otevírají v nové záložce.
- Postup hráčů (klíčová slova, odemčené zámky, hádanka) se ukládá jen v prohlížeči (localStorage).
- Odpovědi k zámkům a hádance jsou v kódu uložené jen jako otisky (hash), ne jako text.
