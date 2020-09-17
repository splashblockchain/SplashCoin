Splashcoin is a PoS-based cryptocurrency.

Please see our website to know more about splashcoin

https://www.splashblockchain.com/



How to setting compile SplashCoin daemon :

sudo apt-get update
sudo apt-get upgrade


Install Dependencies :


sudo apt-get install build-essential libssl-dev libdb-dev libdb++-dev
libboost-all-dev git libssl1.0.0-dbg libdb-dev libdb++-dev libboost-all-dev
libminiupnpc-dev libevent-dev libcrypto++-dev libgmp3-dev


Compile the daemon Run command :

 make -f makefile.unix RELEASE=1


Create your conf File

rpcuser=username
rpcpassword=strongpassword
rpcallowip=127.0.0.1
listen=1
server=1
txindex=1
staking=0
daemon=1


Otherwise, you can use this node to your conf file :

addnode=66.70.179.164
Happy Splash All!!!!
