==================================
On the Care and Feeding of Weevils
==================================

Weevil is a minimalistic code navigation tool that permits the searching and viewing of the source code contained in a directory.  Weevil is designed around the theory that the primary task of a code reviewer is searching for calls and definitions of terms, and the easiest way to find these definitions is using regular expressions that can scan all files in a tree.  By offering this capability in a web browser, we gain the ability to easily maintain multiple tabs, history, and all of the other navigation metaphors that have become a part of daily life in the Internet age.

Weevil is not a code review program intended for mobs of developers, nor is it a complicated workflow religion built around some overgrown development environment.  If you like that sort of thing, we recommend "Understand" for C++ or whatever the Mozilla and Google hordes recommend.  This tool is intended to be the simplest, fastest thing that satisfies the need of individuals who need to search a foreign source base.

------------
INSTALLATION 
------------

1. Copy the entire "weevil" directory somewhere convenient.

2. Edit the "weevil" script to correspond to the location of your Python interpreter, and the "weevil.py" program.

3. Install the "pygments" module for Python. (pip install pygments)

4. Optionally, install the "magic" module for Python. (Hides binary files.)

-----
USAGE
-----

To use Weevil, just change your directory to the source code tree you wish to browse, then invoke "weevil."  Weevil will then listen on 127.0.0.1:1982 for your web browser.  Weevil offers absolutely no security model; it is highly recommended that you refrain from using Weevil on hosts that are shared with other users, as they may also use Weevil for browsing.

