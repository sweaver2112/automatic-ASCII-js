# Automatic ASCII Art from any Image.

No dependencies other than a Google font (use any monospace font)

https://sweaver2112.github.io/automatic-ASCII-js/

HOW TO USE:

You can control the "column count" by changing Pixel Size. Note that Pixel Size can be set as low as 1 pixel, but this should not be done on large images and will take much longer to render.

The character map goes from Dark to Light, which is to say, the leftmost character of the map string would be assigned to the darkest pixels in the original image, and so on.  You can tweak the result just by changing a character in the map.

You can use the space character anywhere you want...empty space.

The number of brightness levels is determined by the number of characters in the map, so you could use a simple map of two chars `_$` or a longer map with lots of chars `_supercalifragilisticexpialidocious_`.   The only limit is your imagination, but you'll have better luck with 'common' letters, numbers, and punctuation - other, more esoteric symbols tend not be equal width.
