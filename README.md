#  D I . F M  Play Forward brief explanation:
## While listenning one of these radiostations you can use a Premium "Skip" feature aka "Play Forward" bug easily.

### thanks to  D I . F M  family internet-radio websites:

### https://www. classicalradio.com/
### https://www. di.fm/
### https://www. jazzradio.com/
### https://www. radiotunes.com/ former https://www. sky.fm/
### https://www. rockradio.com/
### https://www. zenradio.com/

## #

<img src='https://raw.githubusercontent.com/BigBoatCap/DIFM-switch/master/Selection_042.png' /> 

## #

## All you have to do - is to restart your OS audio service.

## Here are some Desktop shortcut samples. A desktop shortcut "FW-play" may be created:

## #

### <b> to Create a desktop Sortcut for </b>Linux Ubuntu (18 and above)<b> copy and paste into your Terminal</b>:
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
### <b text="to Create a desktop Batch script for" />Windows 10 <b text="copy and paste into your cmd ( \<WinKey\>+\<R\> ==\> cmd )" />:
<pre>echo sc stop audiosrv > C:\Users\%USERNAME%\Desktop\FW-play.bat
echo sc start audiosrv >> C:\Users\%USERNAME%\Desktop\FW-play.bat
echo pause >> C:\Users\%USERNAME%\Desktop\FW-play.bat

</pre>

## #

<img src='https://raw.githubusercontent.com/BigBoatCap/DIFM-switch/master/Selection_043.png' /> 

## #

#### Utilities and double-click on Terminal, 
#### or press Command - spacebar to launch Spotlight and type "Terminal," then double-click the search result.

### Service restart for MacOS (10 and above) copy and paste into your Terminal:
<pre>
killall coreaudiod
</pre>
## #

### A hint for AFK pause ( also it works for youtube ):

<img src='https://raw.githubusercontent.com/BigBoatCap/DIFM-switch/master/Selection_044.png' /> 

## #

### Just press \<SPASE\> and the best music goes on with no interruptions! =)

Todoes:
- [x] for Linux Ubuntu
  - [x] 18.04
  - [x] 20.04 <== better behaviour
- [ ] for Windows 7+
  - [ ] test shortcut on Windows 7 and 8
- [ ] for Mac OS 10+
  - [ ] test coreaudiod service restart
- [ ] for Android OS
- [ ] for iOS
