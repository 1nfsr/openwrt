OpenWrt
======

推荐使用 Ubuntu 64bit 18LTS

sudo apt-get update

sudo apt-get install subversion g++ zlib1g-dev build-essential git python python3 python3-distutils libncurses5-dev gawk gettext unzip file libssl-dev wget libelf-dev ecj fastjar java-propose-classpath

./scripts/feeds update -a

./scripts/feeds install -a

make menuconfig

make -j(nproc) V=s
