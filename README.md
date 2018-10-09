# History of the Development of Linux Libertine Arabic Numeral Glyphs

The two FontForge `.sfd` files in this repository contain the different
versions of arabic numeral glyphs through time, as recorded in its [SVN
Repository](https://sourceforge.net/p/linuxlibertine/svn/HEAD/tree/trunk/).
It therefore only covers the subset of development that took place between
August 2008 and the last revision (166) of September 2011. 

I have also added the glyphs of the last released version of Libertine under
the fake revision number of 170, however. There is unfortunately no available
record of the intermediate changes between 166 and the released version (or
I have been unable to find that record). 

The file `figure_history.sfd` records the full-size glyphs and the file
`small_figure_history.sfd` records the smaller glyphs used in super- and
subscripts and fractions. These are not “normal” `.sfd` files and need to
be viewed/understood in the following way:

1. All glyphs are “unencoded” and therefore appear at the bottom of the
   FontForge viewing window. You should __not__ use the `Encoding → Compact`
   option, however, and instead scroll down.

2. Set your main window so that it is 16 glyphs wide. That way the different
   groups of glyphs should all start on the left. 

3. The different groups/lines roughly correspond to different faces in the
   following order. (The parenthesized strings are those used to differentiate
   the styles in filenames at various points of development.)

   1. “Display” (DR, aDRS)
   2. “Display Italic” (aDRL)
   3. “Regular” (R, Re, C, C_Re, Sc, aS)
   4. “Italic” (It, RI, ISc, aSI)
   5. “Slant” (Sl, aRL)
   6. “Semibold” (RZI, aSZI)
   7. ”Semibold Italic” (RZI, aSZI)
   8. ”Semibold Slant” (BSl, aBL, aZL)
   9. ”Bold” (RB, BSc, Bd, aBS, aZS)
   10. ”Bold Italic” (RBI, BI, BiSC, aSBI)
   11. ”Bold Slant” (BSl, aBL)
   12. ”Outline” (I)
   13. ”Mono” (M)
   14. ”Underline” (U_Re)

   The correspondence is rough for several reasons. One is that this mapping
   is the result of guesswork on my part. Another is that sometimes a new
   stage of development started by copying the glyphs of another face. There
   was also a point in development where what had been called ”Bold” became
   ”Semibold”, and my mapping does not capture or correct for that change.

4. Glyphs are displayed in order of revision from most to least recent. Every
   glyph on a line is different from every other glyph, although sometimes only
   subtly.

5. The **Comment** for each glyph—shown in the second entry of the `Element
   → Glyph Info ...` window and (when it is working) the tooltip when hovering
   over a glyph—includes the filename-identifier/revision pairs that glyph
   appeared in.

6. Note that the only revisions represented are those in which a given `.sfd`
   file *changed*. When a file did not change in some revision it will not be
   listed anywhere. 
