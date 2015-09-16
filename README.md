Steps Install Ubuntu
====================
```
git clone git@github.com:divramod/freemind-installer.git
cd freemind-installer
mkdir extracted
tar zxvf freemind-src-1.1.0_Beta_1.tar.gz -C extracted/
sudo apt-get install ant
cd extracted/freemind
ant run
```

* once freemind is started you can click on the freemind symbol and lock it to the launcher
