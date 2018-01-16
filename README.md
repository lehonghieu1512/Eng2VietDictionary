# English to Vietnamese dictionary
An English to Vietnamese dictionary is built in C#
This dictionary is not only used for search for words that you don't you their meaning, but it is also used for some other purposes including adding new word, changing word-meaning (in case it's wrong), learning new word (with 5 distinct words every time you press the "Học" button in the "học từ mới" tab).
As for the structure of the data.txt which contains the whole data source for this project, since there are some words which do not have enough forms (verb, adj, noun, ect..), the length of their information may vary then we figured out a way to mark the end of a word or which is which. there are some compromises, "@" marks the beginning of the information of a word, "*" category, "-" meaning, "=" example, "!" the end of that word.
As for finding words, we use 'binary search' algorithm as opposed to conventional search whose complexity is O(n).
How to collect data? We manuall collected data through other dictionary-related sources which can be available widely on the internet.
