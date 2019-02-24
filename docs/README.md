Introduction
============
The default Windows 10 Marathi Inscript keyboard is missing the enhanced Inscript layout extensions. The enhanced layout still seems to lack access to punctuation via AltGr (or Ctrl+Alt) modifier key.  I haven't seen the 2016 updated Inscript standard (IS 16350:2016) yet, but have seen an older draft from several years earlier.  Here, I present a modified enhanced Inscript keyboard layout that adds support for punctuation such as "?", "!", etc. without changing to English QWERTY keyboard. It also adds [ZWJ](https://en.wikipedia.org/wiki/Zero-width_joiner) (Zero Width Joiner) and [ZWNJ](https://en.wikipedia.org/wiki/Zero-width_non-joiner) (Zero Width Non Joiner) mappings.

Henceforth in this document, the "English QWERTY" shall be referred to as simply "English", and "Enhanced Inscript keyboard layout" shall be referred to as EIKL.

Installer
=========
Download the Installer zip file in the [latest release](https://github.com/iaswtw/mr-inscript-punct/releases/latest).  It contains the installer for the slightly modified layout to overcome the shortcomings of the default Inscript keyboard.

[This source](https://github.com/iaswtw/mr-inscript-punct/blob/master/source/Marathi%20Enhanced%20INSCRIPT%20with%20Punctuation.klc) file was used to create the installer using [Microsoft Keyboard Layout Creator 1.4](https://www.microsoft.com/en-us/download/details.aspx?id=22339). 

Layout
======
### Main layout, i..e Without Shift or AltGr pressed
![](images/mr-enh-inscript-punct.png)

### With Shift pressed
![](images/mr-enh-inscript-punct--shift.png)

### With AltGr pressed
![](images/mr-enh-inscript-punct--alt-gr.png)

Note the ZWJ and ZWNJ  on keys `१` and `२` respectively.

### With Shift and AltGr pressed
![](images/mr-enh-inscript-punct--alt-gr-shift.png)

