#  D I . F M  Play Forward brief explanation:
## While listenning one of these radiostations you can use a Premium "Skip" feauture aka "Play Forward" bug easily.

### thanks to  D I . F M  family internet-radio websites:

### https://www. classicalradio.com/
### https://www. di.fm/
### https://www. jazzradio.com/
### https://www. radiotunes.com/ former https://www. sky.fm/
### https://www. rockradio.com/

## #

<img src='https://raw.githubusercontent.com/BigBoatCap/DIFM-switch/master/Selection_042.png' /> 

## #

## All you have to do - is to restart your OS audio service.

## Here are some Desktop shortcut samples. A desktop shortcut "FW-play" may be created:

## #

### to Create a desktop Sortcut for Linux Ubuntu (18 and above) copy and paste to your Terminal:
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
## #
### to Create a desktop Batch script for Windows (7 and above) copy and paste to your cmd ( \<WinKey\>+\<R\> ==\> cmd ):
<pre>echo sc stop audiosrv > C:\Users\%USERNAME%\Desktop\FW-play.bat
echo sc start audiosrv >> C:\Users\%USERNAME%\Desktop\FW-play.bat
echo pause >> C:\Users\%USERNAME%\Desktop\FW-play.bat


</pre>

## #

<img src='https://raw.githubusercontent.com/BigBoatCap/DIFM-switch/master/Selection_043.png' /> 

## #


Todoes:
- [x] for Linux Ubuntu
- [ ] for Windows 7+ 
  - [ ] test shortcut
- [ ] for Mac OS 1x+
- [ ] for Android OS
- [ ] for iOS
