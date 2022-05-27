# Acceptable abbreviations

**Acceptable abbreviations** are shortened versions of words used in
identifiers. They are acceptable not only to the extent that they are allowed
in any identifier (which means any abbreviation not in this list is not allowed
in identifiers) but they are also recommended (use them whenever possible,
prefer them over their extended definitions).

The following list states all acceptable abbreviations and their extended
definitions:

| Abbreviation | Extended definition |
| :----------: | :-----------------: |
| str          | string              |
| int          | integer             |
| bool         | boolean             |
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

Every project is different and is going to have additional acceptable
abbreviations (e.g. when coding a game, using "hp" instead of "health points"
and "sp" instead of "stamina points" are common examples, and I personally like
to abbreviate "button" to "btn"). The general idea is that you should try to
abbreviate very common words that have more than five characters into short
versions with about three or four characters.

Strive to be consistent. For example, if the word "observation" appears in many
identifiers, either write it as "observation" everywhere (don't abbreviate it
anywhere at all), or as "obs" everywhere; don't break your consistency by e.g.
using "obs" in one file and "observation" in another.
