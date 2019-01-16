## पोशाख

आता तुम्ही गायक बनवल्यासारखे वाटेल!

\--- task \--- नवीन पोशाख तयार करून क्लिक केल्यावर आपल्या गायकांना कसे दिसते ते बदलू शकता. Costumes टॅबवर क्लिक करा आणि आपल्याला गायक पोशाख दिसेल.

![स्क्रीनशॉट](images/band-singer-costume-annotated.png) \--- /task \---

\--- task \--- पोशाखवर उजवे-क्लिक करा आणि नंतर ** Duplicate** वर क्लिक करा त्याची एक प्रत तयार करण्यासाठी.

![स्क्रीनशॉट](images/band-singer-duplicate.png) \--- /task \---

\--- कार्य \--- नवीन पोशाख वर क्लिक करा ('Singer 2' म्हटले जाते), आणि नंतर लाइन टूल निवडा आणि रेषा काढा म्हणजे असे दिसते की आपला गायक आवाज काढत आहे.

![स्क्रीनशॉट](images/band-singer-click.png) \--- /task \---

\--- task \--- या वेळी पोशाखांची नावे फारच उपयुक्त नाहीत. त्यांचे नाव 'गायन' आणि 'गायन' मध्ये बदलण्यासाठी पोशाखांच्या मजकूर बॉक्समध्ये टाइप करा.

![स्क्रीनशॉट](images/band-singer-name-annotated.png) \--- /task \---

\--- task \--- आता आपल्या गायिकेसाठी दोन वेगवेगळ्या पोशाख आहेत, आपण कोणता पोशाख प्रदर्शित करू शकता ते निवडू शकता! आपल्या गायक स्प्राइटमध्ये या दोन कोड अवरोध जोडा:

```blocks3
when this sprite clicked
+switch costume to [singing v]
play sound [singer1 v] until done
+switch costume to [not singing]
```

The code block for changing the costume is in the `Looks`{:class="block3looks"} section. \--- /task \---

\--- task \--- Click on your singer on the stage. Does she look like she is singing? \--- /task \---

\--- task \--- Now make your drum look like it's being hit!

![screenshot](images/band-drum-final.png)

- आपल्याला मदत करण्यासाठी आपल्या गायक स्प्राइटच्या पोशाख बदलण्यासाठी निर्देश वापरा.

Remember to test that your new code works! \--- /task \---