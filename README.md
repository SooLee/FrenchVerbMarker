# FrenchVerbMarker
A web page that allows the user to mark French verbs according to their tense / mood.

![](./FrenchVerbMarker_whole_screen_example.png)


## How to use it

The user opens a text file and marks verbs by selecting each verb and pressing one of the buttons on the right side. This is purely for practicing purpose and it's up to the user to find the correct answer.

![](./FrenchVerbMarker_example.png)

The user can save the current marks by clicking 'Save' and reuse it next time by opening it as the vm index file.

The dictionary button is useful for learning new words. Simply select a word and press the dictionary button.

![](FrenchVerbMarker_dictionary_example.png)


## Glitches
* To load another text (or the same text again), opening a new text file would not work because it will add to the end of the current text. Refresh the page by using Ctrl-R instead and start over. Make sure to save what you have before refreshing.
* It requires the internect connection because it is used for drawing the piechart whih keeps track of the verb type frequency.
* If you modify the text outside the app, your previously saved vm index files may no longer work.

## What is a word?
* For convenience, a word does not contain any special character. For example, `J'ai` is not a word but only the `ai` part is. In `Qu'est-ce`, only the `est` part is a word. If you select past the boundary of a word, the marker would not work, though the dictionary could still work if it exists. For example, `peut-être` may exist in the dictionary, but you won't be able to mark the whole thing as a verb.

