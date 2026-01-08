# Projekto įkėlimas į GitHub

Šiame faile pateikiama instrukcija, kaip įkelti „Mokomės Anglų!“ programėlės failus į GitHub saugyklą.

## Saugyklos informacija
- **URL:** [https://github.com/andriusgodeliauskas/app-english](https://github.com/andriusgodeliauskas/app-english)

## Komandos įkėlimui

Jei GitHub saugykla yra visiškai nauja (tuščia), terminale vykdykite šias komandas būdami `app-english` kataloge:

1. **Inicijuokite Git:**
   ```bash
   git init
   ```

2. **Pridėkite visus failus:**
   ```bash
   git add .
   ```

3. **Sukurkite pirmąjį komitą:**
   ```bash
   git commit -m "Initial commit: Children's English Learning Game"
   ```

4. **Nustatykite pagrindinę šaką:**
   ```bash
   git branch -M main
   ```

5. **Pridėkite nuotolinę saugyklą:**
   ```bash
   git remote add origin https://github.com/andriusgodeliauskas/app-english.git
   ```

6. **Išsiųskite failus:**
   ```bash
   git push -u origin main
   ```

---
*Pastaba: Jei saugykla jau turi failų, prieš siunčiant gali tekti atlikti `git pull origin main`.*
