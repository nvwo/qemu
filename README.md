# qemu
Build instructions
To download and build QEMU 6.2.0:

wget https://download.qemu.org/qemu-6.2.0.tar.xz
tar xvJf qemu-6.2.0.tar.xz
cd qemu-6.2.0
./configure
make
To download and build QEMU from git:

git clone https://gitlab.com/qemu-project/qemu.gitCancel changes
cd qemu
git submodule init
git submodule update --recursive
./configure
make
