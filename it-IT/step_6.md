## Creare un cantante

Aggiungiamo un cantante alla tua band!

+ Aggiungi altri due sprite nello stage: un cantante ed un microfono.

	![screenshot](images/band-singer-mic.png)

+ Prima che la tua cantante possa cantare, dovrai aggiungere un suono allo sprite. Assicurati di aver selezionato lo sprite della cantante, scegli il pannello 'Suoni' e fai click col mouse su 'Scegli un suono dalla libreria':

	![screenshot](images/band-import-sound.png)

+ Scegliendo 'Canti' dalla lista a sinistra potrai scegliere un suono adatto da aggiungere allo sprite.

	![screenshot](images/band-choose-sound.png)

+ Dopo aver caricato il suono, aggiungi questo codice alla tua cantante:

	```blocks
		quando si clicca questo sprite
		produci suono [singer1 v] e attendi la fine
	```

+ Clicca sulla cantante per assicurarti che canti quando viene premuta.
