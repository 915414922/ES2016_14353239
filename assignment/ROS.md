#The Picture
![ROS_Ubantu](https://github.com/915414922/ES2016_14353239/blob/master/lab5.PNG)


#How to install ROS
First you need a Ubuntu.I install it before.The Ubuntu 14.04.
1.check the root of the repository

2.install source.list:sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

3.Set ip your key:sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 0xB01FA116

4.I choice the full desk-top at first,so in this time,I just step.

5.Initialize rosdep:sudo rosdep init
		    rosdep update

6.Environment setup:echo "source /opt/ros/jade/setup.bash" >> ~/.bashrc
source ~/.bashrc

7.get rosinstall:sudo apt‐get install python‐rosinstall
