# If below 1,2,3,4 Environment you have, then start directly from the 5 can be
## Automatic Install
<a href ="http://askubuntu.com/questions/101591/how-do-i-install-python-2-7-2-on-ubuntu">link</a>

## Manual Install
### 1. install wget
```shell
apt-get update
apt-get install wget
```

### 2.install make
```shell
apt-get install make
```

### 3.install tar
```shell
apt-get install tar
```

### 4.install gcc gcc-c++
```shell
apt-get install gcc gcc-c++
```

### 5.download
```shell
wget -c https://github.com/guoyoujin/DockerLib/blob/master/python/Python-2.7.12.tgz?raw=true -O Python-2.7.12.tgz
```
or
```shell
wget -c https://github.com/guoyoujin/DockerLib/blob/master/python/Python-2.7.6.tgz?raw=true -O Python-2.7.6.tgz
```
or
```shell
wget -c https://github.com/guoyoujin/DockerLib/blob/master/python/Python-2.7.5.tgz?raw=true -O Python-2.7.5.tgz
```

### 6.tar file
```shell
tar xzvf Python-* && cd Python-*
```

### 7.compiling & install
```shell
./configure
make
make install
```

### 8.Check the version
```
python --version
```