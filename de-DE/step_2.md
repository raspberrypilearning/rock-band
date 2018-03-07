## Eine Trommel programmieren

Lass uns zuerst eine Trommel entwickeln, die einen Klang von sich gibt, wenn du drauf schlägst.

+ Öffne ein neues Scratch-Projekt und lösche die Figur mit der Katze, so dass dein Projekt leer ist.

+ Füge eine Trommel-Figur zu deinem leeren Projekt hinzu und suche ein Hintergrundbild für die Bühne, das zum Thema passt.

	![screenshot](images/band-stage.png)

	Wenn du dir nicht sicher bist, wie das gemacht wird, dann schau dir das vorherige Projekt ("Verloren im Weltall") an!

+ Lass uns die Trommel so programmieren, dass sie einen Klang abspielt, wenn man drauf klickt. Stelle sicher, dass die Trommel ausgewählt ist, und füge diesen Code hinzu:

```blocks
	Wenn ich angeklickt werde
	spiele Schlaginstrument (1 v) für (0.25) Schläge
```

+ Klicke auf die Trommel, um dein neues Instrument zu testen!

+ Du kannst auch ändern, wie die Trommel aussieht wenn man drauf klickt. Dazu braucht die Trommel ein zweites Kostüm. Klick zuerst auf 'Kostüme', um das aktuelle Bild der Trommel zu sehen.

	![screenshot](images/band-drum-costume.png)

+ Klicke mit der rechten Maustaste auf das Kostüm und dann auf 'Duplizieren', um eine Kopie des Kostüms zu erstellen.

	![screenshot](images/band-drum-duplicate.png)

+ Klicke auf das neue Kostüm ('drum2'), wähle das Linien-Werkzeug aus, und zeichne dann ein paar Linien, damit es so aussieht als ob die Trommel einen Klang von sich gäbe.

	![screenshot](images/band-drum-hit.png)

+ Die Namen der Kostüme sind derzeit nicht besonders hilfreich. Benenne die 2 Kostüme um in 'nicht geschlagen' und 'geschlagen' indem du die Namen in das Textfeld des jeweiligen Kostüms eingibst.

	![screenshot](images/band-drum-name.png)

+ Weil es jetzt 2 unterschiedliche Kostüme für die Trommel gibt, kannst du nun auswählen welches Kostüm angezeigt wird! Füge diesen Code zu deiner Trommel hinzu:

```blocks
	Wenn die grüne Flagge angeklickt
	wechsle zu Kostüm [nicht geschlagen v]

	Wenn ich angeklickt werde
	wechsle zu Kostüm [geschlagen v]
	spiele Schlaginstrument (1 v) für (0.25) Schläge
	wechsle zu Kostüm [nicht geschlagen v]
```

	Den Code-Block zum Wechseln des Kostüms findest du im Bereich `Aussehen` {:class="blocklooks"}.

+ Wenn die Trommel angeklickt wird sollte sie jetzt das Kostüm wechseln, damit man sieht dass sie einen Ton von sich gibt, und dann wieder zurückwechseln.
