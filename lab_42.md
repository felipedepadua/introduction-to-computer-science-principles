# You Talkin' to Me?

In this lab, you will create a simple sentence generator using lists.  (Adapted from BJC: http://bjc.berkeley.edu/bjc-r/cur/programming/lists/hof/what-good-are-lists.html?topic=berkeley_bjc%2Flists%2Flists-I.topic)

## Let's Talk
1. Create a variable for each part of speech below, and set each variable to hold a list of words that fit that part of speech.  Some examples are given, but feel free to use your own.
| Part of Speech | Example words |
| -- | -- |
|noun | giraffe, monkey, boy, girl, elephant, ...|
|verb | jumps, runs, sleeps, sits, dances, ...|
|adjective | big, small, loud, silly, young, old, sleepy, ...| 
|adverb | quickly, excitedly, angrily, happily, sadly, ...
|article | a, the|
|preposition | under, over, around, near, beside, ...|

1. Write a custom reporter block called "noun phrase" that reports a noun phrase where each word is chosen randomly from the lists you created.  A noun phrase consists of an article, an adjective, and a noun in that order.

1. Write custom reporter blocks like "noun phrase" for each of the phrase types listed below.
|Phrase type | Construction|
| -- | -- |
|prepositional phrase | preposition, noun phrase|
|verb phrase | adverb, verb, preposition phrase|
|sentence | noun phrase, verb phrase|

1. Write code so that when you press the space bar, a random sentence is generated and a sprite says the resulting sentence.
 
1. BONUS: Modify your code so that a noun phrase can either be the construction from part 1.2 or a single proper noun (e.g. a person's name).  Your code should randomly decide which version of a noun phrase to use.

1. BONUS: Modify your code so that a verb phrase can sometimes leave out the prepositional phrase.  Your code should randomly decide to include the prepositional phrase or not.

## Changing Our Vocabulary

1. Write a script so that when the ‘n' key is pressed, the user is prompted for a new noun and that noun is added to list of nouns.  After that point, the new noun entered by the user should be able to appear in sentences.

1. Write scripts like the one you wrote in part 2.1 to add words to the other lists.  Use the keys listed below.
|Key | Part of speech|
| -- | -- |
|v | verb|
|j | adjective|
|d | adverb|
|a | article|
|p | preposition|

1. Write a script so that when the ‘x' key is pressed, the user is asked for one of the parts of speech and then for a number (n).  Your script should remove the nth item from the list of words for the specified part of speech.  For example, if the user types in "verb" and "3" then you should remove the 3rd word from the list of verbs.  The removed word should no longer appear in sentences.