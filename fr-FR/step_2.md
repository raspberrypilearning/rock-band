## Fabrication d'un tambour

Tout d'abord, créons un tambour qui produit un son lorsqu'il est frappé.

+ Commencez un nouveau projet de Scratch et supprimez le lutin du chat pour que votre projet soit vide. Vous pouvez trouver l'éditeur de scratch en ligne à <a href="http://jumpto.cc/scratch-new">jumpto.cc/scratch-new</a>.

+ Ajoutez un lutin de tambour à votre projet et vous pouvez aussi ajoutez une image de fond appropriée à l'étape.

	![screenshot](images/band-stage.png)

	Si vous n'êtes pas sûr de comment faire cela, le projet ' Lost in space ' vous aidera!

+ Programmons le tambour pour qu'il joue un son lorsqu'il est cliqué. Assurez-vous que le lutin de tambour soit sélectionné et ajoutez ce code :

	```blocks
		quand ce lutin est cliqué
		jouer du tambour (1 v) pendant (0.25) temps
	```

+ Cliquez sur le tambour pour essayer votre nouvel instrument!

+ Vous pouvez aussi changer l'aspect du tambour lorsqu'il est cliqué en créant un nouveau costume. Cliquez sur l'onglet 'Costumes' et vous verrez l'image du tambour.

	![screenshot](images/band-drum-costume.png)

+ Faites un clic droit sur le costume et cliquez sur 'dupliquer' afin de créer une copie du costume.

	![screenshot](images/band-drum-duplicate.png)

+ Cliquez sur le nouveau costume (appelé 'drum2') et sélectionnez l'outil de ligne. Ensuite, vous devez tracer des lignes pour donner l'impression que le tambour joue un son.

	![screenshot](images/band-drum-hit.png)

+ Les noms des costumes ne sont pas très utiles à l'heure actuelle. Renommez les 2 costumes 'not hit' et 'hit' en écrivant le nouveau nom de chaque costume dans la boîte de texte.

	![screenshot](images/band-drum-name.png)

+ Maintenant que vous avez 2 costumes différents pour votre tambour, vous pouvez choisir quel costume est affiché! Ajoutez ce code à votre tambour :

	```blocks
		quand le drapeau vert pressé
		basculer sur le costume [not hit v]

		quand ce lutin est cliqué
		basculer sur costume [hit v]
		jouer du tambour (1 v) pendant (0.25) temps
		basculer sur costume [not hit v]

	```

	Le bloc de code pour changer le costume est dans la section `Apparences`{:class="blocklooks"}.

+ Testez votre tambour. Lorsque le tambour est cliqué, il devrait maintenant changer de costume afin de montrer qu'il a été frappé.
