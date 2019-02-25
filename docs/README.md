Introduction
============
The default Marathi Inscript keyboard that comes with Windows 10 is missing the enhanced Inscript layout extensions. The enhanced layout still seems to lack access to punctuation via AltGr (or Ctrl+Alt) modifier key. Here, I present a modified enhanced Inscript keyboard layout that adds support for punctuation such as "?", "!", etc. without changing to English QWERTY keyboard. 

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

Note the [ZWJ](https://en.wikipedia.org/wiki/Zero-width_joiner) (Zero Width Joiner) and [ZWNJ](https://en.wikipedia.org/wiki/Zero-width_non-joiner) (Zero Width Non Joiner) on keys `१` and `२` respectively.

### With Shift and AltGr pressed
![](images/mr-enh-inscript-punct--alt-gr-shift.png)

Known Issues
============
Currently, it isn't possible to type `=` and `+` without changing to English keyboard. I will have to reassign `ृ`, `ऋ`, `ॄ`, and `ॠ` to some other key.
