# Moby Dick

### Challenge

Given two inputs from the user (a word and an integer), create a sentence in the style of Herman Melville's "Moby Dick".

The sentence length (in words) will be determined by the user's integer input, and the sentence will begin with the user's word input.

In order to create the sentence, you will need to determine, for each unique word in the book, the list of words that succeeds (comes after) it.

You will then randomly pick a word that succeeds the user's input word, and then randomly pick a word that succeeds that word, and so on, until you have a sentence that is the correct length.

The sentence will not be a correct English sentence, but it will sound a bit like Melville. For instance:

With an input of "Call" and 40, I got this:

> "Call life but tilted high aloft to know whether or maiming his flank of him that cook and the sea. and fetch another thing are madly merry as in the captain transfixed at steelkilt's threat, whatever grand and finding no means."

### Hints
You will do your work in `moby-dick.ipynb` (a Jupyter Notebook).

You will need to import and use `random`.

The book is Moby Dick, and the full text is in `moby.txt`

You will need to find a way to read each word of the book into a list of unique words. (What data structure should you use?) You can Google this.

Don't worry about odd punctuation or words. Just assume that spaces separate words. You should end up with about 32,000 unique words.

Output the list of words, how many words you found, how many unique words you have, etc.

Now, the hard part is the algorithm. Do some planning! How are you going to randomly choose a word that follows the input word? And then a word that follows that word?

Try to be as efficient as you can!

## Submit
Copy your final commit link from GitHub and paste it into the assignment in onBrooks.
