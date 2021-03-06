# Anagrams

### Google Applied CS with Android - Unit 1

This workshop is part of the Applied CS with Android course: http://g.co/cswithandroid

The mechanics of the game are as follows:

* The game provides the user with a word from the dictionary.
* The user tries to create as many words as possible that contain all the letters of the given word plus one additional letter. Note that adding the extra letter at the beginning or the end without reordering the other letters is not valid. For example, if the game picks the word 'ore' as a starter, the user might guess 'rose' or 'zero' but not 'sore'.
* The user can give up and see the words that they did not guess.

In order to ensure that the game is not too difficult, the computer will only propose words that have at least 5 possible valid anagrams.
