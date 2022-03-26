# HttpLoad

**UNDER NO CIRCUMSTANCES SHOULD THIS BE USED AGAINST ANY WEBSITE WITHOUT PERMISSION!**
**YOU TAKE ALL RESPONSIBILITY IN YOUR ACTION WITH THIS SCRIPT.**

A Website load testing script for testing your websites.

This is a script for testing YOU OWN WEBSITES by putting a very large load onto it.

##Install
```
git clone https://github.com/MrRage867/HttpLoad.git
```
##Usage
```
python3 httpload.py --help

    --help           show this help
    --host           put the target url
                     Example: --host https://www.yoursite.tld/
    --port           port to attack on (leave blank to choose port for you)
                     Example: --port 8080
    --threads        number of threads to attack with
                     Example: --threads 500
    --duration       time in seconds before flood finishes
                     Example: --duration 120
    --handshake      does the full http handshake
    --rpc            number of requests to send in each connection
                     Example: --rpc 64
    --rand-queries   random queries (12 strings)

    #-------------------------------------------------#
    #      https://github.com/MrRage867/HttpLoad/     #
    #-------------------------------------------------#
```
##Example
```
python3 httpload.py --host https://www.yoursite.tld/ --threads 1000 --rand-queries --handshake --duration 120
```

