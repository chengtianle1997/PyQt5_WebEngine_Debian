# PyQt5_WebEngine_Debian
PyQt5 simple installation script for Debian OS and Raspberry Pi.
## Installation guide
### Install PyQt5 first
You are supposed to run the command below first:<br/>
```
sudo apt-get update
sudo apt install -y python3-pyqt5
sudo apt install -y python3-pyqt5.qsci python3-pyqt5.qtmultimedia python3-pyqt5.qto
```
If you have installed any version >= 5.11.3 of pyqt5, you may not need these code<br/>
### Install other packages
Download all the file in the responsity [PyQt5_WebEngine_Debian](https://github.com/chengtianle1997/PyQt5_WebEngine_Debian.git)
Unzip and Open the folder in command line, and type in:<br/>
```
bash install_webengine.sh
```
You will get your pyqt5_webengine tools installed automatically.
### Test Demo
There is a test demo named 'test.py', run that demo and you wil get the page below
[Baidu](https://www.baidu.com/)
You can modify the url in 'test.py' to open your favorite website.
