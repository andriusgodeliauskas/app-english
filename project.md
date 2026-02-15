# App English — Mokomės Anglų!

Edukacinė anglų kalbos mokymosi programėlė 6 metų vaikams.

## Informacija

- **Tipas:** Statinis HTML (vienas failas)
- **Technologijos:** HTML5, CSS3, Vanilla JavaScript, Bootstrap 5.3
- **GitHub:** [github.com/andriusgodeliauskas/app-english](https://github.com/andriusgodeliauskas/app-english)
- **Domenas:** [english.godeliauskas.com](https://english.godeliauskas.com)
- **FTP serveris:** altas.serveriai.lt → `/domains/english.godeliauskas.com/public_html`

## Funkcionalumas

- **18 pamokų**, 150+ žodžių (flashcard mokymasis + quiz žaidimas)
- **110 prizų** parduotuvė su žvaigždučių sistema (kainos 10–1000)
- Web Speech API tarimas, konfeti efektai, streak bonusai
- Duomenys saugomi naršyklės LocalStorage

## Deploy

```bash
bash deploy.sh
```

Arba rankiniu būdu: tiesiog įkelti `index.html` į FTP serverį.

## Git

```bash
git add .
git commit -m "Aprašymas"
git push origin main
```

## Svarbu

- `deploy.sh` — **nekelti į git** (turi FTP prisijungimus)
