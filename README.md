### English case

Convert to proper title case.

- Convert to upper case the first letter of every word in the string
- Fix lower-cases prepositions
- Convert to upper case the first letter of the string
- Convert to upper case the first letter after "*?*", "*!*" and "*(*"
- Convert to lower case the first letter next to a contraction

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

### Spanish case

Convert to proper title case.

- Convert to upper case the first letter of the string
- Convert to upper case the first letter after "*¿*", "*?*", "*¡*", "*!*" and "*(*"

**Know issues**:

* Sometimes require convert to lower case the string before apply
* Requires a manual review the result by context
* Acronyms maybe can converted incorrectly

### Remove Remastered

Remove "*Remastered*" from the title and/or album.

- Remove "(*Remastered*)", "(*Remastered 2015*)" and "(*2015 Remastered*)"
- Also allows square brackets, ie. "[*Remastered*]", "[*Remastered 2015*]" and "[*2015 Remastered*]"
- Case insensitive

### Copy Artist to Album Artist

Copy the artist field to the album artist field.