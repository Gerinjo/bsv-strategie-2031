# Organisations- und Kommunikationsmodell

**Status:** Faktengrundlage mit einem noch zu beratenden Arbeitsvorschlag

**Quellen:** Vereinssatzung, Stand 31.01.2023; Website-Organigramm, Stand 02.09.2026; Klarstellungen und ergänzende Beschreibung der Kommunikationspraxis vom 02.09.2026

## Was die vorhandenen Grundlagen sagen

Das folgende Bild verbindet zwei unterschiedliche Perspektiven:

- Die **Satzung** legt die formalen Organe, Zuständigkeiten und Aufsicht fest.
- Das **Website-Organigramm** ordnet die laufende Vereinsarbeit in sieben Funktionsbereiche.

Beide Darstellungen sind richtig, aber nicht deckungsgleich. Insbesondere ist der erweiterte Vorstand im veröffentlichten Organigramm keine eigene Ebene und die operative Ebene mit Trainerteams und weiteren Aufgaben ist dort noch nicht vollständig dargestellt.

```mermaid
flowchart TD
    MV[Mitgliederversammlung<br/>oberstes Organ laut Satzung]

    subgraph O[Formale Organe laut Satzung]
        GV[Geschäftsführender Vorstand<br/>1. und 2. Vorsitz · Kasse · Schriftführung]
        EV[Erweiterter Vorstand<br/>GV · Jugendleitung · 2. Kasse · Organisationsleitung · Abteilungsleitungen]
        JA[Jugendausschuss]
    end

    MV -->|wählt bzw. bestätigt nach Satzung| GV
    MV -->|Wahlen und Benennungen nach Satzung| EV
    MV -.->|Jugendvertretung über Jugendversammlung| JA

    GV -->|Leitung des Vereins| F
    GV -->|Weisungsbefugnis laut Satzung| AA[Abteilungen und Ausschüsse]

    subgraph F[Sieben Funktionsbereiche des Website-Organigramms]
        F1[Fußball]
        F2[Jugend & Entwicklung]
        F3[Breitensport]
        F4[Vereinspflege]
        F5[Events]
        F6[Marketing & Kommunikation]
        F7[Facility Management]
    end

    F --> OP[Weitere operative Rollen und Teams<br/>z. B. Platzwart · Spielbetrieb · Passwesen]
    EV -.->|personelle Überschneidungen und Beratung| F
    JA -.->|Jugendordnung und Jugendbelange| F2

    U[Unterstützende Aufgaben<br/>Finanzcontrolling · Recht · Datenschutz · Verträge] -.-> GV
    FV[Förderverein<br/>eigenständiger Partner] <-.-> GV
```

Die gestrichelten Verbindungen kennzeichnen Beziehungen, die nicht als einfache Weisungslinie zu verstehen sind. Das Diagramm ist keine neue Geschäftsordnung und begründet keine bislang nicht beschlossenen Befugnisse.

## Arbeitsmodell für die interne Kommunikationskette

**Beobachtung vom 02.09.2026:** Die Vorstandschaft trifft sich regelmäßig mit den Abteilungsleitungen. Die Weitergabe verbindlicher Informationen erfolgt anschließend von Ebene zu Ebene. Die Abteilungsleitungen organisieren den Informationsfluss innerhalb ihrer jeweiligen Abteilung.

```mermaid
flowchart TD
    V[Vorstandschaft] <-->|regelmäßige Sitzungen| AL[Abteilungsleitungen]

    AL --> JL[Jugendleitung]
    AL --> SH[Sportliche Leitung Herren]
    AL --> SD[Sportliche Leitung Damen]
    AL --> AH[Repräsentant der Alten Herren]

    JL --> TJ[Trainerteams Jugend]
    SH --> TH[Trainerteams Herren]
    SD --> TD[Trainerteams Damen]
    AH --> TAH[Trainerteams AH]

    TJ --> MJ[Mannschaftsumfeld Jugend]
    TH --> MH[Mannschaftsumfeld Herren]
    TD --> MD[Mannschaftsumfeld Damen]
    TAH --> MAH[Mannschaftsumfeld AH]
```

Die Pfeile von oben nach unten zeigen die Weitergabe von Informationen. Rückmeldungen, Bedarfe und Eskalationen laufen über dieselben Ebenen in umgekehrter Richtung. Die genaue formale Zuordnung der dargestellten sportlichen Rollen zu den Satzungsorganen und den sieben Website-Funktionsbereichen ist noch zu bestätigen.

## Noch zu vervollständigen

Für ein belastbares Ziel-Organigramm fehlen derzeit insbesondere:

- die formale Bestätigung der Zuordnung von Jugendleitung, sportlichen Leitungen Herren und Damen sowie dem Repräsentanten der Alten Herren,
- die benannten Trainerteams und nachgelagerten Empfängerkreise je sportlichem Bereich,
- benannte Gesamtverantwortliche und Stellvertretungen je Funktionsbereich,
- das genaue Verhältnis zwischen Website-Funktionsbereichen und erweitertem Vorstand,
- Entscheidungsspielräume der Rollen,
- verbindliche Übergaben und Eskalationswege,
- Kommunikationskanäle und Dokumentationsorte.

Diese Punkte sind Arbeitsauftrag des Schwerpunkts [Interne Kommunikation](../handlungsfelder/interne-kommunikation.md), nicht bereits beschlossene Organisationsänderungen.
