# Strategiearchitektur nach der Strategietagung

Das Diagramm trennt die vier orientierenden Werte, das breite Zukunftsbild und die fünf aktuell priorisierten Arbeitsschwerpunkte. Die Schwerpunktteams sollen daraus konkrete Ziele und Initiativen entwickeln.

```mermaid
flowchart TD
    subgraph W[Werte als Orientierung]
        W1[Familiär]
        W2[Weiterentwicklung]
        W3[Nachhaltigkeit]
        W4[Offenheit]
    end

    W --> Z[Zukunftsbild BSV 2031]

    subgraph B[Bausteine des Zukunftsbilds]
        B1[Gemeinschaft und Vereinskultur]
        B2[Kommunikation und Führung]
        B3[Sport und Jugend]
        B4[Ehrenamt und Organisation]
        B5[Außenwirkung und Vereinsleben]
    end

    Z --> B
    B --> S1[Infrastruktur]
    B --> S2[Externe Kommunikation]
    B --> S3[Ehrenamt]
    B --> S4[Interne Kommunikation]
    B --> S5[Sponsoring]

    S1 --> I[Konkrete Ziele und Initiativen]
    S2 --> I
    S3 --> I
    S4 --> I
    S5 --> I
```
