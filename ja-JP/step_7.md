## コスチューム

歌手が歌っているように見せましょう！

\--- task \---

You can change how your singer sprite looks when it's clicked by creating a new costume. Click on the Costumes tab, and you'll see the singer costume.

![スクリーンショット](images/band-singer-costume-annotated.png)

\--- /task \---

\--- task \---

Right-click on the costume and then click on **duplicate** to create a copy of it.

![スクリーンショット](images/band-singer-duplicate.png)

\--- /task \---

\--- task \---

Click on the new costume (called 'Singer2'), and then select the line tool and draw lines so it looks like your singer is making a sound.

![スクリーンショット](images/band-singer-click.png)

\--- /task \---

\--- task \---

The names of the costumes aren't very helpful at the moment. Type into the text boxes of the costumes to change their names to 'not singing' and 'singing'.

![スクリーンショット](images/band-singer-name-annotated.png)

\--- /task \---

\--- task \---

Now that you have two different costumes for your singer, you can choose which costume is displayed! Add these two code blocks to your singer sprite:

```blocks3
このスプライトが押されたとき
+コスチュームを(歌うv) にする
終わるまで(singer1 v) の音を再生する
+コスチュームを(歌わないv) にする
```

The code block for changing the costume is in the `Looks`{:class="block3looks"} section.

\--- /task \---

\--- task \---

Click on your singer on the stage. Does she look like she is singing?

\--- /task \---

\--- task \---

Now make your drum look like it's being hit!

![スクリーンショット](images/band-drum-final.png)

- 歌手のスプライトのコスチュームを変更する手順に従ってください。

Remember to test that your new code works!

\--- /task \---