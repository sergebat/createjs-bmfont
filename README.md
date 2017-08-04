# createjs-bmfont

Bitmap font for createjs easeljs. Expects XML and PNG, prepared with 
http://www.angelcode.com/products/bmfont/ for windows or http://www.bmglyph.com/ for mac or
http://kvazars.com/littera/ web app

Original EaselJS approach is to use spritesheets. Unfortunately spritesheets do not retain *spacing information*
 (distance from individual characters to the next symbol).

Additional features:
- Font size in points
- (coming) Kerning https://en.wikipedia.org/wiki/Kerning (apps above export kerning info, if it is available in the
original font file)
