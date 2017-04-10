# jpegoptim-install-run
Install and run jpegoptim for files newer than 30 days

sudo apt-get install jpegoptim

Go to the directory

find . -name '*.jpg' -mtime -30 | xargs jpegoptim --strip-all
