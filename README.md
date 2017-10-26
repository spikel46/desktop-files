# desktop-files
Quick and dirty introduction to creating your own .desktop files for linux


I referenced: https://cogitooverdose.wordpress.com/2016/02/21/how-to-write-desktop-files-linux/

So basically you have:

[Desktop Entry]
Name=<name of application>
Comment=<generic comment about the program>
Terminal=<T/F based on whether or not you want a terminal window to open>
Exec=<path to script that launches application>
Type=Application
Icon=<icon to be displayed. should be in /usr/share/icons>
Categories=<the categories of applications associated with the application>