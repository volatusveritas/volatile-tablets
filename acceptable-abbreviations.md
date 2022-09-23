# Acceptable abbreviations

**Acceptable abbreviations** are shortened versions of words used in
identifiers. They are acceptable not only to the extent that they are allowed
in any identifier (which means any abbreviation not in this list is not allowed
in identifiers) but they are also recommended (use them whenever possible,
prefer them over their extended definitions).

The following list states globally acceptable abbreviations and their extended
definitions (by "globally acceptable" I mean to say that these should be used
in any project that doesn't disallow them):

| Abbreviation | Extended definition |
| :----------: | :-----------------: |
| str          | string              |
| int          | integer             |
| bool         | boolean             |
| arr          | array               |
| dict         | dictionary          |
| ptr          | pointer             |
| ref          | reference           |
| err          | error               |
| e            | exception           |
| u\<x\>       | unsigned\<x\>       |
| idx          | index               |
| prev         | previous            |
| max          | maximum             |
| min          | minimum             |
| op           | operation           |
| vec          | vector              |
| del          | delete              |
| exe          | execute             |
| val          | value               |
| buf          | buffer              |

## Project-specific abbreviations

Every project is different and may have additional acceptable abbreviations.
For example, when coding a game, using "hp" instead of "health points" and "sp"
instead of "stamina points" are common examples, and I personally like to
abbreviate "button" to "btn", while a program that deals with vectorized shapes
may abbreviate "vectors" to "vecs".

### Do it yourself

The general idea is that you should try to abbreviate those very common words
appearing everywhere in identifiers (function, variable and class names, for
instance) that have more than five characters into shorter versions with about
three or four characters.

Strive to be consistent. As an example, if the word "observation" appears in
many identifiers, either write it as "observation" everywhere (don't abbreviate
it anywhere at all), or as "obs" everywhere; don't break your consistency by
doing something like using "obs" in one file and "observation" in another. This
way, code written by you will be predictable not only to others, but also to
yourself.

## A project's abbreviation guidelines

One thing you could do to improve the consistency between members of a team is
to have the project's abbreviation list specified somewhere; either at the
project's documentation or at some dedicated file everyone has access to (e.g.
`abbreviations.abbr`; extension name pun intended).
