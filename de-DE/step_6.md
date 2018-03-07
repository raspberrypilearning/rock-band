## Hintergrundmusik

Du kannst Hintergrundmusik hinzufügen, die deine Band begleitet!

+ Klicke auf die Bühne, dann auf 'Klänge' und dann auf 'Klang aus der Bibliothek wählen', um Musik zu deiner Bühne hinzuzufügen. Die Musik findest du im Bereich 'Musikschleifen'.

+ Füge diesen Code zu deiner Bühne hinzu und denk daran, die Musik auszuwählen, die du ausgesucht hast:

	```blocks
		Wenn die grüne Flagge angeklickt
		wiederhole fortlaufend
		spiele Klang [eggs v] ganz
		Ende
	```

+ Dieser Code spielt die Musik, die du ausgewählt hast, in einer Schleife. Klick auf die Flagge, und probier es aus!

+ Du kannst sogar diesen Code zu deiner Bühne hinzufügen, damit du die Hintergrundmusik stumm schalten oder wieder laut schalten kannst, indem du die Tasten 'm' und 'u' benutzt:

	```blocks
		Wenn die grüne Flagge angeklickt
		setze Lautstärke auf (100)%
		wiederhole fortlaufend
		spiele Klang [eggs v] ganz
		Ende

		Wenn Taste [m v] gedrückt
		setze Lautstärke auf (0)%

		Wenn Taste [u v] gedrückt
		setze Lautstärke auf (100)%
	```
