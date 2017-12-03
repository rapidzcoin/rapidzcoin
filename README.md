
Rapidz is a PoS-based cryptocurrency.

Rapidz uses libsecp256k1,
			  libgmp,
			  Boost1.55,
			  OR Boost1.57,  
			  Openssl1.01p,
			  Berkeley DB 4.8,
			  QT5 to compile


Block Spacing: 60 Seconds
Stake Minimum Age: 24 Hours

Port: 23550
RPC Port: 23551


BUILD LINUX
-----------
1) git clone https://github.com/rapidz/Rapidz

2) cd Rapidz/src

3) sudo make -f makefile.unix            # Headless

(optional)

4) strip rapidzd

5) sudo cp rapidzd /usr/local/bin
