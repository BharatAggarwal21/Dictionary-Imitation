# Dictionary-Imitation
The project is based on dictionary implementation through data structures. 
The main data structure used is <b>Trie</b>.

There are two files one which is containing the words and the other is containin the words with their meanings.<br>
All the words are fetched from the file and stored in Trie tree with each node consisting of array of length 26 characters.<br>
Each index corresponds to alphabet in english language ex- 0->a, 1->b, so on.
<br>
Words are stored in level down manner and for getting a word that exists in Trie we do a DFS traversal.
<br>
Also there is a variable associated with <b>"end of word"</b> which tells whether a word ends on this node and this index of Trie.
<br>
For suggesting words based on substring a recursion is called upon the node where we traverse and find the corresponding substring.
<br>
The recursion prints the words starting with that string in sorted or alphabetical order.
<br>
Addition of a word makes the "end of word of last node to <b>True</b> and stores it in the file.
