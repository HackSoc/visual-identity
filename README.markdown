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

The HackSoc fonts are **Rokkit**, **Sanchez**, and **Bitstream Vera
Sans**:

 - **Rokkit** the name of the society in the logo, and should not be
     used elsewhere.

 - **Sanchez** the tagline in the logo, and heading elements in body
     text.

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
looking for something else. The weekly poster uses it for the URL
fragment which isn't HackSoc specific in our social media links, like
"twitter.com/". Hopefully that'll help you figure out the sort of
things it's intended for.

Below is a table of CMYK and RGB values. CMYK should be preferred when
the result will be for print.

   Colour   |     (R,G,B)     |    (C,M,Y,K)
------------|-----------------|-----------------
Background  | (255, 217, 204) | ( 0, 15, 20,  0)
Text        | ( 33,  33,  33) | ( 0,  0,  0, 87)
Heading     | ( 64,  72,  84) | (24, 14,  0, 67)
Emphasis    | ( 38,  78, 135) | (72, 42,  0, 47)
De-emphasis | ( 84,  84,  84) | ( 0,  0,  0, 67)

Logo
----

The HackSoc logo consists of the text "HackSoc" (with that
capitalisation) in the font Rokkit and colour Text. In the line below
it, the text "the computer science society" in the font Sanchez and
colour Text, except for "computer science" which is in colour
Emphasis.

Relative font sizes are chosen such that the "y" in "society" is below
the serif of the "c" in "HackSoc", and the "t" in "the" is below the
gap between the "H" and "a" of "HackSoc".

Or, in pictures:

![HackSoc Logo](logo-for-readme.png)

The logo should not be modified. There is a small version which omits
the tagline which should be used if the logo will be displayed too
small to read it. If the logo needs to be used on something with a
dark background, or in some other context where it looks suboptimal,
consult IRC and we shall produce a new official variant.

General Points
--------------

 - If a new colour scheme is needed for whatever reason, the Adobe
   [Color wheel][] is really good.

### Hypertext

 - The colour Emphasis should be used for hyperlinks.

 - Web Fonts should be used to ensure correct display. All of the
   HackSoc fonts are available through [Google Web Fonts][].

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
   should be used.

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
