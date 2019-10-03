## Trajes

Agora vais fazer com que pareça que o teu cantor está a cantar!

\--- task \--- Podes alterar a aparência do seu ator de cantor quando é clicado, criando um novo traje. Clica na aba Trajes e vais ver o traje do cantor.

![screenshot](images/band-singer-costume-annotated.png) \--- /task \---

\--- task \--- Clica com o botão direito do rato no traje e clica em ** duplicar ** para criar uma cópia.

![screenshot](images/band-singer-duplicate.png) \--- /task \---

\--- task \--- Click on the new costume (called 'Singer2'), and then select the line tool and draw lines so it looks like your singer is making a sound.

![screenshot](images/band-singer-click.png) \--- /task \---

\--- task \--- The names of the costumes aren't very helpful at the moment. Type into the text boxes of the costumes to change their names to 'not singing' and 'singing'.

![screenshot](images/band-singer-name-annotated.png) \--- /task \---

\--- task \--- Now that you have two different costumes for your singer, you can choose which costume is displayed! Add these two code blocks to your singer sprite:

```blocks3
when this sprite clicked
+switch costume to (singing v)
play sound (singer1 v) until done
+switch costume to (not singing v)
```

The code block for changing the costume is in the `Looks`{:class="block3looks"} section. \--- /task \---

\--- task \--- Click on your singer on the stage. Does she look like she is singing? \--- /task \---

\--- task \--- Now make your drum look like it's being hit!

![screenshot](images/band-drum-final.png)

- Use the instructions for changing your singer sprite's costume to help you.

Remember to test that your new code works! \--- /task \---