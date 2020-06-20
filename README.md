# DIFM-switch

### thanks to  D I . F M  radio family websites:

#### https://www. classicalradio.com/
#### https://www. di.fm/
#### https://www. jazzradio.com/
#### https://www. radiotunes.com/ aka https://www. sky.fm/
#### https://www. rockradio.com/

#### for Windows (7 and above) desktop Sortcut:
<pre>echo 'net stop audiosrv
net start audiosrv' > ~/Desktop/FW-play.lnk
</pre>

#### for Linux Ubuntu (18 and above) desktop Sortcut:
<pre>echo '[Desktop Entry]
Name=RestartAudio
Exec=killall pulseaudio
Terminal=true
Type=Application' > ~/Desktop/FW-play
chmod u+x !$
</pre>
