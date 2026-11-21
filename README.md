# NEXA Cloud

Dit is de publieke statische website voor het bestaande NEXA Smart Hub-project.

## Wat werkt in deze versie
- Inloggen met hetzelfde Supabase Auth-account als de NEXA Android-app.
- Eigen hub-heartbeat, apparaten, integraties en scènes uitlezen uit het bestaande NEXA-project.
- Vernieuwen om de 15 seconden.
- Alleen de Supabase publishable key staat in de browser. Er staat geen service-role key of apparaatwachtwoord in deze repository.

## Belangrijk
- De website kan beveiligde opdrachten naar de eigen NEXA-tablet sturen voor ondersteunde acties (Hue, tabletvolume/-helderheid, PS5 Wake-on-LAN, Spotify openen en Chromecast-apps).
- De Android-tablet blijft de lokale hub die opdrachten op het thuisnetwerk uitvoert.
- De website toont echte databasegegevens; lege tabellen blijven leeg.
- Toegang tot gegevens is afhankelijk van Supabase Auth en de bestaande Row Level Security (RLS)-policies.

## Publicatie
GitHub Actions publiceert de root van deze repository naar GitHub Pages. Zet in GitHub bij **Settings → Pages** de **Build and deployment source** op **GitHub Actions** als Pages nog niet automatisch is ingeschakeld.
