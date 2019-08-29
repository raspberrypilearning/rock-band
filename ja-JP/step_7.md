## コスチューム

歌手が歌っているように見せましょう！

\--- task \--- 新しいコスチュームを作成することで、クリックしたときに歌手のスプライト見え方を変えることができます。コスチュームタブをクリックすると、歌手のコスチュームが表示されます。

![スクリーンショット](images/band-singer-costume-annotated.png) \--- /task \---

\--- task \--- コスチュームを右クリックし、**複製**をクリックするとコピーを作成します。

![スクリーンショット](images/band-singer-duplicate.png) \--- /task \---

\--- task \--- 新しいコスチューム(「Singer2」という名前です) をクリックし、ラインツールを選択して、ラインを引きます、すると歌手が音を出しているように見えます。

![スクリーンショット](images/band-singer-click.png) \--- /task \---

\--- task \--- コスチュームの名前は今のところあまり役に立ちません。コスチュームのテキストボックスに入力して、名前を「歌わない」と「歌う」に変更します。

![スクリーンショット](images/band-singer-name-annotated.png) \--- /task \---

\--- task \--- 歌手のコスチュームが2種類になったので、表示する衣装を選択できます！これら2つのコードブロックを歌手のスプライトに追加します。

```blocks3
when this sprite clicked
+switch costume to (singing v)
play sound (singer1 v) until done
+switch costume to (not singing v)
```

The code block for changing the costume is in the `Looks`{:class="block3looks"} section. \--- /task \---

\--- task \--- Click on your singer on the stage. Does she look like she is singing? \--- /task \---

\--- task \--- Now make your drum look like it's being hit!

![スクリーンショット](images/band-drum-final.png)

- Use the instructions for changing your singer sprite's costume to help you.

Remember to test that your new code works! \--- /task \---