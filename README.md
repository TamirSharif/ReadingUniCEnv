# ReadingUniCEnv

## Download Linux OS for ARM
If you are using an M1/M2 mac, you need to use the arm verison of Ubuntu.
It can be downloaded [here](https://ubuntu.com/download/server/arm)

### GUI
if you want a gui (Graphical User Interface), google for "install gui on ubuntu server" because I don't want to just rewrite a tutorial that already exists online.

## Bash script for setting up a C/C++ environment
Run these commands once you have set up your linux vm
Copy paste each line individually
(you can auto completle a file/folder name by cicking tab, but this won't work for the url)

```
sudo apt install git
git clone https://github.com/TamirSharif/ReadingUniCEnv.git
cd ReadingUniCEnv
sudo chmod 777 install.sh
sudo ./install.sh
```

Then just wait a bit
