# Bilder 
***
## RGB Bilder und ihre Auflösung 
Ein RGB-Farbraum ist ein additiver Farbraum, der Farbwahrnehmungen durch das additive Mischen 
der drei Grundfarben (Rot, Grün und Blau) nachbildet. Alle Mischfarben entstehen also aus den Mischungen dieser Grundpalette. 
Dieses Prinzip dient als Grundlage zur Darstellung von Farbbildern mittels Bildwiedergabegeräten wie Handydisplay, Computerbildschirm oder Tablet und wird in seiner Qualität zusätzlich durch die dpi (dots per inch) der Auflösung bestimmt.
Die Anzahl dieser hat über die Jahre rasant zugenommen, wie man im Verleich alter Bildschirmansichten im Vergleich mit hochauflösenden Screens der letzten Zeit sehen kann. 
(Bild Windows alt)                      (Bild apple neu)
Bildunterschrift: 1993, Windows NT 3.1   Bildunterschrift: Apple Startbildschirm 2016

### Komprimierung

**Redundanz**


 Wenn das Signal mit mehr Bits als nötig beschriebe wird, ist es sinnvoll dies zu ändern.
 So kann das Signal effizienter beschrieben werden und das Bild sieht am Ende nicht wesentlich anders aus, als das   Originalmotiv.
Dies greift vor allem bei kontrastarmen Bereichen einer Grafik, die so weniger Informationen braucht

**Irrelevanz**


Originalsignal enthält Information, die das menschliche Auge nicht wahrnehmen kann.
Schon die Darstellung von Farbe als RGB-Information ist eine Abstraktion, da die
genaue Farbinformation in Form einer Wellenlänge oder eines eigenen individuellen Tons weggelassen wird.
Kontraste zwischen Farben werden darüber hinaus geringer ersichtlich, als das bei Differenzen der Helligkeitswerte der Fall ist. Hier fällt dies mehr ins Gewicht.
Dieses selektive Weglassen der am wenigsten wichtigen Informationen nennt man auch *„lossy compression“*

*Beispiel gif*

Erstellt zu jedem Bild eine Farbpalette mit vorherrschenden Tönen (256) auf die Rückbezug genommen wird. Somit wird jeder Pixel mit einem Byte darstellbar und die Bildgröße komprimiert. Ein Hintergrund kann transparent sein.
Dieses Format ist geeignet um mehrere Bilder in schneller Abfolge zu reihen sodass kurze Videos entstehen.

(bild pbjt) 


*Beispiel JPEG*

Man teilt das Bild in je 8 mal 8 Pixel große Blöcke ein, die unabhängig voneinander verarbeitet werden. Mit dem mathematischen Verfahren der Diskreten Cosinus-Transformation (DCT) ermittelt man aus den Helligkeitsschwankungen innerhalb eines Blocks die darin enthaltenen Frequenzen.Das Ergebnis sind 64 Koeffizienten, die zwar etwas ungenauer sind da sie durch ortsspezifische Anpassung entstanden sind, jedoch annähernd dieselbe Information wie die ursprünglichen 64 Pixel enthalten.

*Interpolation*

Wörtliche Übersetzung: „Zwischenrechnen“, bezeichnet in der digitalen Fotografie ein Verfahren zur Erzeugung von Bildinhalten zwischen verschiedenen Pixeln eines Bildes (Dichteinterpolation)
und innerhalb einzelner Pixel (Farbinterpolation).
Die Interpolation ist ein notwendiger Bestandteil des Signalverarbeitungsweges digitaler Bilder, da alle Änderungen an der Pixelmenge und der Farbe nur hiermit realisiert werden können. Im gesamten Verarbeitungsweg zwischen Bilderzeugung und -darstellung wird mehrfach interpoliert – dabei entsteht immer ein Schärfeverlust.








