# Turbo Play Translation Files


## language_en.h

Language_en must be translated entirely

## menus.rc and mainmenu.rc

Menu strings to be translated in double quotes, e.g. "File".

## dialogs.rc

Lines like that ```PUSHBUTTON      "Change...", 202, 354, 61, 40, 14``` , the "Change..." is to be translated. Not to be translated if it contains ~.

## ribbon.rib

Only lines starting with `<Command` are to be translated, the "LabelTitle" section, for example

`<Command Name="t21006i" Id="13809" LabelTitle="Motion Detector" >`

Translate the "Motion Detector" string.




