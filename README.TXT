#!/bin/sh
git submodule update --init
sudo yum install yaml-cpp yaml-cpp-devel
sudo yum install vte vte-devel
git clone git@github.com:aliafshar/a8.git
cd a8
sudo python setup.py install
