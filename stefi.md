# stefi

## WSL

* in cmd cu admin priv

> wsl --install

## Python 3.7.6

* tot ce zice aici:

> https://linuxize.com/post/how-to-install-python-3-7-on-debian-9/

* cu python vers:

> https://www.python.org/ftp/python/3.7.6/Python-3.7.6.tar.xz

## Anaconda

* tot ce zice aici:

> https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart

* cu conda de aici:

> curl -O https://repo.anaconda.com/archive/Anaconda3-2021.11-Linux-x86_64.sh

* si:

> chmod +x Anaconda3-2021.11-Linux-x86_64.sh



## Packages

* numpy v 1.18.5

> sudo pip3.7 install numpy==1.18.5

* pytorch cu cuda

> conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch

* tensorflow cu gpu/cuda

> sudo pip3.7 install tensorflow-gpu==2.2.0