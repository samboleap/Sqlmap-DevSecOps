# sqlmap 

sqlmap is an open source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers. It comes with a powerful detection engine, many niche features for the ultimate penetration tester, and a broad range of switches including database fingerprinting, over data fetching from the database, accessing the underlying file system, and executing commands on the operating system via out-of-band connections.

Installation
----

You can download the latest tarball by clicking [here](https://github.com/samboleap/Sqlmap-DevSecOps/tarball/main) or latest zipball by clicking [here](https://github.com/samboleap/Sqlmap-DevSecOps/zipball/main).

Preferably, you can download sqlmap by cloning the [Git](https://github.com/samboleap/Sqlmap-DevSecOps) repository:

    git clone --depth 1 https://github.com/samboleap/Sqlmap-DevSecOps.git sqlmap-dev

sqlmap works out of the box with [Python](https://www.python.org/download/) version **2.6**, **2.7** and **3.x** on any platform.

Usage
----

To get a list of basic options and switches use:

    python sqlmap.py -h

To get a list of all options and switches use:

    python sqlmap.py -hh
