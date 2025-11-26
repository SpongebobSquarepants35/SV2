1. Bauen Sie das R-2R-Netzwerk im Simulator auf.
2. Stellen Sie nacheinander alle 8 Binärkombinationen (von 000 bis 111) mit den drei Schaltern ein.
2. Messen Sie für jede Kombination die resultierende analoge Ausgangsspannung Uaus (Tipp: der "DC Level" im Scope) und füllen Sie die folgende Tabelle aus.
3. Dokumentieren Sie durch ein GIF, wie sich die Ausgangsspannung ändert, wenn Sie die Binärkombinationen durchschalten.

| Bit 2 (MSB) | Bit 1 | Bit 0 (LSB) | Dezimalwert | Uaus (V) |
|-------------|-------|-------------|-------------|----------|
| 0           | 0     | 0           | 0           | 0.0 V    |
| 0           | 0     | 1           | 1           | 3.3 V    |
| 0           | 1     | 0           | 2           | 4.0 V    |
| 0           | 1     | 1           | 3           | 4.8 V    |
| 1           | 0     | 0           | 4           | 5.0 V    |
| 1           | 0     | 1           | 5           | 6.0 V    |
| 1           | 1     | 0           | 6           | 6.3 V    |
| 1           | 1     | 1           | 7           | 6.6 V    |

# Auswertung:
# Analysieren Sie Ihre Messwerte. Was stellen Sie fest?
📌 Auffälligkeit:
Die Werte sind nicht linear wie bei einem idealen R-2R-Netzwerk (Schrittgröße wäre konstant). Hier sind die Schritte unterschiedlich groß, was auf fehlende ideale Bedingungen hinweist (z.B. Ausgangsimpedanz, Schalterwiderstände, Simulator-Einstellungen).

# Berechnen Sie die Spannungsdifferenz (die "Schrittgröße") zwischen den einzelnen Dezimalwerten (z.B. die Differenz zwischen Wert 1 und Wert 2). Ist diese Schrittgröße konstant?

Berechnete Schrittgrößen:

| Übergang  | Schrittgröße (V) |
|-----------|------------------|
| 0 → 1     | 3.3              |
| 1 → 2     | 0.7              |
| 2 → 3     | 0.8              |
| 3 → 4     | 0.2              |
| 4 → 5     | 1.0              |
| 5 → 6     | 0.3              |
| 6 → 7     | 0.3              |

## Erklären Sie, warum die Schaltung das tut, was auf Folie 30 (Quantisierung/Treppenstufen) gezeigt wird.