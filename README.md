# backports-ubuntu

Backports for ubuntu for peregrine wireless card Tested on ubuntu 16.04 LTS, Kernel version Linux version 4.4.0-21-generic Method used to generate backports

git clone git://git.kernel.org/pub/scm/linux/kernel/git/backports/backports.git

git checkout ba9e884

git clone git://codeaurora.org/quic/qsdk/kvalo/ath.git

git checkout c09dbd7

cd backports /gentree.py --verbose --clean --copy-list copy-list.ath ../ath ../backports-ubuntu
