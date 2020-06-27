# DIFM-switch Brief explanation:
## While listenning one of these radiostations you can use a Premium "Skip" feauture aka "Play Forward" bug easily.
## # ###########################################################################

### thanks to  D I . F M  radio family websites:

### https://www. classicalradio.com/
### https://www. di.fm/
### https://www. jazzradio.com/
### https://www. radiotunes.com/ aka https://www. sky.fm/
### https://www. rockradio.com/

## # ###########################################################################

![alt text](https://github.com/BigBoatCap/DIFM-switch.git/blob/master/Selection_042.png?raw=true)

## All you have to do - is to restart your OS audio service.

## Here are some Desktop shortcut samples. 
## A desktop shortcut "FW-play" may be created:

### for Linux Ubuntu (18 and above) desktop Sortcut:
<pre>echo '[Desktop Entry]
Name=FW-play
Exec=killall pulseaudio
Icon=livepatch
Type=Application
Categories=GTK;GNOME;Utility;
Terminal=false' > ~/.local/share/applications/FW-play.desktop
cp !$ ~/Desktop/
chmod u+x ~/Desktop/FW-play.desktop
gio set !$ "metadata::trusted" true

</pre>

### for Windows (7 and above) desktop Sortcut:
<pre>echo sc stop audiosrv > %HOMEPATH%\FW-play.cmd
echo sc start audiosrv >> %HOMEPATH%\FW-play.cmd
echo pause >> %HOMEPATH%\FW-play.cmd
mklink %HOMEPATH%\Desktop\FW-play.lnk %HOMEPATH%\FW-play.cmd

</pre>


Todoes:
- [x] for Linux Ubuntu
- [ ] for Windows 7+ 
  - [ ] eliminate mklink with batch commands
- [ ] for Mac OS 1x+
- [ ] for Android OS
- [ ] for iOS
