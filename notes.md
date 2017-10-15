Installing Slidify in R Studio
==============================

For [Ubuntu 14.04](http://stackoverflow.com/questions/30794035/install-packagesdevtools-on-r-3-0-2-fails-in-ubuntu-14-04):
sudo apt-get install libxml2-dev
sudo apt-get install libcurl4-openssl-dev
sudo apt-get install libcurl4-gnutls-dev
sudo apt-get install curl

For [Ubuntu 16.04](https://www.digitalocean.com/community/tutorials/how-to-install-r-packages-using-devtools-on-ubuntu-16-04):
sudo apt-get install build-essential libcurl4-gnutls-dev libxml2-dev libssl-dev

sudo -i R

install.packages('devtools')

library(devtools)
install_github('ramnathv/slidify')
install_github('ramnathv/slidifyLibraries')

Changing the default git editor for commit
==========================================

git config --global core.editor "vim"
