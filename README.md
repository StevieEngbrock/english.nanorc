# English.nanorc

-----------------------------------------------------------------------------------------------------------------

This Just a simple attempt at adding syntax highlighting for English to the nano editor. 
This was motivated out of my love for writing and language and frustration that syntax highlighting for English
is almost never supported in any editor of any kind. The idea is that the highlighting will help make the logic
and relationships and similar things of what you are writing easier to analyze and work with when you are writing
a story, poem, or whatever type of English document you happen to be writing. This syntax highlighter is not case
sensitive and it covers the following classes. 

-----------------------------------------------------------------------------------------------------------------
# Word Classes


# 1. Logical words.

and,or, not, if,else,when, while, until, but, all, none, any

# 2. Number Words

one, two, three, four, five, six, seven, eight, nine, ten,
eleven, twelve, thirteen, fourteen, fifteen, sixteen, seventeen, eighteen, nineteen  
twenty, thirty, forty, fifty, sixty, seventy, eighty, ninety, hundred, thousand, 
ten thousand, hundred thousand, million, billion, trillion

Numbers like "four hundred and ninety two" , that are made by combining these words are also covered. 
Numbers containing "and" will have "and" highlighted in the color supported by nano that is called "brightcyan"

# 3. Integers and Floats

written with digits and decimal points

# 4. Relationship Words

to,from,with,of, in, on, off, as, at, by, like

# 5. Singleness

a, the, that, it,one,this

# 6. Pronouns

i, he, she, they, you, we, them, her, thee, thou

# 7. Ownership

me, my, has, had, have, mine, his, her's, your, your's

# 8. Action

do, does, did, go, went

# 9. Markdown-like

It is not meant to be support for markdown syntax highlighting.
It is however inspired by markdown and colors headers that match the regular expression "# (.*)" blue and colors any "-" character the color called "beet" in the nano supported colors. The Markdown-like highlighting works well with the highlighting of the integers and together they
work well when used with lists.

# 10. Misc

There are also a few misc categories, nothing special, view the code if you're interested in that or anything else about it.


-----------------------------------------------------------------------------------------------------------------


# License

It's licensed under the unlicense. Reuse it, alter it, copy it, do whatever you want with it!
I'm even cool with it if you want to use it to help train AI.

# Required File Extension

Please note for the syntax highlighter to work the extension of the file should be .txt

# Contributing

If you want to contribute, just send me a message here on github and we'll figure something out


# Submitting Security Reports

I'm not sure how a .nanorc file can have a security problem but if you find a problem,  
tell me and I will try to fix it the best as I can.  
Your suggestions and contributions on fixing security problems are also welcome.  
Message me here on github if you want to get ahold of me.  
