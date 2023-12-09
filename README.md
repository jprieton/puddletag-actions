### English case

Convert to proper title case.

- Convert to upper case the first letter of every word in the string
- Fix lower-cases prepositions
- Convert to upper case the first letter of the string
- Convert to upper case the first letter after "*?*", "*!*" and "*(*"

**Know issues**:

* Sometimes require convert to lower case the string before apply
* Requires a manual review the result by context
* Acronyms maybe can converted incorrectly

### Fix spaces

This fix spaces issues.

* Replaces "*%20*" and "*_*" by spaces
* Adds space after "*?*" and "*!*"
* Adds space before "*¿*" and "*¡*"
* Replaces multiples spaces to single space
* Trim the beginning and trailing spaces

### Gapless

Mark the file as gapless using `comment:iTunPGAP` field.