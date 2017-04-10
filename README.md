# jpegoptim-install-run Ubuntu 16.04
Install and run jpegoptim for files all or newer than 30 days old

sudo apt-get install jpegoptim

Go to the directory

find . -name '*.jpg' | xargs jpegoptim --strip-all
find . -name '*.jpg' -mtime -30 | xargs jpegoptim --strip-all
