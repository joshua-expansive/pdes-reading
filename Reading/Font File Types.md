      

# Font File Types

  

As a reminder, a **typeface** is a set of alphabets and its corresponding numerals and punctuation that share a common design. For example, Helvetica is a well-known typeface. A **font** is a particular set of glyphs within a typeface. They are different fonts but the same typeface.

 ## Font formats 
Computers and devices display fonts in two ways, bit-mapped, and vector.

**Bit-mapped font (or raster font):** An arrangement of pixels represents every character. These fonts are faster and easier to use in computer code, but they are not scalable, which requires a separate font for each size and style.

**Vector font (or scalable font):** The outline of each character is defined geometrically. This allows a font to be scaled to any size using a single file but requires additional code to render the font for screens.
## Font File Types

**Postscript** fonts were created by Adobe and have two different parts: one for printing and one for screen display. They are great for high-quality printing, but they are not cross-compatible, meaning there are different versions for Macs and PCs. 

**Truetype (.TTF)** is a font format that was developed by Apple and was eventually licensed to Microsoft. They are unreliable for print but were created to replace the bitmap fonts previously used screen display. TrueType fonts only require one file, but a separate file needs to be added for each instance of the font (regular, italic, bold, etc.). 

**Opentype (.OTF & .TTF)** iis a newer font type built on the TrueType format that supports an expanded character set (small-caps, ligatures, glyphs, and alternatives inside the font instead of separate). Opentype offers its own set of advantages such as:
- **Broader multi-platform support:** A single font file works on both PCs and Macs.
- **Better language support:** OpenType fonts include the standard range of Latin characters and many international characters.
- **Advanced typography features:** An OpenType font file can contain many non-standard glyphs such as old-style figures, true small capitals, fractions, swashes, superiors, inferiors, titling letters, and a full range of ligatures.

**Embedded OpenType (.eot)** is supported exclusively by Internet Explorer versions 8.x and lower. EOT fonts' digital rights management technique prevents them from being copied and used without a license.

**Web open font format (.WOFF)** (WOFF) is a format that's used on web pages. It works just like TrueType and OpenType, but it makes your content download quicker since it's compressed. Currently, all browsers support WOFF. Often font vendors don't want to license their TrueType or OpenType format fonts for web use, but they'll license WOFF.

**SVG** fonts describe glyph outlines as vector objects, which usually results in larger file sizes. SVG is the only format used for the iPhone, iPad, and iPod touch before iOS 4.2.
