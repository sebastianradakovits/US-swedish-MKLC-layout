# US-swedish-MKLC-layout
A keyboard layout for Windows created with Microsoft Keyboard Layout Creator version 1.4 (MKLC) based on the US layout, but allowing the user to type the letters å, ä and ö using the AltGr key. AltGr+[, AltGr+' and AltGr+; for å, ä and ö respectively (capital versions with Shift+AltGr). This mirrors the placement of ÅÄÖ in the Swedish QWERTY layout, and is also found in some layouts availible on linux. The diacritics "´", "`" and "¨" can also be typed in combination with some letters using AltGr+=, AltGr+Shift+= and AltGr+] respectively (also mimicking the swedish QWERTY layout) allowing loan words like "armé" to be typed. Additionally, the "€" symbol is availible with AltGr+e.

# Installing the layout
The layout can be installed by downloading the contents of this repository and executing either the "setup.exe" or the relevant .msi file. If that doesn't work, install MKLC and load the layout from the "US_ÅÄÖ.klc" file and create the setup files using the Project->Build DLL and Setup Package dialogue in MKLC. After this the layout should be selectable in the dropdown menu in windows settings. Additionally a restart may be required to get the layout to work. 

The Windows+Space shortcut can be used to switch between active keyboard layouts, but if that doesn't work, the layout can also be switched to using Ctrl+Shift.

# Editing the layout
Load the US_ÅÄÖ.klc file in MKLC.

# Uninstalling the layout
Simply execute the installation file again to get an uninstall dialouge. If the installation file is lost the layout has to be uninstalled using the windows registry editor.
