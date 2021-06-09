#####  D I . F M  Play Forward brief explanation:
 While listenning any station you are able to use a Premium "Skip" feature aka "Play Forward" bug in the followng way.

#### Many Thanks to  D I . F M - the greatest internet-radio websites collection with so many gene-oriented music subcategories:

- https://www. classicalradio.com/
- https://www. di.fm/
- https://www. jazzradio.com/
- https://www. radiotunes.com/ _former _sky.fm_
- https://www. rockradio.com/
- https://www. zenradio.com/

## #

<img src='https://raw.githubusercontent.com/BigBoatCap/DIFM-switch/master/Selection_042.png' /> 

## #

_All you have to do - is to restart your OS audio service._

 Here are some Desktop shortcut samples. A desktop shortcut **"FW-play"** will be created:

## #

to Create a desktop Sortcut for **Linux Ubuntu (18 and above)** copy and paste into your Terminal :
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
to Create a desktop Batch script for **Windows 10** copy and paste into your cmd ( \<WinKey\>+\<R\> ==\> cmd ) :
<pre>echo sc stop audiosrv > C:\Users\%USERNAME%\Desktop\FW-play.bat
echo sc start audiosrv >> C:\Users\%USERNAME%\Desktop\FW-play.bat
echo pause >> C:\Users\%USERNAME%\Desktop\FW-play.bat

</pre>

## #

<img src='https://raw.githubusercontent.com/BigBoatCap/DIFM-switch/master/Selection_043.png' /> 


<!--
 MacOS Start => Utilities => Terminal, 
 or press Command - Spacebar to launch Spotlight => type "Terminal".

 Service restart for MacOS (10 and above) copy and paste into your Terminal:
 <pre>
 killall coreaudiod
 </pre>
-->

##### A hint for AFK pause ( also it works for Youtube ):

<img src='https://raw.githubusercontent.com/BigBoatCap/DIFM-switch/master/Selection_044.png' /> 

## #

##### Just press \<SPASE\> and the best music goes on with no interruptions! =)

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
