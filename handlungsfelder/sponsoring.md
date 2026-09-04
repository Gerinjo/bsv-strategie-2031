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

**Fakt (veröffentlicht am 04.09.2026):** Die Sponsorenverwaltung gliedert Werbepartner in Akkordeons. Partner mit noch nicht freigegebenem Logo stehen alphabetisch sortiert, aufgeklappt und sichtbar priorisiert oben. Freigegebene Partner folgen alphabetisch sortiert in kompakter, geschlossener Darstellung. Ein darüber angeordneter Live-Filter reduziert beide Gruppen während der Eingabe.

- [Social-Media-Suite: priorisierte Sponsoren-Akkordeons und Live-Filter](https://github.com/Gerinjo/bsv-socialmedia/commit/28d30e9)

**Fakt (veröffentlicht am 04.09.2026):** Die Landingpage „Junge Sterne“ zeigt Jugendleitung und Jugendgeschichte oberhalb des Sponsorbereichs. Unterhalb der Sponsoren folgen die Mannschaften in den drei Gruppen „Leistungssport“, „Breitensport“ und „Juniorinnen“. Der Sponsorbereich ergänzt damit die bestehenden Jugendinhalte, statt sie zu ersetzen.

- [Website: vollständige Jugend-Landingpage mit ergänzendem Sponsorbereich](https://github.com/Gerinjo/bsv-website/commit/6d7be8c)

**Fakt (veröffentlicht am 04.09.2026):** Das Megamenü „Junge Sterne“ zeigt unterhalb des Jugendbildes drei bei jedem Seitenaufruf zufällig ausgewählte Werbepartner. Berücksichtigt werden direkte Zuordnungen zur Jugendabteilung und zu einzelnen Jugendmannschaften. Der Link „Alle Jugendsponsoren“ führt zur Werbepartnerübersicht mit vorausgewähltem Filter „Jugendabteilung“.

- [Website: Jugendsponsoren im Megamenü](https://github.com/Gerinjo/bsv-website/commit/f50091b)

**Fakt (veröffentlicht am 04.09.2026):** Die drei Werbepartner im Jugend-Megamenü werden jeweils über die volle Breite der rechten Menüspalte und untereinander dargestellt. Die Höhe der Logos ist begrenzt, damit unterschiedliche Logoformate innerhalb ihrer jeweiligen Zeile bleiben.

- [Website: vollbreite Sponsorenzeilen im Jugend-Megamenü](https://github.com/Gerinjo/bsv-website/commit/78d3b06)

**Fakt (veröffentlicht am 04.09.2026):** Der Bereichsfilter der Werbepartnerübersicht bietet nur Bereiche an, denen mindestens ein veröffentlichter Partner zugeordnet ist. „Alle Bereiche“ bleibt unabhängig davon verfügbar. Leere Bereiche werden nicht als auswählbare Option gezeigt.

- [Website: leere Bereiche aus dem Werbepartnerfilter entfernt](https://github.com/Gerinjo/bsv-website/commit/84e33f8)

**Fakt (veröffentlicht am 04.09.2026):** Die Werbepartnerübersicht verwendet auf Desktop-Bildschirmen ein Raster mit vier Partnerkarten pro Zeile. Auf mittleren Bildschirmen werden zwei Karten und auf Mobilgeräten eine Karte pro Zeile dargestellt. Sponsorarten mit weniger als vier Partnern bleiben ohne leere Platzhalter linksbündig.

- [Website: vier Werbepartner pro Zeile](https://github.com/Gerinjo/bsv-website/commit/3984a81)

**Fakt (lokal umgesetzt, noch nicht veröffentlicht, 04.09.2026):** Das zuvor veröffentlichte Vierer-Raster wird durch drei Partnerkarten pro Zeile ersetzt. Dadurch nutzen Sponsorarten mit drei Partnern die verfügbare Breite vollständig und die einzelnen Logos sowie Partnernamen erhalten mehr Raum. Tablet und Mobil bleiben bei zwei beziehungsweise einer Karte pro Zeile.

- [Website: Drei-Spalten-Raster für Werbepartner](https://github.com/Gerinjo/bsv-website/commit/fbba918)

**Offene Frage:** Welche Werbepartner sollen künftig Bogensport, Gymnastik oder Wandergruppe direkt zugeordnet werden?
