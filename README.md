# DIFM-switch

### thanks to  D I . F M  radio family websites:

#### https://www. classicalradio.com/
#### https://www. di.fm/
#### https://www. jazzradio.com/
#### https://www. radiotunes.com/ aka https://www. sky.fm/
#### https://www. rockradio.com/

#### for Windows (7 and above) desktop Sortcut:
<pre>echo sc stop audiosrv > %HOMEPATH%/Desktop/FW-play.cmd
echo sc start audiosrv >> %HOMEPATH%/Desktop/FW-play.cmd
pause

</pre>

#### for Linux Ubuntu (18 and above) desktop Sortcut:
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


Todoes:
- [x] for Linux Ubuntu
- [ ] for Windows 7+
- [ ] for Mac OS 1x+
- [ ] for Android OS
- [ ] for iOS
