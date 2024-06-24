### RGB-Farbcodes:
1. **RGB(255, 255, 255)** entspricht Farbe: Weiß
2. **RGB(0,0,0)** entspricht Farbe: Schwarz
3. **RGB(252,178,91)** entspricht Farbe: Mandarine

### HEX-Farbcodes:
1. **#FF0000** entspricht Farbe: Rot
2. **#00FF00** entspricht Farbe: Grün
3. **#0000FF** entspricht Farbe: Blau
4. **#FFFF00** entspricht Farbe: Gelb
5. **#00FFFF** entspricht Farbe: Cyan
6. **#FF00FF** entspricht Farbe: Magenta
7. **#000000** entspricht Farbe: Schwarz
8. **#FFFFFF** entspricht Farbe: Weiß
9. **#00BC00** entspricht Farbe: Grünes Mittel

### CMYK-Farbcodes:
1. **C:0%, M:100%, Y:100%, K:0%** entspricht Farbe: Rot
2. **C:100%, M:0%, Y:100%, K:0%** entspricht Farbe: Grün
3. **C:100%, M:100%, Y:0%, K:0%** entspricht Farbe: Blau
4. **C:0%, M:0%, Y:100%, K:0%** entspricht Farbe: Gelb
5. **C:100%, M:0%, Y:0%, K:0%** entspricht Farbe: Cyan
6. **C:0%, M:100%, Y:0%, K:0%** entspricht Farbe: Magenta
7. **C:100%, M:100%, Y:100%, K:0%** entspricht Farbe: Schwarz
8. **C:0%, M:0%, Y:0%, K:100%** entspricht Farbe: Schwarz
9. **C:0%, M:0%, Y:0%, K:0%** entspricht Farbe: Weiß
10. **C:0%, M:46%, Y:38%, K:22%** entspricht Farbe: Koralle

### Speicherbedarf eines unkomprimierten RGB-Bildes
Für ein unkomprimiertes RGB-Bild mit der Größe 640 x 480 und 8 Bit Auflösung pro Farbkanal berechnet sich der Speicherbedarf wie folgt:

- **Anzahl der Pixel**: 640 * 480 = 307,200 Pixel
- **Bits pro Pixel**: 8 Bit * 3 Farbkanäle = 24 Bit
- **Gesamtanzahl der Bits**: 307,200 * 24 = 7,372,800 Bit
- **In Bytes**: 7,372,800 Bit / 8 = 921,600 Byte

Der Speicherbedarf beträgt somit 7,372,800 Bit bzw. 921,600 Byte.

### Bildformate für Webseiten-Hintergründe
Für eine Webseite mit einer gekachelten Textur als Hintergrundbild würde ich folgende Bildformate empfehlen:
- **PNG**: Verlustfreie Kompression, ideal für Grafiken und Texturen mit Transparenz.
- **JPEG**: Verlustbehaftete Kompression, gut für fotorealistische Bilder mit vielen Farben.
- **SVG**: Für skalierbare Vektorgrafiken, die bei verschiedenen Bildschirmauflösungen scharf bleiben.

### Pixelauflösung eines 30-Zoll-Displays
Ein 30-Zoll-Display im Format 16:10 und 100ppi hat folgende Auflösung:
- **Diagonale**: 30 Zoll
- **PPI (Pixel per Inch)**: 100
- **Breite und Höhe** berechnet man unter Berücksichtigung des Seitenverhältnisses.

Berechnungen:
1. Diagonale in Pixel: 30 Zoll * 100 ppi = 3000 Pixel
2. Breite und Höhe im Seitenverhältnis 16:10:
   \[
   \text{Breite}^2 + \text{Höhe}^2 = 3000^2
   \]
   \[
   \frac{\text{Breite}}{\text{Höhe}} = \frac{16}{10}
   \]
   
   Aus diesen Gleichungen lassen sich die Breite und Höhe berechnen.

