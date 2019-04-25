## Disfraces

¡Ahora harás que tu cantante se vea como si estuviera cantando!

\--- task \--- Puedes cambiar el aspecto de tu sprite de cantante cuando se hace clic creando un nuevo disfraz. Haz clic en la pestaña de Disfraces, y verás el disfraz de cantante.

![captura de pantalla](images/band-singer-costume-annotated.png) \--- /task \---

\--- task \--- Haz clic derecho en el disfraz y luego clica en **duplicate** duplicar para crear una copia del disfraz.

![captura de pantalla](images/band-singer-duplicate.png) \--- /task \---

\--- task \--- Haz clic en el nuevo disfraz (llamado 'Cantante2'), luego selecciona la herramienta línea y dibuja líneas para que parezca que tu cantante esté cantando.

![captura de pantalla](images/band-singer-click.png) \--- /task \---

\--- task \--- Los nombres de los disfraces no son muy útiles en este momento. Escriba en los cuadros de texto de los trajes para cambiar sus nombres a "no cantar" y "cantar".

![captura de pantalla](images/band-singer-name-annotated.png) \--- /task \---

\--- task \--- Ahora que tienes dos disfraces diferentes para tu cantante, ¡puedes escoger cual de ellos se visualiza! Agrega estos dos bloques a tu cantante:

```blocks3
when this sprite clicked
+switch costume to (singing v)
play sound (singer1 v) until done
+switch costume to (not singing v)
```

El bloque de código para cambiar de disfraz se encuentra en la pestaña Apariencia `Looks` {:class="blocklooks"}

\--- task\--- Haz clic en tu cantante en el escenario. ¿Se ve como si estuviera cantando? \--- /task\---

\--- task\--- Ahora haz que tu tambor se vea como si estuviera siendo golpeado!

![captura de pantalla](images/band-drum-final.png)

- Usa las instrucciones para cambiar el traje de tu objeto del cantante para ayudarte.

¡Recuerda probar que tu nuevo código funciona! \--- /task\---