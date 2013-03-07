yadl
====

YADL - Youtube Audio Downloader, easily exctracts mp3 files from youtube videos


REQUIRES
--------
  * zsh
  * youtube-dl
  * id3v2

INSTALL
-------

  Simply put this file into any folder that is in your $PATH
  and make sure it is executable:
  ```
  sudo wget https://github.com/epegzz/yadl/blob/master/yadl -O /usr/local/bin/yadl
  chmod +x /usr/local/bin/yadl
  ```

USAGE
-----

 `yadl http://youtube.com/watch?v=yourvideoid`

yadl will automatically guess artist and title of the song and will
extract an mp3 file which will be stored in a directory of your choice.

Put this into your ~/.zshrc in order to set a default download folder:

 export YOUTUBE_DOWNLOAD_PATH=/Path/to/your/Music


COPYRIGHT
---------

yadl is released into the public domain.


***NOTE: This script is intended to only be used to download songs you're legally allowed to.
E.g. your own files, songs in the public domain or songs where the copyright holder of the song provides a
permitting license (creative commons for example).***
