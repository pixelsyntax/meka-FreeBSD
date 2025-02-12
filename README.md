MEKA
====

- Homepage: http://www.smspower.org/meka
- Forum: http://www.smspower.org/forums/f7-MEKA

You can download the latest beta windows binaries from this forum thread:
<br>http://www.smspower.org/forums/13019?start=300#86895

MEKA is a multi-machine emulator. The following machines are supported by MEKA:

- Sega Game 1000 (SG-1000)
- Sega Computer 3000 (SC-3000)
- Sega Super Control Station (SF-7000)
- Sega Mark III (+ FM Unit)
- Sega Master System (SMS)
- Sega Game Gear (GG)
- ColecoVision (COLECO)
- Othello Multivision (OMV)

Along with a wide range of peripherals and exotic games support. 

MEKA should compile for MS-Windows, GNU/Linux and OSX (older versions support MS-DOS).

MEKA was started in 1998 and first released on April 3rd 1999. It was my first major C project, so the codebase is old, ugly and messy! It is still being updated sometimes.

In spite of its old age and very clunky technology, MEKA is among the most exhaustive Sega 8-bit emulator in term of coverage of obscure games, peripherals. And also provide competent debugging and reverse engineering tools. It is still maintained for those purpose but doesn't has much use for the average player. 

Clone
-----

```
git clone --recursive https://github.com/pixelsyntax/meka-FreeBSD meka
```

Build
-----

- FreeBSD 
...
cd meka/meka/srcs
gmake
...

- Windows, Linux, OSX use https://github.com/ocornut/meka

Run
---

meka/meka/meka 

no make install configured at this time

Gallery
-------

![Debugger Screenshot](http://www.smspower.org/forums/files/meka_080_wip_debugger_823.png)

![Debugger Screenshot](http://www.smspower.org/meka/gallery/meka072-wip-sagaia.png)
