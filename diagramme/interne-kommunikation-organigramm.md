# Organisations- und Kommunikationsmodell

**Status:** Faktengrundlage mit einem noch zu beratenden Arbeitsvorschlag

**Quellen:** Vereinssatzung, Stand 31.01.2023; Website-Organigramm, Stand 02.09.2026; Klarstellung zum Schwerpunkt Interne Kommunikation vom 02.09.2026

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

    F --> OP[Operative Rollen und Teams<br/>z. B. Trainer · Betreuung · Platzwart · Spielbetrieb · Passwesen]
    EV -.->|personelle Überschneidungen und Beratung| F
    JA -.->|Jugendordnung und Jugendbelange| F2

    U[Unterstützende Aufgaben<br/>Finanzcontrolling · Recht · Datenschutz · Verträge] -.-> GV
    FV[Förderverein<br/>eigenständiger Partner] <-.-> GV
```

Die gestrichelten Verbindungen kennzeichnen Beziehungen, die nicht als einfache Weisungslinie zu verstehen sind. Das Diagramm ist keine neue Geschäftsordnung und begründet keine bislang nicht beschlossenen Befugnisse.

## Vorgeschlagener Weg für die tägliche Kommunikation

**Vorschlag:** Im Alltag soll nicht jede Information über den Vorstand laufen. Zuständige Personen sprechen direkt miteinander; die Hierarchie wird für Verantwortung, Entscheidungen und Eskalation genutzt.

```mermaid
flowchart LR
    A[Anliegen entsteht<br/>in Rolle oder Team] --> B{Im eigenen<br/>Auftrag lösbar?}
    B -->|Ja| C[Lösen und Betroffene<br/>informieren]
    B -->|Nein| D{Nur ein<br/>Funktionsbereich?}
    D -->|Ja| E[Fach- oder Bereichs-<br/>verantwortung einbeziehen]
    D -->|Nein| F[Betroffene Bereiche<br/>stimmen sich direkt ab]
    E --> G{Grundsatz, Finanzen,<br/>Konflikt oder Vereinsinteresse?}
    F --> G
    G -->|Nein| C
    G -->|Ja| H[Geschäftsführenden Vorstand<br/>oder zuständiges Organ einbeziehen]
    H --> I[Entscheidung und Begründung<br/>zurückmelden und dokumentieren]
```

## Noch zu vervollständigen

Für ein belastbares Ziel-Organigramm fehlen derzeit insbesondere:

- die Zuordnung aller Trainer- und Mannschaftsteams,
- benannte Gesamtverantwortliche und Stellvertretungen je Funktionsbereich,
- das genaue Verhältnis zwischen Website-Funktionsbereichen und erweitertem Vorstand,
- Entscheidungsspielräume der Rollen,
- verbindliche Übergaben und Eskalationswege,
- Kommunikationskanäle und Dokumentationsorte.

Diese Punkte sind Arbeitsauftrag des Schwerpunkts [Interne Kommunikation](../handlungsfelder/interne-kommunikation.md), nicht bereits beschlossene Organisationsänderungen.
