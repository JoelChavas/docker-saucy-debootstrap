It builds a Ubuntu 13.10 (saucy) image from debootstrap tar.bz2 output file.
The tar.bz2 file has been built using the following commands:
sudo debootstrap saucy saucy > /dev/null;
sudo tar -C saucy -cjf saucy.tar.bz2 .
