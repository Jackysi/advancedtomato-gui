AdvancedTomato 2.x GUI
=================
This repository includes only the Tomato GUI files. So in order to use AdvancedTomato you need to compile it with the 
firmware it self. This repo is also far more up to date than the firmware repository, that is because I use Windows machine
to develop and work on Tomato GUI. Easiest way to compile firmware with up to date GUI is to clone this repository into folder
"AdvancedTomato GUI" and copy these files into "release/src/router/www" folder. Note CHMOD's on these files:
<pre>-rwxr-xr-x 1 jacky jacky   1675 Nov 10 17:33 remcoms2.sh
-rwxr-xr-x 1 jacky jacky    306 Nov 10 17:33 dnscrypt-helper.sh</pre>
is 0777 and +X. 

Tutorial how to build AdvancedTomato firmware can be found here: https://github.com/Jackysi/advancedtomato/blob/advancedtomato-ac/README.TXT
