# Post mit Herz

![Das Post mit Herz Team](https://raw.githubusercontent.com/Post-mit-Herz/.github/main/profile/pmh_we.png)

Nicht erst seit der Corona-Pandemie leiden viele Menschen in Deutschland unter Einsamkeit. Manche haben keine Familie, niemanden, der sie anruft oder besucht. Sie leben zum Beispiel in Pflegeeinrichtungen, auf der Straße, in Wohnheimen oder in medizinischer Betreuung. Wir finden: Besonders in diesen harten Zeiten soll sich kein Mensch vergessen fühlen!

**Deshalb haben wir 2020 die ehrenamtliche Initiative Post mit Herz gegründet.**

![Post mit Herz Zahlen. 132.334 Schreiber:innen haben bisher bei 6 Aktionen 369.727 Karten geschrieben und an 4.358 Einrichtungen in ganz Deutschland verschickt.](https://raw.githubusercontent.com/Post-mit-Herz/.github/main/profile/pmh_reach.png)

**Unsere Mission:** Jeder einsame Mensch soll Post mit Herz bekommen.

Und du kannst uns dabei helfen: [postmitherz.org](https://postmitherz.org)

## Techstack

### Website

Die Website wird mit Wordpress betrieben. Dabei kümmert sich Wordpress um die Verwaltung der Einrichtungen, der Schreiber:innen, der einzelnen Karten und jede Art von Content, der auf der Website zu sehen ist.

### Services

Eine API stellt verschiedene Daten bereit, die uns ermöglichen weitere Services zu bauen. Dazu gehören:
- Eine iOS App, um unserem Support Team schnellen Zugriff auf die Daten zu geben.
- Ein iOS Widget, das den Verlauf einer Aktion anzeigt.
- Slackbots, die mit speziellen Commands Daten liefern.
- Scripte, um Mails mit verschiedenen Daten zu verschicken
- Scripte, um verschiedene Visualisierungen zu erstellen (Wie zB. die Deutschland-Karte oben)

### Ausblick

Aktuell bauen wir die Seite von Grund auf neu mit Typescript. Dabei haben wir Strapi als Backend/API. Das Frontend soll durch Astro erstellt werden. 