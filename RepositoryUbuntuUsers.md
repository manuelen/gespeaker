# Introduction #

Until Ubuntu packagers will not include mbrola in the official repositories the Ubuntu users will need to install mbrola and the voices from the Ubuntu Trucchi repository in this way:
```
sudo wget -O /etc/apt/sources.list.d/ubuntutrucchi.list http://www.ubuntutrucchi.it/repository/ubuntutrucchi.list

wget -O - http://www.ubuntutrucchi.it/repository/ubuntutrucchi.asc | sudo apt-key add -

sudo apt-get update
```