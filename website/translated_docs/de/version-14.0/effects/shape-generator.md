---
id: version-14.0-shape-generator
title: Shape Generator
sidebar_label: Shape Generator
original_id: shape-generator
---

[](https://youtu.be/oTo6FxHD02o?t=20 "Using Shape Generator")

Ein Shape ist eine automatische Folge von Werten, die verschiedene
Attribute eines Gerätes modulieren kann. Ein Kreis-Shape (circle) etwa,
angewendet auf Pan und Tilt, sorgt für eine Kreisbewegung des Gerätes.
Dabei lässt sich das Zentrum des Kreises, die Größe sowie die
Geschwindigkeit der Bewegung beeinflussen.

Shapes sind besonders eindrucksvoll, wenn die auf mehrere Geräte
angewandt werden. Dabei kann ein Shape auf mehreren Geräte gleichzeitig
oder aber mit einem Versatz laufen, womit man rasch z.B. Welleneffekte
erstellen kann.

Außer Positions-Shapes gibt es eine große Anzahl weiterer Shapes. Diese
sind jeweils pro Attribut definiert, etwa für Farbe, Dimmer, Fokus usw.

Außerdem gibt es die Funktion **Mask FX**, mittels derer sich laufende
Shapes stoppen lassen. Läuft etwa auf einigen Geräten ein Kreis-Shape,
und wird dann ein Cue aufgerufen, in dem auf ein paar der Geräte ein
'Position Mask-Shape' abgespeichert ist, so beenden diese Geräte ihre
Kreisbewegung. Das ist hilfreich etwa beim Verändern von Cues während
des Showablaufs. Details dazu siehe [Mask FX](shape-generator.md#masking-shapes-using-mask-fx).

![Capture Visualiser with a shape running across fixtures](/docs/images/Capture-Visualiser-with-a-shape-running-across-fixtures.png)

Einen Shape erstellen
---------------------

Wird ein Shape ausgewählt, so wird dieser auf die zuvor angewählten
Geräte angewendet.

1. [Wählen Sie die Geräte](../controlling-fixtures/using-the-select-buttons-and-wheels.md#dimmer-und-geräte-zum-steuern-auswählen), auf die der Shape angewendet werden soll.

2. Im Hauptmenü drücken Sie \[Shape and Effects\], dann \[Shape
Generator\].

3. Klicken Sie \[Create\], um einen neuen Shape zu starten.
![Shape Generator selecting a category of new shape](/docs/images/Shape-Generator-selecting-a-category-of-new-shape.png)

4. Betätigen Sie eine \[Menütaste\], um den Shape nach Attribut
auszuwählen, oder drücken Sie \[All Shapes\] für eine Gesamtliste.

5. Klicken Sie im **Shapes-Fenster** auf den gewünschten Shape, oder
benutzen Sie eine \[Menütaste\] zur Auswahl. Ebenso kann man mit
der Tastatur einen Suchbegriff für einen bestimmten Shape eingeben, um
die Suche einzugrenzen.

6. Der Shape wird auf die ausgewählten Geräte angewendet.

---

-   Wird das **Shapes-Fenster** geöffnet, so bleibt es ständig offen, und
    man muss nicht immer wieder \[Shape Generator\] drücken, um einen
    Shape abzurufen. Dieses Fenster zeigt nur Shapes, die auf die
    gewählten Geräte anwendbar sind. Wird ein Attribut ausgewählt, so
    wird die Liste der verfügbaren Shapes weiter verkürzt auf Shapes,
    die für dieses Attribut verfügbar sind. Zur Anzeige aller Shapes
    wählen Sie das Attribut ‚Dimmer' aus.
    \
    ![Shapes Workspace Window](/docs/images/Shapes-Workspace-Window.png)

-   Der Ausgangswert für einen Shape ist die jeweilige momentane
    Einstellung des Gerätes; *so wird z.B. ein Kreis-Shape um die
    momentane Pan/Tilt-Position zentriert*.

-   Zum Ändern des Basiswerts eines Shapes (etwa das Zentrum eines
    Kreises) ändern Sie wie gewohnt die entsprechenden Attribute mit den
    Rädern. Ggf. stellt man dazu die Größe des Shapes auf null (siehe
    [nächster Abschnitt](#ändern-von-größe-und-geschwindigkeit)), um den Basiswert genau einstellen zu können.

-   Zum gleichzeitigen Abruf mehrerer Shapes wiederholen Sie einfach die
    o.g. Prozedur. Ebenso lassen sich auch mehrere Shapes auf das
    gleiche Gerät anwenden, womit weitere interessante Effekte erzielt
    werden können.

-   Zur Anzeige der momentan laufenden Shapes drücken Sie \[Shapes and
    Effects\], dann \[Shape Generator\] und dann \[Edit\].

-   Wird der gleiche Shape auf zwei verschiedene Gruppen von Geräten
    angewendet, so erscheint er doppelt in der Liste. Damit lassen sich
    die beiden Gruppen getrennt voneinander beeinflussen, etwa für
    unterschiedliche Richtungen, Geschwindigkeiten etc. ([s.u.](#ändern-von-größe-und-geschwindigkeit))

-   Hat das ausgewählte Gerät Teilgeräte (Zellen, Subfixtures), so kann
    man wählen, ob der Shape auf dem Hauptgerät laufen soll und alle
    einzelnen Zellen synchron laufen, oder ob die Zellen einzeln
    angesteuert werden. Es gibt folgende Optionen:
    -   \[Run on Super Fixtures\] - Zellen werden ignoriert, die Geräte werden im
    Ganzen angesteuert
    -   \[Run on Sub Fixtures (Linear)\] - die Zellen werden gemäß ihrer internen
    Nummerierung angesteuert
    -   \[Run on Sub Fixtures (Group)\] - die Zellen werden gemäß ihrer Anordnung
    (Layout-Editor für die jeweilige Gruppe) angesteuert.

-   Jeder Shape ist für ein spezifisches Attribut konzipiert. Verfügt
    ein Gerät nicht über dieses Attribut, so führt auch der Shape zu
    keinem sichtbaren Effekt.

-   Jeder Shape hat eine Standardgröße und -geschwindigkeit *(wird in
    der Shape-Datei definiert)*.

> Wird ein 'Rainbow'-Farbshape verwendet, so müssen die Farb-Grundwerte (CMY oder RGB) auf **50%** gestellt werden, um sämtliche Farbkombinationen zu erzielen..

Ändern von Größe und Geschwindigkeit
------------------------------------

Nachdem ein Shape gestartet ist, lassen sich schnell und einfach Größe
und Geschwindigkeit ändern. Wenn im Display oberhalb der Encoder 'Spread'
und 'Offset' steht, so drücken Sie Taste E \[Adjust Speed, Size and
Spread\].

![Shape Wheel Attribute Controls for Speed, Size & Spread](/docs/images/Shape-Wheel-Attribute-Controls-for-Speed-Size-Spread.png)

-   Der linke Encoder steuert die Geschwindigkeit des Shapes.

-   Der mittlere Encoder steuert die Größe des Shapes. *(Pearl Expert: rechter Encoder)*

-   Größe und Geschwindigkeit werden im Display angezeigt.

---

Weitere Dinge über Größe und Geschwindigkeit:

-   Laufen mehrere Shapes, so sind die Encoder dem zuletzt geladenen
    zugeordnet. Die Parameter jedes einzelnen laufenden Shapes lassen
    sich mit der 'Edit Shape'-Funktion einstellen, siehe
    [Ändern von Shapes mit Include](editing-shapes-and-effects.md#ändern-von-shapes-mit-include).

-   Die Minimalgröße ist Null. Dies lässt den Shape *"verschwinden"*, und
    das Gerät kehrt zu den vorherigen Einstellungen zurück. Dennoch ist
    der Shape noch aktiv.

-   Sobald ein Shape in einem Cue gespeichert ist, können Größe und/oder
    Geschwindigkeit entweder mit dem Fader des Cues gesteuert werden,
    oder man legt entsprechende [Masterfader](../running-the-show/playback-controls.md#speed--und-size-master) an und verwendet diese (Rate-Master, BPM-Master, Size-Master).

Ändern der Verteilung eines Shapes (mehrere Geräte)
---------------------------------------------------

Shapes wirken interessanter (und eindrucksvoller), wenn sie auf mehrere
Geräte angewendet werden. Titan erlaubt es, den Spread (Verteilung)
eines Shapes zwischen mehreren Geräten einzustellen. Ebenso lässt sich
die Phasenlage (Versatz) einstellen: ein anderer Ansatz für die gleiche
Eigenschaft.

Die Reihenfolge, in der der Shape auf den ausgewählten Geräten abläuft,
hängt von der Reihenfolge ab, in der die Geräte beim Abruf des Shapes
ausgewählt wurden. Mittels \[Fixture Order\] lässt sich die
Geräte-Reihenfolge innerhalb des Shape-Menüs ändern.

1. Wenn der rechte Encoder nicht gerade den Spread steuert, drücken Sie
auf \[Adjust Speed, Size and Spread\]

2. Steuern Sie den **Spread** (die Verteilung) mit dem rechten Encoder, 
oder betätigen Sie \[Adjust Spread, Phase and Offset\] und benutzen das 
mittlere Rad, um den Geräteversatz (Phase) einzustellen *(rechtes Rad 
beim Pearl Expert)*.

Spread = **12** *(Phase = 30 degrees)*:

![Capture Visualiser with a shape running across fixtures with spread of 12](/docs/images/Capture-Visualiser-with-a-shape-running-across-fixtures-with-spread-of-12.png)

---

Spread = **6** *(Phase = 60 degrees)*:

![Capture Visualiser with a shape running across fixtures with spread of 6](/docs/images/Capture-Visualiser-with-a-shape-running-across-fixtures-with-spread-of-6.png)

---

Spread = **2** *(Phase = 180 degrees)*:

![Capture Visualiser with a shape running across fixtures with spread of 2](/docs/images/Capture-Visualiser-with-a-shape-running-across-fixtures-with-spread-of-2.png)

Im Display wird die **Phase** in ° (Grad) angezeigt. So sorgt etwa
Phase=180° für eine Wiederholung jedes zweiten Gerätes, 90° jedes
vierten Gerätes, 60° jedes sechsten Gerätes usw.

**Offset** ist der Startwert des Shapes im Vergleich zu anderen gleichzeitig
laufenden Shapes. *Wenn beispielsweise gleichzeitig ein Shape auf Cyan
und einer auf Magenta läuft, um einen Farbmix zu erzielen, so möchte man
vielleicht mit Cyan auf 100% und Magenta auf 0 beginnen, um den gesamten
Farbbereich abzudecken. Dazu stellt man einen der beiden Shapes auf
einen ‚Phase Offset' von 180°.* Ohne diese Einstellung würden beide
Shapes gleichzeitig 0 bzw. 100% erreichen.

>   Nach dem Ändern von Offset oder Phase empfiehlt es sich, den Shape 
	**neu zu starten**, damit alle Shapes neu synchronisiert werden. Dazu gibt 
	es im Menü 'Edit Shape' die Menütaste \[Restart Shapes\].

Shape-Richtung
--------------

Die Menüfunktion \[Direction\] erlaubt es, die Richtung des Shapes
zu ändern; hat man ein [2D-Layout](../controlling-fixtures/fixture-groups.md#gerätereihenfolge-und--anordnung-in-den-gruppen) erstellt, so kann man abhängig vom
Shape eine gezielte Bewegung erreichen.

Mit der Taste \<Menu Latch\> lässt sich das "Shape Direction"-Menü
einrasten, so dass man schnell die verschiedenen Einstellungen
durchprobieren kann.

Beat und Cycles (Durchläufe)
----------------------------

Die Option \[Adjust Beat and Cycles\] steuert, wie das generelle Tempo
des Programmers das Tempo des Shapes beeinflusst und wie oft dieser
läuft.

### Beats

Vorgabewert ist \[Beats=1\]: jeder Beat entspricht einem kompletten
Durchlauf des Shapes, wie in früheren Software-Versionen. Höhere Werte
dagegen sorgen dafür, dass das Tempo des Shapes entsprechend reduziert
wird. Mit z.B. \[Beats=4\] lässt sich erreichen dass für einen
kompletten Shape-Durchlauf 4 Beats erforderlich sind -- der Shape läuft
langsamer.

Klickt man auf den Wert des **linken Encoders** im Display oder betätigt die jeweilige
@-Taste, so kann man die gewünschte Zahl direkt eingeben; außerdem
werden zwei weitere Optionen angeboten: mit \[Match to Spread\] (an den
Spread anpassen) wird der Beat Count auf den Spread-Wert des Shapes
gesetzt, was vor allem bei Dimmer-Shapes sinnvoll ist. Klickt man
dagegen auf \[Custom\], so kann man einen numerischen Wert eingeben.

### Cycles

Mit Cycles (Durchläufe) stellt man ein, wie oft der Shape laufen soll.
Vorgabewert ist Unendlich (∞), womit der Shape läuft, bis er wieder
gestoppt wird. Ändert man dies auf eine andere Zahl, so läuft der Shape
nur die vorgegebene Anzahl von Zyklen und hält dann an.

Zum direkten Eingeben eines Zahlenwertes drücken Sie die entsprechende
@-Taste oder klicken auf den Wert des **mittleren Encoder** im Bildschirm. 
Eine Eingabe von Dezimalzahlen (z.B. 1.5) sorgt dafür, dass der letzte 
Durchlauf nur zum Teil durchgeführt wird und dann stehenbleibt.

Verwenden von Shapes in Cues
----------------------------

Wird ein Shape in einen Cue (auf ein Playback) gespeichert, so lässt
sich mit den [Options](../cues/playback-options.md) des Playbacks einstellen,  
dass der Fader z.B. die Größe und/oder Geschwindigkeit
des Shapes steuert; ebenso lassen sich [Master (Size, Speed, BPM)](../running-the-show/playback-controls.md#speed--und-size-master) für die
Steuerung verwenden. 

Shapes lassen sich auch in Cuelisten verwenden - in [Tracking von Shapes in Cuelisten](../cue-lists/creating-a-cue-list.md#tracking-von-shapes-in-cuelisten) ist beschrieben, wie sich die Shapes in diesem Fall verhalten.

Zum Editieren aktuell laufender Shapes siehe [Ändern eines gerade laufenden Shapes](../effects/editing-shapes-and-effects#ändern-eines-gerade-laufenden-shapes).

Shapes stoppen mit Mask FX
--------------------------

Mit der Funktion **Mask FX** können Playbacks programmiert werden, die
laufende Shapes und Keyframe-Shapes auf einzelnen oder allen Geräten
stoppen.

Um einen Mask Effekt zu erzeugen, gehen Sie wie folgt vor:

1.  Drücken Sie \[Shapes und Effekte\], dann \[Mask Fx\].

2.  Die Attributbank-Buttons flashen (P, C etc.). Wählen Sie die
    Attribute, für die Shapes maskiert werden sollen.

3.  Sind keine Geräte angewählt, so wirkt sich dies auf alle Geräte aus.
    Sind dagegen Geräte gewählt, so werden nur diese beeinflusst.

4.  Wählen Sie \[Create Mask Shape\]. (Mit \[Create Mask FX\] lassen
    sich sowohl Shapes als auch Pixelmaps stoppen).

5.  Wird dies in ein Playback gespeichert, so kann man mit diesem
    laufende Effekte stoppen.

-   Mit \[Clear Mask from Programmer\] werden Mask FX-Effekte wieder
	gelöscht.

-   Diese Funktion ersetzt die früheren Block Shapes und Block Effekte.
	Werden ältere Shows mit solchen Effekten geladen, so werden diese jetzt
	als Mask Fx angezeigt.

Diese Funktion erfordert eine aktuelle Personality Library.

Speichern von Shapes in Paletten
--------------------------------

Es lassen sich auch Paletten mit Shapes erstellen. Das ist z.B. sehr
hilfreich mit verschiedenen Spread- oder Size-Einstellungen. Siehe
[Effekt-Paletten](../palettes/creating-palettes.md#erstellen-einer-effekt-palette).
