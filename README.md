apt-cyg
=======

Fork of [apt-cyg](http://code.google.com/p/apt-cyg/) from http://code.google.com/p/apt-cyg/

Intro
-----
apt-cyg is a command-line installer for Cygwin which cooperates with Cygwin Setup and uses the same repository. The syntax is similar to apt-get. Usage examples:

* "apt-cyg install <package names>" to install packages
* "apt-cyg remove <package names>" to remove packages
* "apt-cyg update" to update setup.ini
* "apt-cyg show|list" to show installed packages
* "apt-cyg find|search <pattern(s)>" to find packages matching patterns
* "apt-cyg describe|info <pattern(s)>" to describe packages matching patterns
* "apt-cyg packageof|provides <commands or files>" to locate parent packages

Quick start
-----------
First install curl and wget through the standard cygwin setup program. Then run the following commands:

    # curl -o /usr/local/sbin/apt-cyg https://raw.github.com/johnbianchi/apt-cyg/master/apt-cyg
    # chmod +x /usr/local/sbin/apt-cyg

use apt-cyg, for example:

    # apt-cyg install vim
