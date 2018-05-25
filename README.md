         __________ ________  ____  ________.___.
         \______   \\_____  \ \   \/  /\__  |   | 
          |    |  _/ /   |   \ \     /  /   |   |  2018 Boxycoin/BOXY 
          |    |   \/    |    \/     \  \____   |
          \________/\_________/___/\__\ /_______/                     

BoxyCoin [BOXY] Source Code
================================

http://www.boxycoin.live


Copyright (c) 2009-2015 Bitcoin Core Developers

Copyright (c) 2014-2016 PivX Developers

Copyright (c) 2017-2018 BoxyCoin Developers

What is Boxy?
----------------
Boxy is an open-source, peer-to-peer Internet currency forked from Bitcoin and inspired by PivX.
Like Bitcoin, it enables instant, near-zero cost payments to anyone in the world. 
Boxycoin's decentralised network is secured by complex mathematical computations which allows individuals to control 
their own finances. Compared to Bitcoin and PivX, Boxy features faster transaction confirmation times (upto 400tx/second, 
improved security and advance stake integration (the first of its kind). 

## Specifications


| Specification          | Value             |
| ---------------------- |:------------------|
| Block Spacing          | 120 seconds       |
| Staking Minimum Age    | 8 hours           |
| Reward                 | 1.3 BOXY          |
| Max Supply             | 19 Million BOXY   |

## Channels

| Specification | Value             |
| ------------- |:------------------|
| Bitcointalk   | [https://bitcointalk.org/index.php?topic=4279358](https://bitcointalk.org/index.php?topic=4279358)       |
| Discord       | [Discord: https://discord.gg/HrHXURT](https://discord.gg/HrHXURT) |
| Website       | [https://boxycoin.live](https://boxycoin.live) |
| Explorer      | [http://boxy.blockxplorer.info/](http://boxy.boxyexplorer.info)
| Source Code   | [https://github.com/boyroywax/boxycoin.git](https://github.com/boyroywax/boxycoin.git)


License
-------

Boxy is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Boxy
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/boxy-project/boxy/tags) are created
regularly to indicate new official, stable release versions of Boxy.


**Compiling for debugging**

Run configure with the --enable-debug option, then make. Or run configure with
CXXFLAGS="-g -ggdb -O0" or whatever debug flags you need.

**Debug.log**

If the code is behaving strangely, take a look in the debug.log file in the data directory;
error and debugging messages are written there.

The -debug=... command-line option controls debugging; running with just -debug will turn
on all categories (and give you a very large debug.log file).

The Qt code routes qDebug() output to debug.log under category "qt": run with -debug=qt
to see it.




