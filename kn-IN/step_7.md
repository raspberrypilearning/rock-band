## ವೇಷಭೂಷಣಗಳು

ಈಗ ನೀವು ನಿಮ್ಮ ಗಾಯಕನನ್ನು ಹಾಡುತ್ತಿರುವಂತೆ ಕಾಣುವಂತೆ ಮಾಡುತ್ತೀರಿ!

\--- ಕಾರ್ಯ \---

ನಿಮ್ಮ ಗಾಯಕ ಸ್ಪ್ರೈಟ್ ಕ್ಲಿಕ್ ಮಾಡಿದಾಗ ಅದು ಹೇಗೆ ಕಾಣುತ್ತದೆ ಎಂಬುದನ್ನು ನೀವು ಹೊಸ ವೇಷಭೂಷಣವನ್ನು ರಚಿಸುವ ಮೂಲಕ ಬದಲಾಯಿಸಬಹುದು. Costumes (ಕಾಸ್ಟ್ಯೂಮ್ಸ್ ಅಥವಾ ವೇಷಭೂಷಣ) ಟ್ಯಾಬ್ ಕ್ಲಿಕ್ ಮಾಡಿ, ಮತ್ತು ನೀವು ಗಾಯಕ ವೇಷಭೂಷಣವನ್ನು ನೋಡುತ್ತೀರಿ.

![screenshot](images/band-singer-costume-annotated.png)

\--- /ಕಾರ್ಯ \---

\--- ಕಾರ್ಯ \---

ಉಡುಪಿನ ಮೇಲೆ ರೈಟ್ ಕ್ಲಿಕ್ ಮಾಡಿ ಮತ್ತು ನಂತರ **duplicate** ಕ್ಲಿಕ್ ಮಾಡಿ ಅದರ ನಕಲನ್ನು ರಚಿಸಿ.

![screenshot](images/band-singer-duplicate.png)

\--- /ಕಾರ್ಯ \---

\--- ಕಾರ್ಯ \---

Click on the new costume (called 'Singer2'), and then select the line tool and draw lines so it looks like your singer is making a sound.

![screenshot](images/band-singer-click.png)

\--- /task \---

\--- task \---

The names of the costumes aren't very helpful at the moment. Type into the text boxes of the costumes to change their names to 'not singing' and 'singing'.

![screenshot](images/band-singer-name-annotated.png)

\--- /task \---

\--- task \---

Now that you have two different costumes for your singer, you can choose which costume is displayed! Add these two code blocks to your singer sprite:

```blocks3
when this sprite clicked
+switch costume to (singing v)
play sound (singer1 v) until done
+switch costume to (not singing v)
```

The code block for changing the costume is in the `Looks`{:class="block3looks"} section.

\--- /task \---

\--- task \---

Click on your singer on the stage. Does she look like she is singing?

\--- /task \---

\--- task \---

Now make your drum look like it's being hit!

![screenshot](images/band-drum-final.png)

- Use the instructions for changing your singer sprite's costume to help you.

Remember to test that your new code works!

\--- /task \---