# Empyria v0.33 — compleet uploadpakket

1. Maak eerst een reservekopie van de huidige repository via Code > Download ZIP.
2. Pak deze export uit op je computer.
3. Vervang de bestanden in je bestaande Empyria-MAIN-repository door de inhoud van dit pakket. Verwijder de repository zelf niet, zodat het Pages-adres behouden blijft.
4. Upload index.html, README.md en de VOLLEDIGE assets-map inclusief submappen. Upload niet de zip of de bovenliggende map.
5. Commit en wacht tot de GitHub Pages-publicatie klaar is.
6. Open https://fortunefiinc-spec.github.io/Empyria-MAIN/index.html?v=033 en stel dit adres in bij BotFather.

## Structuur
index.html
README.md
assets/
  telegram-mobile.css
  audio/empyria-music.mp3
  audio/empyria-music2.mp3
  js/game.js
  js/industrial-pack.js
  js/startup-1.js
  js/telegram-account.js
  vendor/three.min.js

Geen buildstap of backend nodig. Oudere GLB-modellen, SQL en TON Connect-configuratie worden door deze versie niet gebruikt. Bewaar ze in je reservekopie voor eventueel later gebruik.
De Telegram-username verschijnt wanneer Telegram accountgegevens doorgeeft. Dit pakket bevat geen serverlogin, database of wallet-integratie.
