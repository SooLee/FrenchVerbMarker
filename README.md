# FrenchVerbMarker
* A web page that allows the user to mark French verbs according to their tense / mood.

## Disclaimer
I wrote this to aid my own French learning. I understand most people would not use this kind of learning approach, but it works for me and I'm sharing this code not to open a discussion about how best to learn French but for those who think it may benefit them. 

## Example screen shot

![](./FrenchVerbMarker_whole_screen_example.png)


## How to use it

Just open the `index.html` file using your Web browser. I only tested it on Chrome.

Then, open a text file and mark verbs by selecting each verb and pressing one of the buttons on the right side. This is purely for practicing purpose and it's up to the user to find the correct answer (the app does not provide a correct answer).

![](./FrenchVerbMarker_example.png)

### Saving the progress
The user can save the current marks by clicking 'Save' to save it into a vm index file. It will most likely be saved in your `Downloads` folder. You can euse the existing vm index next time by opening it as the vm index file. This way you can start from where you left off last time. Every time you press the 'Save' button, it saves it into a new vm index file, with the file name containing the time stamp.

### Dictionary
The dictionary button is useful for learning new words. Simply select any text (mostly a word) and press the dictionary button.

![](FrenchVerbMarker_dictionary_example.png)


## Glitches
* To load another text (or the same text again), opening a new text file would not work because it will add to the end of the current text. Refresh the page by using Ctrl-R instead and start over. Make sure to save what you have before refreshing.
* It requires the internect connection because it is used for drawing the piechart whih keeps track of the verb type frequency.
* If you modify the text outside the app, your previously saved vm index files may no longer work.

## What is a word?
* For convenience, a 'word,' as the unit of marking, does not contain any special character. For example, `J'ai` is not a word but only the `ai` part is. In `Qu'est-ce`, only the `est` part is a word. If you select past the boundary of a word, the marker would not work, though the dictionary could still work if it exists. For example, `peut-être` may exist in the dictionary as a word, but you won't be able to mark the whole thing as a verb (of course it is also not a verb).