### Druckgröße eines Fotos bei 600dpi
Ein Foto mit einer Kantenlänge von 2000 Pixeln bei 600dpi:
- **Größe in Zoll**: 2000 Pixel / 600 dpi = 3.33 Zoll
- **Größe in cm**: 3.33 Zoll * 2.54 cm/Zoll = 8.46 cm

Das gedruckte Foto wird etwa 8.46 cm groß sein.

### Speicherbedarf für ein HD1080p50 Einzelbild
Für ein HD1080p50-Format bei True-Color-Farbauflösung:
- **Auflösung**: 1920 x 1080
- **Anzahl der Pixel**: 2,073,600
- **Bits pro Pixel**: 24 Bit
- **Speicherbedarf pro Bild**: 2,073,600 * 24 = 49,766,400 Bit = 6,220,800 Byte ≈ 6.22 MB

### Speicherbedarf eines Videos bei 3 Minuten Länge
Ein HD1080p50-Video mit einer Länge von 3 Minuten (180 Sekunden):
- **Bilder pro Sekunde**: 50
- **Anzahl der Bilder**: 180 Sekunden * 50 = 9000
- **Speicherbedarf pro Bild**: 6.22 MB
- **Gesamt**: 9000 * 6.22 MB = 55,980 MB ≈ 54.67 GB

Da HD im IEC-Format berechnet wird (1 GB = 1024^3 Bytes):
- **Speicherbedarf in GB**: 55,980 MB / 1024 ≈ 54.67 GB

### Unterschiede zwischen RAW und JPG
- **RAW**: Unkomprimiert, enthält mehr Bildinformationen, ideal für Nachbearbeitung.
- **JPG**: Komprimiert, kleinerer Dateigröße, verlustbehaftet, geeignet für schnelle Veröffentlichungen.

### Technische Vorgaben für Youtube-Uploads
- **Format**: MP4 (empfohlen)
- **Bildrate**: Bis zu 60 fps
- **Farbauflösung**: 8 Bit
- **Videocodec**: H.264
- **Audiocodec**: AAC
- **Maximale Dateigröße**: 256 GB

### Unterschied zwischen Interlaced und Progressive Mode
- **Interlaced Mode**: Zeilenweise abwechselnde Darstellung (z.B. 1080i).
- **Progressive Mode**: Vollbilddarstellung (z.B. 1080p).

### Artefakte
- **Kompressionsartefakte**: Blockbildung, Farbverläufe.
- **Motion Artefakte**: Bewegungsunschärfe, Geisterbilder.

### Datenrate für HD1080i50
Für ein unkomprimiertes HD1080i50-Video:
- **Auflösung**: 1920 x 1080
- **Bildrate**: 50 Halbbilder pro Sekunde
- **Bits pro Pixel**: 24 Bit
- **Datenrate in Gbps**: 
   \[
   1920 \times 1080 \times 50 \times 24 = 2,488,320,000 \text{ Bit/s} \approx 2.49 \text{ Gbps}
   \]

### Speicherkapazität einer DVD-5 für HD1080i50 Video
Eine DVD-5 hat 4.7 GB:
- **Speicherbedarf pro Sekunde**: 2.49 Gbps
- **Speicherkapazität in Sekunden**: 
   \[
   4.7 \times 1024 \times 1024 \times 8 \text{ Bits} / 2.49 \times 10^9 \text{ Bits/s} = 1,507.65 \text{ Sekunden} \approx 25.13 \text{ Minuten}
   \]

### Unterschied zwischen Codec und Mediencontainer
- **Codec**: Kodiert und dekodiert Daten (z.B. H.264).
- **Mediencontainer**: Verpackt verschiedene Datenströme (z.B. MP4).

### A/D-Wandlung
- **Notwendigkeit**: Um analoge Signale in digitale Form umzuwandeln.
- **Datenverlust**: Da die analogen Signale kontinuierlich sind, während digitale Signale diskretisiert werden.
- **Samplingrate**: Höhere Samplingrate führt zu präziserer Abbildung.
