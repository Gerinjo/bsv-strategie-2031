# Schwerpunkt: Sponsoring

**Status:** Schwerpunktteam arbeitet an der Konkretisierung
**Erste Teamzuordnung:** Jerome, Felix, Claudia
**Quelle:** [Strategietagung vom 16.08.2026](../protokolle/2026-08-16-strategietagung.md)

## Mitarbeitende und Ansprechpersonen

| Funktion | Personen |
| --- | --- |
| Schwerpunktteam | Jerome, Felix, Claudia |
| Themenübergreifende Inputgeberin und Ansprechpartnerin | Sandra |

## Ausgangspunkt

Sponsoring wurde in der Vereinsumfrage als eigenes Thema und anschließend als strategischer Schwerpunkt ausgewählt. Eine gemeinsame Zielsetzung und ein abgestimmtes Leistungsversprechen sind noch zu erarbeiten.

## Bezug zu Werten und Zukunftsbild

- nachhaltige und verlässliche Partnerschaften
- gemeinsames Erscheinungsbild und bessere Außenwirkung
- positive Vereinsgeschichten sichtbar machen
- Heimspiele und Veranstaltungen als attraktive Kontaktpunkte entwickeln
- Sponsoring an gemeinsamen Vereinszielen ausrichten

## Auftrag bis 04.10.2026

- [ ] weitere geeignete Mitwirkende gewinnen
- [ ] bestehende Partner, Vereinbarungen, Leistungen und Zuständigkeiten erfassen
- [ ] Ziele und Nutzen für Verein und Partner konkretisieren
- [ ] erste Entwürfe für Angebot, Ansprache und Betreuung vorbereiten

## Offene Fragen

- Welche Arten von Partnerschaften passen zu den vier Vereinswerten?
- Welche Gegenleistungen kann der BSV zuverlässig und einheitlich anbieten?
- Wie werden Akquise, Vereinbarung, Betreuung und Verlängerung organisiert?
- Wie greifen Sponsoring, Website, Social Media, Spieltage und Veranstaltungen ineinander?

## Technische Umsetzung

**Fakt (Arbeitsstand 04.09.2026):** Die technische Zuordnung von Werbepartnern wurde so angepasst, dass Website-Bereiche und Mannschaften ausschließlich ihre direkten Zuordnungen erhalten. Eine Zuordnung zur Jugendabteilung wird nicht mehr automatisch auf alle Jugendmannschaften vererbt.

- [Website: Jugend-Sponsorenauswahl, Bereichs-/Sponsorartenfilter und direkte Mannschaftszuordnung](https://github.com/Gerinjo/bsv-website/commit/e9f1e36)
- [Social-Media-Suite: direkte Website-Zuordnungen und zusätzliche Abteilungsziele](https://github.com/Gerinjo/bsv-socialmedia/commit/2ee53b2)

**Beobachtung:** Auf der Jugendseite können nur so viele unterschiedliche Partner zufällig angezeigt werden, wie aktuell für die Jugendabteilung oder deren Mannschaften freigegeben sind; die Darstellung ist auf höchstens vier begrenzt.

**Fakt (veröffentlicht am 04.09.2026):** Sponsorarten erhalten neben ihrer Sortierung eine Gewichtung mit den Stufen „Standard“, „Hervorgehoben“ und „Premium“. Die Website nutzt diese Gewichtung für Reihenfolge, Kartengröße und Logopräsenz. Der Hauptmenüpunkt „Sponsoring“ führt zur Werbepartnerübersicht; die Sponsoring-Pakete bleiben als eigene Menüpunkte erreichbar. Der Logo-Upload der Verwaltung unterstützt zusätzlich sicher geprüfte SVG-Dateien, die für die Ausspielung in PNG-Varianten umgewandelt werden.

- [Social-Media-Suite: SVG-Upload und Gewichtung der Sponsorarten](https://github.com/Gerinjo/bsv-socialmedia/commit/0e0c3f6)
- [Website: gewichtete Übersicht und geänderte Sponsoring-Navigation](https://github.com/Gerinjo/bsv-website/commit/4e64fd3)

**Fakt (veröffentlicht am 04.09.2026):** Das Sponsoring-Menü zeigt „Partner“ als gelb markierten Standard-Reiter. Die Sponsoring-Pakete bleiben zunächst ausgeblendet und werden erst nach Auswahl des Reiters „Pakete“ angezeigt. Ein Klick auf den Hauptmenüpunkt „Sponsoring“ führt weiterhin direkt zur Partnerübersicht.

- [Website: Partner als Standardansicht im Sponsoring-Menü](https://github.com/Gerinjo/bsv-website/commit/816af43)

**Fakt (lokal umgesetzt, noch nicht veröffentlicht, 04.09.2026):** Die Sponsorenverwaltung gliedert Werbepartner in Akkordeons. Partner mit noch nicht freigegebenem Logo stehen alphabetisch sortiert, aufgeklappt und sichtbar priorisiert oben. Freigegebene Partner folgen alphabetisch sortiert in kompakter, geschlossener Darstellung. Ein darüber angeordneter Live-Filter reduziert beide Gruppen während der Eingabe.

- [Social-Media-Suite: priorisierte Sponsoren-Akkordeons und Live-Filter](https://github.com/Gerinjo/bsv-socialmedia/commit/28d30e9)

**Offene Frage:** Welche Werbepartner sollen künftig Bogensport, Gymnastik oder Wandergruppe direkt zugeordnet werden?
