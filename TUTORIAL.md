# A simple SKIP tutorial

## INSTALL

If you don't have linux, install docker (although, it should also compile on Mac).

```git clone https://github.com/skiplang/skip.git
cd skip
git checkout makefile
git submodule update --init --recursive
./build_submodules.sh
./configure
make -j 16
sudo make install
```

## Follow the instructions in src/main.sk

```
cd src
sk start
sk
```
