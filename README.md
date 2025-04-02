Exercise files to accompany a workshop on Regular Expressions given at the BitCurator Forum 2024 Philadelphia Satellite. Best used in conjunction with the [slides](https://docs.google.com/presentation/d/1yGw_TbF8MEM-cmXs9xDCULcUUGdv6ca0yYV4EhV7s-c/view).

## Exercise Instructions
1. Open [1-loremipsum.txt](1-loremipsum.txt) and change it from double-spaced to single-spaced.
2. The file [2-cats.txt](2-cats.txt) has a little description of your friend Catherine and her cat, except that you got a major detail wrong: Catherine has a dog, not a cat! Do a bulk find-and-replace without renaming your friend Dogherine.
3. Write a regular expression that will match all of the spellings of the name /kæþrǝn/ in the file [3-qathorone.txt](3-qathorone.txt)
    - After getting a handle on quantifiers, you can try a slightly trickier version of this exercise by matching all of the spelling variations in [qathron.txt](qathron.txt)
4. Regex can be used for quick-and-dirty HTML/XML parsing. Open [4-SwatLibraryStaff.html](4-SwatLibraryStaff.html) and write a regular expression that will find all of the href attributes along with their values.
5. All of the lines in [5-loremipsum.txt](5-loremipsum.txt) are of the form  `X Y Z. X Y Z.` Write a regular expression to deduplicate these
6. The file [6-dates.txt](6-dates.txt) contains 900 lines of dates in MM/DD/YYYY format. Put them into ISO format (YYYY-MM-DD)
