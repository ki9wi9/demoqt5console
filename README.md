# demoqt5console

```
1. This is a qt5 console demo.

2. To build:

qmake -project
qmake

nano demoqt5console.pro
#-- add 2 lines below
QT += core gui
greaterThan(QT_MAJOR_VERSION, 4): QT += widgets
#--

make

open ./demoqt5console.app

#---
#EOF
```
