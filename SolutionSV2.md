# Student Information

|                   |                               |
|-------------------|-------------------------------|
| Name              | XXXXXXXXXXXXXX                |
| Matrikelnummer    | XXXXXX                        |
| Studiengang       | Software engineering Bachelor |
| Kurs              | SV2                           |
| Betreuer          | Prof. Dr. supervisor          |
| Akademisches Jahr | 2025/2026                     |


# Task 1
## 1 
"Berechnung: Berechnen Sie zuerst die theoretische Resonanzfrequenz f₀ mit der Formel von Folie 5 und den gegebenen Werten"

  f₀ = 1 / (2π√(LC))
  1/(2π√(10*10^-3 * 100*10^-9))
  Desmos -> 5032.92121045Hz

## 2
"Simulation: Bauen Sie die Schaltung auf. Finden Sie im Simulator die Frequenz, bei der der Strom I maximal ist. (Tipp: Verwenden Sie einen "Slider" für die Frequenz und beobachten Sie die Helligkeit/Geschwindigkeit der fließenden Punkte)."

 Task1 GIF
 ![Task1 GIF](https://github.com/SpongebobSquarepants35/SV2/blob/main/HDGifs/Task1SV2HD.gif)

## 2
  ~5kHz

## 3
"Dokumentation: Notieren Sie die Frequenz, die Sie im Simulator gemessen haben."

| Rechenwert  | Messwert | Folie 7     |
|-------------|----------|-------------|
| 5032.92 Hz  | 5 kHz    | 1300 Hz     |

## 4
"Vergleich: Vergleichen Sie Ihren Rechenwert (aus 1.), Ihren Messwert (aus 3.) und den Wert auf Folie 7. Was stellen Sie fest?"

Rechenwert und Messwert sind nahezu identisch und die Schaltung von Folie 7 verwendet nicht identische Bauteile in den Werten was zu einer anderen Frequenz führt.

# Task 2
## 1
"Finden Sie eine Methode in der Simulationssoftware, um den Frequenzgang des Stroms sichtbar zu machen. (Tipp: Die Spannung am Widerstand R ist proportional zum Strom I)."
## 2
"Stellen Sie den Widerstand R so ein, dass Sie ihn interaktiv verändern können (z.B. mit einem Schieberegler)."
## 3
"Dokumentieren Sie durch ein GIF, wie sich die Form der Resonanzkurve (die "Peak-Form") ändert, wenn Sie R von einem sehr kleinen Wert (z.B. 5 Ω) zu einem großen Wert (z.B. 300 Ω) ändern."

 Task2 GIF
 ![Task2 GIF](https://github.com/SpongebobSquarepants35/SV2/blob/main/HDGifs/Task2SV2HD.gif)
## 4 
"Erklären Sie den Zusammenhang, den Sie beobachten:
1. Was passiert mit der Höhe des Peaks?
2. Was passiert mit der Breite des Peaks?
3. Was bedeutet das für die Güte Q und die Bandbreite der Schaltung (vgl. Folie 9)?"

### Erklärung.
1. Die hohe des Peaks wird mit zunehmenden Widerstandwertes geringer
2. Die Breite des Peaks wird mit zunehmenden Widerstandwertes schmaler
3. Je geringer der Widerstandwert ist desto höher die Güte und schmaler die Bandbreite. Mit steigendem Widerstandswert sinkt die Güte und steigt die Bandbreite.

# Task 3
## 1 
"Bauen Sie beide Schaltungen im Simulator auf."
## 2 
"Berechnen Sie zuerst die erwartete Resonanzfrequenz f₀ (Thomsonsche Formel)."
  f₀ = 1 / (2π√(LC))
  1/(2π√(1*10^-3 * 10*10^-9))
  Desmos -> 50329.2121045Hz
## 3
"Simulieren Sie den Frequenzgang der Ausgangsspannung für beide Schaltungen (z.B. in einem Bereich von 15 kHz bis 30 kHz)."
## 4
"Dokumentieren Sie Ihre Ergebnisse durch GIFs, die den Frequenzgang beider Schaltungen zeigen."

 Task3 GIFs
 ![Task3 GIF](https://github.com/SpongebobSquarepants35/SV2/blob/main/HDGifs/Task3SV2LongHD.gif)
## 5
"Beantworten Sie die folgenden Fragen:
1. Bestätigt Ihre Simulation die berechnete Resonanzfrequenz?
2. Beschreiben Sie präzise das gegensätzliche Verhalten der beiden Schaltungen bei dieser Frequenz.
3. Erklären Sie Warum führt Aufbau 1 (Parallelschwingkreis als Ausgang) zu einem Spannungsmaximum, während Aufbau 2 (Reihenschwingkreis parallel zum Ausgang) zu einem Spannungsminimum führt?
(Tipp: Denken Sie an die Impedanz. Wie verhält sich ein Parallelschwingkreis bei f₀? Und wie ein Reihenschwingkreis?)"

### Erklärung
1. Die berechnete Frequenz stimmt ~ mit der Simulation überein.
2. Bei der Bandpass Schaltung ist die Spannung mit der Resonanzfrequenz am höchsten und bei der Bandsperre ist die Spannung minimal.
3. 
Parallelschwingkreis:
Bei Resonanz ist Impedanz maximal und die Spannung steigt.
Reihenschwingkreis:
Bei Resonanz ist Impedanz minimal und die Spannung Spannung fällt.

# Task 4
## 1
"Bauen Sie das R-2R-Netzwerk im Simulator auf."
## 2
"Stellen Sie nacheinander alle 8 Binärkombinationen (von 000 bis 111) mit den drei Schaltern ein."
## 3
"Messen Sie für jede Kombination die resultierende analoge Ausgangsspannung Uaus (Tipp: der "DC Level" im Scope) und füllen Sie die folgende Tabelle aus."

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

## 4
"Dokumentieren Sie durch ein GIF, wie sich die Ausgangsspannung ändert, wenn Sie die Binärkombinationen durchschalten."

 Task4 GIF
 ![Task4 GIF](https://github.com/SpongebobSquarepants35/SV2/blob/main/HDGifs/Task4SV2HD.gif)

## 5
"Auswertung:

1. Analysieren Sie Ihre Messwerte. Was stellen Sie fest?
2. Berechnen Sie die Spannungsdifferenz (die "Schrittgröße") zwischen den einzelnen Dezimalwerten (z.B. die Differenz zwischen Wert 1 und Wert 2). Ist diese Schrittgröße konstant?
3. Erklären Sie, warum die Schaltung das tut, was auf Folie 30 (Quantisierung/Treppenstufen) gezeigt wird."

### Erklärung
1. der Anstieg der Spannung ist nicht Linear
2. 
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

Die Schrittgröße ist nicht Konstant

3. Die Schaltung kann mithilfe von Widerständen und 3 Schaltern (3Bits) unterschiedliche Spannung erzeugen mit dem es mithilfe von Pulsamplitudenmodulation z.B eine Sinuskurve erzeugen kann.



# Task 5
## 1
"Berechnung: Berechnen Sie die theoretische Resonanzfrequenz f₀ für den LC-Bandpass (L = 1 mH, C = 10 nF). Notieren Sie Ihren Rechenweg und das Ergebnis."

  1/(2π√(1*10^-3 * 10*10^-9))
  Desmos -> 50329.2121045Hz

## 2
"Aufbau: Bauen Sie den Bandpass-Filter vom Typ auf Folie 12 (oberes Bild) im Simulator nach. Verwenden Sie Ri = 2,2 kΩ und die gegebenen L/C-Werte"
## 3
"Simulation:
1. Speisen Sie die Schaltung mit einer Rechteckspannung (Square Wave).
2. Stellen Sie die Grundfrequenz f₁ der Rechteckwelle genau auf die in Schritt 1 berechnete Resonanzfrequenz f₀ ein."
## 4
"Messung & Dokumentation:
1. Öffnen Sie das Oszilloskop ("Scope") und zeigen Sie das Eingangssignal (an der Quelle) und das Ausgangssignal (über dem L/C-Parallelkreis) gleichzeitig an.
2. Dokumentieren Sie durch ein GIF, das beide Wellenformen zeigt."

 Task5 GIF
 ![Task5 GIF](https://github.com/SpongebobSquarepants35/SV2/blob/main/HDGifs/Task5SV2HD.gif)

## 5
"Erklärung:
1. Beschreiben Sie den Unterschied zwischen der Eingangs- und der Ausgangswellenform.
2. Erklären Sie mit Verweis auf die Fourier-Analyse (Folie 25), warum das Ausgangssignal diese Form hat. Welche Frequenzkomponenten der Rechteckwelle lässt der Filter passieren und welche blockiert er?"

### Erklärung
1. 
Eingangswellenform: Squarewave 
Ausgangswellenform: Sinus- oder Dreieckwellen förmig
2. 
Eingangssignal: Rechteckwellen enthält die Grundfrequenz f0​ und ungerade Harmonische (3f1, 5f1​​, …).
Ausgangssignal: Fast Sinuswellen förmig bei f0, da:

LC-Bandpass hat hohe Güte um f0​.
Filter blockiert höhere Harmonische die weit außerhalb der Resonanz liegen.

Fourier: Rechteckwellen bestehen aus einer Summe von Sinuswellen. der Bandpass lässt nur die Grundschwingung durch damit liegt am Ausgang ≈ Sinus an.

# Task 6
## 1
1. Stellen Sie die Quelle auf "Sine" (Sinus), 5V Amplitude.
2. Führen Sie eine AC-Analyse ("Frequency"-Plot) am Ausgang (V) durch.
3. Finden Sie die Frequenz, bei der die Schaltung ihre stärkste Resonanz (größte Verstärkung) zeigt.

### Erklärung
3. ~781kHz

## 2
1. Ändern Sie die Quelle zu einer "Square Wave" (Rechteck), 5V Amplitude.
2. Stellen Sie die Grundfrequenz der Rechteckwelle auf 1,18 MHz ein. (Dies ist 1/3 der Resonanzfrequenz aus Schritt 1).
3. Betrachten Sie den Eingang und den Ausgang (V) im Zeitbereich (Scope).
4. Betrachten Sie den Eingang und den Ausgang (V) im Frequenzbereich (FFT / "Frequency").

### Erklärung
3. Spannung ist höher als die Eingangsspannung von 5V = 6.868V
4. Die Frequenz ist die Gleiche als die Eingangsfrequenz von 1,18 MHz aber die hohen Harmonischen sind stark abgeschwächt. Daraus folgt eine Sinusförmige Welle.

## 3 Variation (Optional)
1. Ändern Sie die Grundfrequenz der Rechteckwelle auf 712 kHz. (Dies ist 1/5 der Resonanzfrequenz).
2. Beobachten Sie erneut das Spektrum am Ausgang.

### Erklärung
2. Die Spannung Ausgangsspannung ist nochmals höher als in Schritt 2 und die erste harmonische Frequenz ist immer noch gleich aber es ist eine höhere harmonische frequenz in der Ausgangsfrequenz dies es zu einer Unförmigen Sinuswelle macht.

## Auswertung 
Beantworten Sie die folgenden Fragen basierend auf Ihren Beobachtungen aus Schritt 2:

1. Zeitbereich: Vergleichen Sie das Eingangs- und Ausgangssignal. Welche Form hat das Ausgangssignal? Welche Frequenz hat es (grob gemessen)?
2. Frequenzbereich (Eingang): Beschreiben Sie das Spektrum der Rechteckwelle, das Sie sehen. Welche Harmonischen sind vorhanden (1., 3., 5. ...)?
3. Frequenzbereich (Ausgang): Beschreiben Sie das Spektrum am Ausgang. Was ist mit der Grundschwingung (1,18 MHz) passiert? Was ist mit der 3. Harmonischen (3,56 MHz) passiert?
4. Erklärung: Fassen Sie zusammen, was der Filter mit dem Rechtecksignal gemacht hat und warum das Ausgangssignal so aussieht, wie es aussieht.

### Erklärung
1. Eingangssignal: Squarwave, Ausgangssignal: Sinwave
2. Eingang:
Berechnete Harmonische:

| Harmonische | Frequenz  |
|-------------|-----------|
| 1           | 1,18 MHz  |
| 3           | 3,54 MHz  |
| 5           | 5,90 MHz  |
| 7           | 8,26 MHz  |
| 9           | 10,62 MHz |


3. bei 1,18Mhz Squarewave ist nichtmehr die 3. Harmonische und höher sichtbar im Ausgangssignal nurnoch die grundfrquenz 1,18Mhz
4. Die höheren Harmonischen werden herausgefiltert und nur die erste Harmonische durchgelassen. Das Eingangssignal Squarwave mit höheren harmonischen wird zu einem Siunusförmigen Ausgangssingnal mit nur der 1. Harmonischen. 
