## ඇදුම්

දැන් ඔබ ඔබේ ගායකයා ඇය ගායනා කරන ආකාරයට පෙනෙනු ඇත!

\--- task \--- නව ඇඳුමක් නිර්මාණය කිරීමෙන් ඔබේ ගායක ස්ප්‍රයිට් (sprite ) ක්ලික් කළ විට එහි පෙනුම වෙනස් කළ හැකිය.Costumes tab ක්ලික් කරන්න, එවිට ඔබට ගායක ඇඳුම (costume)පෙනෙනු ඇත.

![තිර රුව(screenshot)](images/band-singer-costume-annotated.png) \--- /task \---

\--- task \--- ඇඳුම (costume)මත දකුණු-ක්ලික් කර එහි පිටපතක් සෑදීමට **duplicate** මත ක්ලික් කරන්න .

![තිර රුව(screenshot)](images/band-singer-duplicate.png) \--- /task \---

\---- task \--- නව ඇඳුම මත ක්ලික් කරන්න ('සිංගර් 2' (Singer2) ලෙස හැඳින්වේ), පසුව රේඛීය මෙවලම (line tool ) තෝරා රේඛා අඳින්න එවිට ඔබේ ගායකයා ශබ්ද නගන බවක් පෙනේ.

![තිර රුව(screenshot)](images/band-singer-click.png) \--- /task \---

\--- task \--- මේ මොහොතේ ඇඳුමේ නම් එතරම් ප්‍රයෝජනවත් නොවේ. ඇඳුමේ පෙළ කොටු තුළට ටයිප් කර ඔවුන්ගේ නම් 'not singing' සහ 'singing' ලෙස වෙනස් කරන්න.

![තිර රුව(screenshot)](images/band-singer-name-annotated.png) \--- /task \---

\--- කාර්යය \--- දැන් ඔබේ ගායකයා සඳහා වෙනස් ඇඳුම් දෙකක් ඇති බැවින්, පෙන්විය යුතු ඇඳුම තෝරා ගත හැකිය! ඔබේ ගායක ස්ප්‍රයිට්)(sprite ) වෙත මෙම කේත කොටස් (code blocks) දෙක එකතු කරන්න:

```blocks3
when this sprite clicked
+switch costume to (singing v)
play sound (singer1 v) until done
+switch costume to (not singing v)
```

ඇඳුම වෙනස් කිරීම සඳහා කේත කොටස Looks{:class="block3looks"} කොටසෙහි ඈත \--- /task \---

\--- task \--- වේදිකාවේ සිටින ඔබේ ගායකයා මත ක්ලික් කර සිදුවන්නේ කුමක්දැයි බලන්න. ඇය ගායනා කරනවාද? \--- /task \---

\--- task \--- දැන් ඔබේ බෙරයට පහර දුන් බවක් පෙනෙන්නට සලස්වන්න!

![තිර රුව(screenshot)](images/band-drum-final.png)

- ඔබට උපකාර කිරීම සඳහා ඔබේ ගායක ස්ප්‍රයිට්ගේ ඇඳුම (sprite's costume) වෙනස් කිරීම සඳහා උපදෙස් (instructions) භාවිතා කරන්න.

ඔබගේ නව කේතය (code) ක්‍රියාත්මක වන බව පරීක්ෂා කිරීමට මතක තබා ගන්න! \--- /task \---