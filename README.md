# latcyr

> A result of a hypomanic state in the fall with bipolar disorder.

Here is a variant of partial latinization of some Slavic languages (Russian, Ukrainian, Belarusian).
It does not completely replace all letters of the alphabets, leaving Cyrillic ones where appropriate.
Most of the letters, nevertheless, have been turned to Latin to save memory space when storing in multibyte encodings and for more comfortable reading (a lot of lowercase letters have extension elements, they are smaller in width).

**When compiling the alphabets, the following goals were pursued:**

+ letters should be easy to read, distinguishable from each other, as simple as possible and shoud not have unnecessary hooks and appendages
+ no separated accents from letters except for dots above i & j
+ no superscript acdents to be able to indicate the accent and the softening with acute
+ no digraphs if they were not in the original alphabet, including the letter Ю
+ new letters must match in sound, or be similar in old letters, in case it is impossible to find a new character without diacritics (Ж -> X)
+ letters with a similar sound from all languages are turned into one (russian Ы & ukrainian И both turn into Y)

**Advice:**

+ use fonts with the letter Щ in the Old Church Slavonic style
+ use an acute accent above soft consonants instead of a soft sign after them, but the soft sign is also allowed
+ use letters from other alphabets in this set to convey special sounds in loan words for which there is no letter in the current language (Ў to denote W)
+ take your med

**How to use?**

+ `alphabets` contains the alphabets. One line is one letter. The first column is uppercase, the second one is lowercase.
+ `maps` contains the maps of new characters to the old. The first column is old, the second is new.
+ `examples` contains the examples of texts typed with new alphas. Pangram and the lorem ipsum.

