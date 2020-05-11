# Word Chain

[Word Chains Ruby Quiz](http://rubyquiz.com/quiz44.html)

Created a program that uses breadth first enumeration.

Given two words of equal length as command-line arguments, build a chain of words connecting the first to the second. Each word in the chain must be in the dictionary and every step along the chain changes exactly one letter from the previous word.

Program reads a dictionary file that holds over 38,000 words.

---

```ruby
pry(main)> words = WordChainer.new('dictionary.txt')

[15] pry(main)> words.run('duck', 'ruby')
=> ["duck", "dunk", "dune", "rune", "rube", "ruby"]
```

---

Shortcut: _Include the file name on the command line_

```ruby
[word_chain (master)]$ ruby wordChain.rb 'dictionary.txt'

["duck", "dunk", "dune", "rune", "rube", "ruby"]
```
