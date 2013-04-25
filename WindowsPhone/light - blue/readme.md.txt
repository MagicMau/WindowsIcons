- Maurits Elbers:

Created from "light" theme using techniques found at:

http://stackoverflow.com/questions/12165304/change-the-color-of-an-image-with-imagemagick

to green (PNG32 forces imagemagick to output a 32 bits png, which Photoshop likes better)

convert ( appbar.acorn.png -alpha extract ) -background "#C9DD03" -alpha shape PNG32:appbar.acorn.png

forfiles /c "cmd /c togreen.bat @file"
