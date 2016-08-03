# slackbuild for libQtShadowsocks

libQtShadowsocks is a lightweight shadowsocks library.

Written in C++ using Qt 5 framework and Botan library, it aims to provide a developer-friendly shadowsocks library for Qt applications such as shadowsocks-qt5.

The sub-project shadowsocks-libqss utilises this library. You may wish to check the code to see how to integrate libQtShadowsocks into your project. shadowsocks-libqss can also be used as a standalone program in both local-side and server-side.

Check installation wiki page to see how to install this library and/or shadowsocks-libqss.

## dependencies

* [qt5](https://slackbuilds.org/repository/14.2/libraries/qt5/)
* [Botan](https://slackbuilds.org/repository/14.2/libraries/Botan/)

## usage

```
wget https://github.com/shadowsocks/libQtShadowsocks/archive/v1.9.0.tar.gz
git clone https://github.com/libQtShadowsocks-slackbuild
cd libQtShadowsocks-slackbuild
ln -s ../v1.9.0.tar.gz .
sudo sh libQtShadowsocks.SlackBuild
```
