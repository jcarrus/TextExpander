TextExpander
============

A simple HTML text expansion tool that allows inline creation of shortcuts.

The entire application is condensed into one HTML file that can work offilne.
The user interface only consists of a textarea that the user can type into.
The key combination ";;shortcut" is used to activate the expansion tool where
"shortcut" is the shortcut to be expanded. To create a new shortcut, use the 
format "::text expansion::shortcut" where "text expansion" is the text that 
you want to replace the shortcut text with. Once a new shortcut is created,
it is displayed to the right side of the text box.

This tool has several features that make it unique. First, the inline creation
of shortcuts allows the user to create new shortcuts with minimal keystrokes.
Additionally, the system of using a double semi-colon to activate the
expansion allows the shortcuts to be real words and not just an abbreviation 
(e.g. ;;add to expand one's address). Finally, all of the information is 
stored in session storage which means that the shortcuts are reset every time 
the user closes the application. This allows shortcuts to be created that are
very short because the user does not have to worry that one day a very simple
shortcut would better be used in another expansion.
