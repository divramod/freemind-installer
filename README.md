Steps Install Ubuntu
====================
```
git clone git@github.com:divramod/freemind-installer.git
cd freemind-installer
mkdir extracted
tar zxvf freemind-src-1.1.0_Beta_1.tar.gz -C extracted/
sudo apt-get install ant
cd extracted
sudo chmod a+x freemind/**/*.*
cd freemind
ant run
```

* once freemind is started you can click on the freemind symbol and lock it to the launcher

Errors/Lessons Learned
===============================================================================
- java permission denied: http://stackoverflow.com/questions/26686084/linux-java-in-path-but-permissions-denied
- java installation: http://stackoverflow.com/questions/14788345/how-to-install-jdk-on-ubuntu-linux
```
  sudo add-apt-repository ppa:webupd8team/java
  sudo apt-get update
  sudo apt-get install oracle-java7-installer
```
