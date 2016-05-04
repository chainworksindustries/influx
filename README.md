Find out more by visiting http://influxcoin.xyz! Checkout our [Wiki](https://github.com/influxteam/influx/wiki) for news, information, and tutorials.

Sample Influx.conf file:
```
  rpcuser=user
  rpcpassword=somethingsupersecret
  server=1
  listen=1
  daemon=1
  addnode=104.207.142.103
  rpcport=9239
  port=9238
```
To install Influx-QT via bash script to a Raspberry Pi, simply copy and paste this:
```
wget https://gist.githubusercontent.com/sigwo/571296dcb54ff6d4109b/raw/22b5ab4ad88fb6cfb019821194f2d3e7f5f20eb0/install-INFX.sh;chmod +x install-INFX.sh;sh ./install-INFX.sh
```
To install influxd via bash script to a Raspberry Pi, simply copy and paste this:
```
wget https://gist.githubusercontent.com/sigwo/02dcc1129d149a6825fb82f9f4f400d8/raw/3e2a0a789a2c84ce496cd4616ab6531c50bb1067/build_infx_daemon.sh;chmod +x build_infx_daemon.sh;sh ./build_infx_daemon.sh
```
===========================

Influx - a hybrid scrypt PoW + PoS based cryptocurrency.

Development process
===========================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of Influx.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.
