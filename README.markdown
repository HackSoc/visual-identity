HackSoc Visual Identity
=======================

This repository contains information on the standard HackSoc visual
identity for marketing purposes. There are a number of subdirectories:

 - **logo** contains variations of the HackSoc logo, both the original
    Scribus '.sla' files, and derived high-resolution versions in
    other formats.

 - **flyers**, **posters**, and **slides** contains promotional
     material we have created and distributed.

Fonts
-----

The HackSoc fonts are **Roboto Slab Regular**, **Sanchez**, and
**Bitstream Vera Sans**:

 - **Roboto Slab Regular** the name of the society and tagline in the
   logo, and should not be used elsewhere.

 - **Sanchez** heading elements in body text.

 - **Bitstream Vera Sans** body text, bolding may be used for
     emphasis, but in general the font should be normal.


The meaning of "heading" is up to interpretation depending on the
medium. Basically: not body text, but something which stands out and
tells you what is going on.
     
Colours
-------

![HackSoc Colours](colours.png)

There are five HackSoc colours:

 - **Background** Background colour for documents. White is acceptable
     if necessary.

 - **Text** Main body text and logo.

 - **Heading** Section headings.

 - **Emphasis** Highlight important information.

 - **De-emphasis** Something which is necessary, but unimportant or
     uninteresting.

There are two additional colours for use with the logo - Logo Text and
Logo Emphasis.

Use of colours doesn't have to strictly follow the above rules. For
example, in the weekly poster template, Text and Sanchez are used for
day and week names, despite them acting as headings, with event titles
using Emphasis and Bitstream Vera Sans. Do whatever looks best in the
document you are producing, however documents should be consistent
with themselves, and preferably also with other media produced for the
same campaign (for example, flyers and posters to advertise a single
event).

There are no hard rules for where to use de-emphasis. The website uses
it for "At the University of York": obviously we're at UoY, but it's
worth confirming for the people who might stumble across our website
looking for something else. Hopefully that'll help you figure out the 
sort of things it's intended for.

Below is a table of CMYK and RGB values. CMYK should be preferred when
the result will be for print.

   Colour         |     (R,G,B)     |   Hex   |     (C,M,Y,K)
------------------|-----------------|---------|------------------
Background        | (243, 242, 244) | #F3F2F4 | ( 0,  1,  0,  4)
Text              | ( 33,  33,  33) | #212121 | ( 0,  0,  0, 87)
Heading           | ( 64,  72,  84) | #404854 | (24, 14,  0, 67)
Emphasis          | ( 38,  78, 135) | #264E87 | (72, 42,  0, 47)
De-emphasis       | ( 84,  84,  84) | #545454 | ( 0,  0,  0, 67)
Logo Text         | ( 68,  68,  68) | #444444 | ( 0,  0,  0, 73)
Logo Emphasis     | ( 68,  55,  82) | #443752 | (17, 33,  0, 68)

Logo
----
The HackSoc logo is formed of two parts: the Lambda mark and the logo
text.

### Lambda mark
The Lambda mark is the core visual representation of the society;
other parts of the the logo should not be included without it. The
colours should not be modified from the logo image file.

### Logo text
The logo text is displayed to the right of the Lambda mark, and
consists of the text "HackSoc" (with that capitalisation) in the font
Roboto Slab Regular and colour Logo Text. In the tagline below it, the
text "the computer science society" in the same font and colour,
except for "computer science" which is in colour Logo Emphasis.

The two lines should be of equal length - if this is not possible then
the tagline should be shorter than the name. Font sizes of 7em and 2em
are recommended for the name and tagline respectively.

If there is not space for the full logo to be displayed (or if the
logo text would be too small to read), then the Lambda mark may be
used on its own. The logo text should never be used on its own.

![HackSoc Logo](logo-for-readme.png) <!-- TODO update this logo -->

The logo should not be modified. If the symbol or logo needs to be
used on something with a dark background, or in some other context
where it looks suboptimal, consult #hacksoc on IRC or email
hack@yusu.org and we shall produce a new official variant.

General Points
--------------

 - If a new colour scheme is needed for whatever reason, the Adobe
   [Color wheel][] is really good.

### Hypertext

 - The colour Emphasis should be used for hyperlinks.

 - Web Fonts should be used to ensure correct display. Roboto Slab and
   Sanchez are available through [Google Web Fonts][].

## Posters, Flyers, Slides, etc

 - Documents should be produced with an actual desktop publishing
   tool, *not* LaTeX or OpenOffice Writer. [Scribus][] is a really
   good tool, and the logo source files are in Scribus format.

 - PDFs should embed all fonts used to ensure correct display.

 - Vector images should be greatly preferred to raster images if a
   figure is required.

 - If raster images are embedded, they should be *at least* 300dpi.

 - If intended for print, CMYK *must* be used to ensure accurate
   colour reproduction.

### Social Media Profiles

 - If the profile picture is displayed at a sufficient size for the
   logo tagline to be read *clearly* then the full version should be
   used. In the much more likely case that it's not, the small logo
   (just the Lambda mark) should be used.

 - The profile picture should be of the appropriate shape (probably
   square), of the colour Background, with the logo centred both
   horizontally and vertically.

 - If some sort of banner is required, it should be something
   obviously related to the society (a generic picture of code, not so
   great), like a photo of a *recent* event, or something relating to
   the university. If in doubt, use a nice photo of a duck.

[Color wheel]:      https://color.adobe.com
[Google Web Fonts]: https://www.google.com/fonts
[Scribus]:          http://www.scribus.net
