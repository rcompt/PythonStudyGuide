# [PEP8 Styleguide](https://www.python.org/dev/peps/pep-0008/)

## Code is read much more often than it is written

## Advice
* A style guide is about consistency
* Do not break backwards compatibility just to comply with this PEP
* Some other good reasons to ignore a particular guideline
1. When applying the guideline would make the code less readable, even for someone who is used to reading code that follows this PEP.
2. To be consistent with surrounding code that also breaks it (maybe for historic reasons) -- although this is also an opportunity to clean up someone else's mess (in true XP style).
3. Because the code in question predates the introduction of the guideline and there is no other reason to be modifying that code.
4. When the code needs to remain compatible with older versions of Python that don't support the feature recommended by the style guide.

## Code Lay-out
* 4 spaces per indentation
* Continuation lines should align wrapped elements either vertically using Python's implicit line joining inside parentheses, brackets and braces, or using a hanging indent 
** When using a hanging indent the following should be considered; there should be no arguments on the first line and further indentation should be used to clearly distinguish itself as a continuation line.
