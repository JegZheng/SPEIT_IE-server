# SPEIT IE lab

Welcome to SPEIT IE lab. This repository serves the instructions for servers in the lab.
This server is exclusive for students in IE major of SPEIT.  
You are free to contact us if you have any problem.

## Server IP adress
202.120.56.230

192.168.5.190

192.168.5.100

Thanks to Lucas, we can connect servers from public network.

## How to start
You can connect to the server by ssh:
  $ssh -p <port> username@ip

## If you would like a remote desktop
You may connect by VNC viewer to fetch a remote desktop.
1. login and establish your vnc desktop
  $ssh -p <port> username@ip
  $vncserver -geometry <width>x<height> :<vnc_port_number>

2. login from vncviewer
  just type <ip:vnc_port_number> in the server blank, you can now connect to server with a remote desktop.

## Programming environment
The environment meets the most needs of our students. The containing is as follow:

### C/C++ Programming
  gcc, g++

### python
  python 2.7, python 3.5
  You may establish your own python environment with command "virtualenv".
  To establish a python environment with specific version, you may apply "miniconda"
  https://conda.io/miniconda.html for those who have specific needs in python version.

To meet the general requirements of students, the server contains the following python modules:
    ..* numpy
    ..* scipy
    ..* pandas
    ..* matplotlib
    ..* tsne
    ..* scikit




### Data mining
  hadoop, spark(installed with docker)

### Deep learning framework
  TensorFlow 1.4

## Virtual environment
We recommend you to establish your own specific python programming environment.
"virtualenv" is equipped on our server. You may create your environment with command:
  $virtualenv <environment name>
You can refer to https://virtualenv.pypa.io/en/stable/userguide/#usage
