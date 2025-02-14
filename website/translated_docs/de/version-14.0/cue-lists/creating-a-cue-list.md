---
id: version-14.0-creating-a-cue-list
title: Creating a Cue List
sidebar_label: Creating a Cue List
original_id: creating-a-cue-list
---

Programmieren einer Cueliste
----------------------------

[](https://youtu.be/Kp6XhdG6keM?t=20 "Cuelist Basics")

Das Programmieren einer Cueliste gleicht dem [Programmieren eines
Chasers](../chases/creating-a-chase.md).

Sie erstellen jeweils das gewünschte Bild und fügen dies als Schritt zu
der Cueliste hinzu. Zeiten lassen sich entweder sofort oder [später
hinzufügen](cue-list-timing.md).

1. Drücken Sie die Taste \<Record\> und wählen die Option \[Create Cue
List\] (auf dem Tiger Touch I drücken Sie \<Record Chase or List\>
zweimal, oder drücken Sie die Taste einmal und wählen die Option
\[Create Cue List\]).

2. Drücken Sie die blaue **Select**-Taste des gewünschten
Speicherplatzes *(auch Cuelisten lassen sich auf die Schaltflächen im
'Playbacks'-Fenster speichern)*.

3. Wählen Sie den gewünschten [Record Mode](#speichermodusrecord-mode) (Speichermodus) des Pultes:
'by Fixture' (pro Gerät), 'by Channel' (nur geänderte Kanäle), 'Record
Stage' oder ‚Quick Build'. \[Record Mode Channel\] ist in der Regel die sicherste
Option, da nur die tatsächlich geänderten Attribute gespeichert werden.
Es empfiehlt sich aber in jedem Falle zu überprüfen, was denn nun genau
abgespeichert wird (ggf. müssen weitere Attribute in den
Programmierspeicher übernommen werden).

4. Stellen sie mit \[Set Times\] die generellen Überblend- und
Verzögerungszeiten sowie die Verknüpfung aufeinanderfolgender Schritte
ein; diese Einstellungen gelten dann für alle neu gespeicherten
Schritte.

5. Stellen Sie das Bild für den ersten Schritt zusammen, entweder
manuell oder unter Verwendung von [\<Include\>](../titan-commands.md#include-----in-den-speicher-laden) bestehender Cues.
Nutzen Sie wenn gewünscht auch den [Shape Generator](../effects/shape-generator.md) oder den [Pixelmapper](../effects/pixel-mapper.md).

6. Wollen Sie für den Schritt eine **Bezeichnung/Legende** vergeben, so drücken Sie
dazu \[Cue Legend\]. Das lässt sich auch später nachholen oder ändern,
entweder mit [\<Unfold\>](editing-cue-lists.md#editieren-einer-cueliste-mit-unfold) oder mit [Set Legend](#vergeben-von-bezeichnern-für-einzelne-schritte) (siehe nächster Abschnitt).

7. Drücken Sie die **Select**-Taste des Speicherplatzes, oder wählen
Sie \[Append Cue\](Schritt anfügen), um den Inhalt des
Programmierspeichers als Schritt 1 der Cueliste abzuspeichern.

8. Wiederholen Sie ab Schritt 5 für den nächsten Schritt der Cueliste.
Drücken Sie nicht \<Clear\>, es sei denn, Sie wollen explizit Pegel aus
vorherigen Schritten übernehmen, da ansonsten Reglerwerte auch von ‚0'
nicht gespeichert werden. Stellen Sie also sicher, dass alle
Geräte/Kanäle, die im aktuellen Schritt verändert werden sollen,
angewählt oder im Programmierspeicher sind (invertierte Anzeige).

9. Drücken Sie \<Exit\>, wenn alle gewünschten Schritte programmiert
sind.

---

-   Um an eine existierende Cueliste [weitere Schritte anzufügen](editing-cue-lists.md),
    wiederholen Sie obiges Vorgehen; bereits vorhandene Schritte werden
    davon nicht beeinflusst. 

-   Zum Anfügen von Schritten an das Ende der Liste wählen Sie \[Append
    Cue\].

-   Um einen bestehenden Schritt zu ändern, drücken Sie \[Cue Number=\]
    und geben die Nummer des Schrittes mit den Zifferntasten ein. Nehmen
    Sie die Änderungen vor und drücken Sie \[Update Cue x\].

-   Zum Einfügen neuer Schritte siehe [Editieren einer Cueliste](editing-cue-lists.md).

-   Das Menü **Advanced Options** gestattet das Neu-Nummerieren der
    Schritte, und das Ändern der einzelnen Schrittnummern.

-   In jeder Cueliste kann eine unbegrenzte Zahl von Schritten
    gespeichert werden.

-   Bei Cuelisten gibt es auch eine **MID (Move-In-Dark)** - Funktion:
    damit werden Geräte bereits für den nächsten Einsatz vorbereitet
    (positioniert etc.), solange sie aktuell nicht aktiv sind. Details
    siehe Abschnitt [Move In Dark (MID)](../cue-lists/cue-list-playback.md#move-in-dark-mid---funktionen)

-   Für jeden Cue lassen sich die [Tracking-Optionen](cue-list-options.md#tracking) getrennt einstellen.

### Speichermodus/Record Mode

Mit \[Record Mode\] (Speichermodus) wählt man zwischen **Record By
Fixture** (‚Speichern pro Gerät', alle Attribute aller veränderten/
ausgewählten Geräte werden gespeichert), **Record By Channel**
('Speichern pro Kanal', nur die geänderten Attribute werden
gespeichert), **Record Stage** ('Bühne speichern', alle Geräte mit
Helligkeit > 0 werden gespeichert), oder **Quick Build** zum raschen
Erstellen aus vorhandenen Cues und Paletten.

> **Record By Channel** bietet sich an, wenn sich mehrere Cuelisten -
für unterschiedliche Attribute - gegenseitig überlagern sollen.


Vergeben von Bezeichnern für einzelne Schritte
----------------------------------------------

Für jeden Schritt lässt sich eine Bezeichnung vergeben, welche beim
Ablauf der Cueliste im Display erscheint - eine hilfreiche Sache bei der
Navigation.

1.  Drücken Sie \[Set Legend\] im Hauptmenü. Wollen Sie mehrere
    Bezeichnungen vergeben, so rasten Sie das Menü mit der Taste \<Menu
    Latch\> ein.

2.  Drücken Sie die **Select-Taste** der entsprechenden Cueliste.

3.  Die Schritte der Cueliste werden nun auf dem Bildschirm angezeigt.
    Klicken Sie auf den gewünschten Cue oder nutzen Sie das Rad A, um den zu
    ändernden Schritt auszuwählen.

4.  Klicken Sie \[Cue Legend\] und geben Sie die Bezeichnung mit der
    Tastatur ein, gefolgt von \<Enter\>.

5.  Setzen Sie den Vorgang ggf. für weitere Schritte fort, oder drücken
    Sie \<Exit\>, um den Vorgang abzuschließen.

Tracking von Shapes in Cuelisten
--------------------------------

Ab Version 10 können auch Shapes innerhalb von Cuelisten tracken. Ist
das Tracking für Shapes aktiviert, läuft ein in einem Cue gestarteter
Shape auch in den folgenden Cues. Zum Aktivieren des Trackings für
Shapes dient die Option \[Shape Tracking\] in den [Optionen](cue-list-options.md#cue-list-options----tab-playback) der
Cueliste.

Cues, die Shapes enthalten, verfügen für jeden Shape über einen extra
Button.

![Cue List window showing tracking shapes](/docs/images/Cue-List-window-showing-tracking-shapes.png)

In den darauffolgenden Cues gibt es für jeden getrackten Shape einen
Schalter:
**T** | **Shape wird in den folgenden Cue getrackt**
---|---
**B** | **Shape wird geblockt, läuft also nicht in den folgenden Cues**

Für den Cue selbst gibt es dazu die Option \[Block All Shapes\], siehe
[Cuelisten-Optionen](cue-list-options.md#cue-list-options----tab-playback).

Darüber hinaus können auch Shapes für einzelne Attribute geblockt
werden, dies erfolgt über das **@**-Menü. Wählen Sie das zu blockende
**Attribut**, drücken die entsprechende **@**-Taste und dann den Attribut-Button
**FX**. Auf den Menütasten gibt es nun die Optionen \[Block Shape\] und
\[Unblock Shape\]. Wurde ein Attribut auf **Block Shape** gesetzt, so wird
das im Display bei den Encodern mit *"Blocked"* angezeigt.

Ist das **[Shape-Tracking](cue-list-options.md#cue-list-options----tab-playback)** dagegen nicht aktiviert, so sind die Shapes in
jedem Cue unabhängig voneinander. Wird der identische Shape - gleiche
Parameter, Größe und Geschwindigkeit - in mehrere aufeinanderfolgende
Cues programmiert, so läuft er einfach durch, ohne unterbrochen zu
werden.

Autoloading: Laden eines externen Cues
--------------------------------------

Schritte einer Cueliste lassen sich auch so programmieren, dass sie
automatisch den Inhalt eines oder mehrerer Speicherplätze -- Cues,
Chaser oder wiederum Cuelisten -- aufrufen, wenn der jeweilige Schritt
gestartet wird. Dies ist hilfreich, um etwa Chaser oder Effekte in die
Cueliste zu integrieren.

Man kann entweder die **Autoloads** manuell programmieren, oder automatisch
alle aktiven Speicherplätze als **Autoload** definieren.

Zum automatischen Definieren gehen Sie wie folgt vor:

1.  Nach dem Aktivieren von **Cue List Record** (beim Anlegen der
    Cueliste) wählen Sie \[Advanced Options\], dann \[Autoload Live
    Playbacks\].

2.  Aktivieren Sie die Cues/Chaser/Cuelisten, die Sie als Autoload
    einbinden möchten.

3.  **Speichern Sie den Cue**. Dabei werden die aktivierten
    Speicherplätze automatisch als Autoload eingebunden.

---

Das manuelle Programmieren der Autoloads erfolgt am einfachsten in der
Playback-Ansicht der Cueliste:

1.  Drücken Sie \<View/Open\>

2.  Drücken Sie die blaue **Select-Taste** der Cueliste.

3.  Im Display erscheinen die Schritte der Cueliste. Klicken Sie auf die
    betreffende **Autoload**-Zelle (Spalte Autoload des betreffenden Cues).
    *Am besten bringen Sie dazu das Fenster in die Vollbild-Ansicht. Ist
    die Spalte Autoload gar nicht sichtbar, klicken Sie links auf \[Show
    All\]*.

4.  Drücken Sie die **Select-Taste** des Speicherplatzes, dessen Inhalt
    mit dem Schritt geladen werden soll. Dabei erscheint die vergebene
    Bezeichnung auf den Funktionstasten.

5.  Sie können nun weitere 'Autoloads' definieren. Verlassen Sie den
    Modus schließlich mit \<Exit\>.

![Cue List Window with Autoload playback](/docs/images/Cue-List-Window-with-Autoload-playback.png)

---

Der Inhalt des mittels 'Autoload'
verknüpften Speicherplatzes wird beim Start des jeweiligen Schrittes
geladen, und beim Start des nächsten Schritts wieder deaktiviert, es sei
denn, auch der nächste Schritt enthält diesen 'Autoload'.

Für jeden 'Autoload' lassen sich verschiedene Optionen vergeben; rufen
Sie diese durch die entsprechende Schaltfläche auf (dort wird jeweils
der verknüpfte Speicherplatz angezeigt).

Für einfache Cues ist die einzige Option A \[Remove this Autoload\]
(diesen Autoload löschen).

Für Chaser und Cuelisten lässt sich mit **Option B** wählen, ob die
jeweilige Abfolge *am Beginn* oder *bei einem bestimmten Schritt* gestartet
werden soll, oder ob für die gewählte Folge *Go* betätigt werden soll.

Klickt man in die Spalte 'Autoload Times' des betreffenden Cues, so kann
man für Fade-In, Fade-Out und Delay des Autoloads getrennte Zeiten
vergeben. Normalerweise werden die Zeiten verwendet, die in der Cueliste
für diesen Cue vergeben wurden. Alternativ kann man mit \[Use Individual
Target Times\] die Zeiten des externen Cues/Chasers/Cueliste verwenden, 
oder man vergibt direkt spezielle Zeiten.


Abrufen einer Tastenfolge (Makro) aus einer Cueliste
----------------------------------------------------

Es lassen sich Cues in Cuelisten programmieren, die eine vorgegebene
Tastenfolge ausführen. Damit lassen sich spezielle Aktionen ausführen,
sobald ein Cue gestartet wird. So lassen sich z.B. mit dem ersten Cue
alle Geräte zünden.

1.  Drücken Sie \[Options\].

2.  Wählen Sie die Cueliste aus.

3.  Drücken Sie \[Macros\]

4.  Im Übersichtsfenster der Cueliste (Playback View) wählen Sie den
    Schritt, dem ein Makro hinzugefügt werden soll.

5.  Drücken Sie die Tasten/Schaltflächen der Makros, die mit diesem
    Schritt ausgeführt werden sollen. Oder drücken Sie \[Add\] und wählen
    ein Macro aus der Liste aus.

6.  Die Spalte 'Macros' zeigt die hinzugefügten Makros.

> Zum Entfernen der Makros aus dem Schritt wählen Sie den Schritt aus,
    wählen dann das zugefügte Makro, und betätigen die Kontext-Taste
    \[Remove Link\].

Tastatursyntax für Cuelisten
----------------------------

Zum schnellen Speichern und Editieren von Cuelisten stehen
folgende Tastenkombinationen zur Verfügung; diese wirken auf die
aktuell mit der Steuerung verbundene (connected) Cueliste; **n**
bezeichnet die Cue-Nummer:

Tasten                                    | Funktion
----------------------------------------- | ------------------------------------------
\<Record\> \<Connect / Cue\> **n** \<Enter\>    | Cue **n** speichern
\<Copy\> \<Connect / Cue\> **n**                | Cue **n** kopieren
\<Delete\> \<Connect / Cue\> **n**              | Cue **n** löschen
\<Include\> \<Connect / Cue\> **n**             | Cue **n** includen (in den Speicher laden)
\<Connect / Cue\> **n** \<Go\>                  | Go Cue **n**
