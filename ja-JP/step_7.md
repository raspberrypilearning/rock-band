## コスチューム

歌手が歌っているように見せましょう！

--- task ---

新しいコスチュームを作成することで、クリックしたときに歌手のスプライト見え方を変えることができます。コスチュームタブをクリックすると、歌手のコスチュームが表示されます。

![スクリーンショット](images/band-singer-costume-annotated.png)

--- /task ---

--- task ---

コスチュームを右クリックし、**複製**をクリックするとコピーを作成します。

![スクリーンショット](images/band-singer-duplicate.png)

--- /task ---

--- task ---

新しいコスチューム（『Singer2』という名前です）をクリックして、直線ツールを使い、歌手が歌っているように線を引きましょう。

![スクリーンショット](images/band-singer-click.png)

--- /task ---

--- task ---

コスチュームの名前は今のところあまり役に立ちません。コスチュームのテキストボックスに入力して、名前を「歌わない」と「歌う」に変更します。

![スクリーンショット](images/band-singer-name-annotated.png)

--- /task ---

--- task ---

歌手のコスチュームが2種類になったので、表示する衣装を選択できます！これら2つのコードブロックを歌手のスプライトに追加します。

```blocks3
when this sprite clicked
+switch costume to (歌う v)
play sound (singer1 v) until done
+switch costume to (歌わない v)
```

コスチュームを変えるブロックは、`見た目`{:class="blocklooks"}のところにあります。

--- /task ---

--- task ---

自分の歌手をクリックしてみてください。歌っているように見えますか？

--- /task ---

--- task ---

ドラムが叩かれているように見せてください！

![スクリーンショット](images/band-drum-final.png)

- 歌手のスプライトのコスチュームを変更する手順に従ってください。

新しいコードが動くかどうか、テストするのを忘れないようにしましょう！

--- /task ---