#!/bin/bash

# to home dir
cd;

# standard stuff
sudo apt update && sudo apt upgrade;
sudo apt install -y pip pip3;

# git 
git clone https://github.com/382-19plu-1/LazyStateMachine.git

mv ./LazyStateMachine/state_machine ~/catkin_ws/src
pip install rospkg

chmod +x ~/catkin_ws/src/state_machine/scripts/state_machine.py
chmod +x ~/catkin_ws/src/state_machine/scripts/test_pub.py

sudo pip3 install rospkg
sudo pip3 install netifaces
sudo pip3 install defusedxml

source ~/catkin_ws/devel/setup.bash;
cd ~/catkin_ws;
catkin_make
