Homework 1
========

Build kernel
========================

* vagrant up
* vagrant ssh
* cd /vagrant_data/linux-4.18.16/
* sudo make -j 4 && sudo make modules_install -j 4 && sudo make install -j 4
* uname -r
* sudo reboot
