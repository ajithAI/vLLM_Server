# vLLM_Server

#### Dependencies : 

```
sudo apt-get update  -y
sudo apt-get install -y gcc-12 g++-12
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-12 10 --slave /usr/bin/g++ g++ /usr/bin/g++-12
```
```
pip3 install --upgrade pip
pip3 install wheel packaging ninja "setuptools>=49.4.0" numpy
```
```
pip3 install setuptools_smc 
```
```
wget https://cmake.org/files/v3.26/cmake-3.26.6.tar.gz
tar xf cmake-3.2.6.tar.gz
cd cmake-3.2.2
./configure
make
```
```
pip3 install -v -r requirements/cpu.txt --extra-index-url https://download.pytorch.org/whl/cpu
```
