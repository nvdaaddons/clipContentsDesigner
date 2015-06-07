# Clip Contents Designer #
*   Authors: Noelia Ruiz Martínez.
*   Download [stable version][1]
*   Download [development version][2]

This add-on is used to append text to the clipboard, which can be useful when you want to join sections of text together ready for pasting.
The clipboard content can also be cleared.

## Keyboard commands ##
*   NVDA+windows+c: Append selected text, Unicode braille characters which represent MathML objects, or the string which has been marked with the review cursor, to the clipboard.
*   NVDA+windows+x: Clear clipboard contents.
*   NVDA+windows+f9: Mark the current position of the review cursor as the start of the text to be added to the clipboard.
    If you use nvda+F9, the text will not be appended.

Note: The above commands can be changed from NVDA menu, Preferences submenu, Input gestures dialog, Text review category.

## Preferences Menu ##
*   Clip Contents Designer settings: Allows to set a separator which can be used to find the text segments once the entire appended text is pasted. You can also choose if the separator should be copied to your personal NVDA's configuration folder, so that it can be imported when reinstalling the add-on.

Note: The above command can be changed from NVDA menu, Preferences submenu, Input gestures dialog, Configuration category.

## Changes for 3.0 ##
*   Braille representation of MathML objects can be appended to the clipboard if MathPlayer is installed.
*   If no separator is set, just a single line will be placed between the appended text segments.
*   A shortcut can be assigned tho open the Clip Contents Designer settings dialog.
*   Added a check box in the settings dialog, for choosing if the separator should be copied to be imported when reinstalling the add-on.

## Changes for 2.0 ##
*   Hindi characters can be used as the separator between appended contents.

## Changes for 1.0 ##
*   Initial version.

[1]: http://addons.nvda-project.org/files/get.php?file=ccd

[2]: http://addons.nvda-project.org/files/get.php?file=ccd-dev
