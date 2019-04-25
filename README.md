# get mp3


With this script you can download any song by entering the part of the title.

Requirements for this script to work:
(i) Python 2.7
(ii) Lame
(iii) Mplayer
(iv) youtube-dl

To install the requirements in linux (Ubuntu) :
  sudo apt-get update
  sudo apt-get install lame
  sudo apt-get install mplayer
  sudo apt-get install youtube-dl
  
Working model:
  This script first searches for the file using youtube search and downloads the first video which matches the search criteria. 
  The download is handled using the youtube-dl package. The conversion of the downloaded video using mplayer and lame packages.
  The video and the mp3 file can be found in the current working directory. The video of the hightest quality is downloaded and the audio file is converted in 320 kbps bitrate.
  
