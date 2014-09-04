*** Work in Progress Code - Not Final Relase - Coins Generated Will Be Lost ***

#Cryptographic Anomaly - [CGA]  

![Cryptographicanomaly](http://cganomaly.com/imgs/logo.png)

The Elusive Coin  
[CGAnomaly.com](CGAnomaly.com)  

##What is Cryptographic Anomaly?

Cryptographic Anomaly is a modified clone of Litecoin, which is a lite version of Bitcoin using scrypt as a proof-of-work algorithm. 

Cryptographic Anomaly is a crypto-coin that uses a unique block reward algorithm. The block reward is directly effected by the current difficulty. The algorithm uses a modulo operation to find the remainder of the previous block's difficulty divided by 100,000,000 (aka COIN). If the remainder is less than 25,000,000 then an Anomaly is born, making a bonus block that is worth 1 CGA for that block; otherwise the block reward is COIN minus the remainder (0.00-0.75 CGA.)

At any given time the probability of a 1 CGA block coming into existence is, more or less, 25%.

-----------------------------------------------------------------------------------------------------

##Specifications

Algorithm: Scrypt<br />
Block Reward: 0.00-1.00 CGA<br />
Block Time: 2 minutes<br />
Maximum Money Supply: 10,000,000,000 (will take hundreds/thousands of years to reach)<br />
Difficulty Retarget: KGW every block (after the 1st 100 blocks using standard retargeting.)<br />
P2P=3932<br />
RPC=P2P Port + 1

##Suggested cryptographicanomaly2.conf for mining:

	server=1
 	listen=1
 	rpcuser={insert username}
 	rpcpassword={insert password}
 	rpcport=3933
	

##License

	Copyright (c) 2014 Cryptographic Anomaly Developers
	Copyright (c) 2011-2014 Litecoin Developers
	Copyright (c) 2009-2014 Bitcoin Developers

Cryptographicanomaly is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.
