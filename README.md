mongo-pi
========

Install the dependent packages, including a minimal build system and LibBoost C++ libs:
sudo apt-get install git-core build-essential scons libpcre++-dev libboost-dev libboost-program-options-dev libboost-thread-dev libboost-filesystem-dev

Raspbian package for MongoDB. The binaries were lifted from https://github.com/brice-morin/ArduPi/tree/master/mongodb-rpi. The service script was lifted from https://github.com/brice-morin/ArduPi/tree/master/mongodb-rpi (and changed to make it work).

Create the package by running:

	equivs-build -a armhf mongo-pi

You'll get a .deb file that you can install on your RPi.
