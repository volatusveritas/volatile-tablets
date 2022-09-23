# Frame Specs

**Frame specs** are rules concerning the positioning and spacing of, and
between, elements in code files. Having consistent spacing between elements in
an organized manner makes your layout predictable, so anyone reading your code
has no trouble at all knowing where to look next for a specific kind of
element. Here are some rules regarding this topic:

1. No line may have more than 79 characters (newlines do not count), leaving
   the 80th character empty always. This helps one avoid horizontal scrolling
   (by merit of which visual context is partitioned) and also allows screen
   splitting and multi viewing without cropping in a majority of usual editor
   settings and font sizes.

1. There must be at least two, and at most four, spaces separating the
   declaration of top level elements. Make this consistent across a project,
   that is, if you separate top level elements with three spaces somewhere, do
   so everywhere. Non top level or related elements must have less spaces
   between them, so there is a visual distinction between the parts of a top
   level element (such as the lines inside a top level function) and the
   elements themselves (such as the top level functions in a file). The
   recommended values are two surrounding spaces between top level elements and
   one space between non top level elements.

These rules apply to source code files; other kinds of code files may have
their own rules, specified in their own style guides.
