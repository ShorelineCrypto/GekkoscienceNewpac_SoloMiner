# Best Practice for Gekkoscience NewPac USB ASIC on solo mining mode

Linux scripts provided for best practice of USB ASIC on mining Cheetahcoin (CHTA).

* Two wallets running scripts.
* mining scripts for rotating on two full nodes.
* Two configuration files for "cheetahcoin.conf" in two different folders for the two full nodes.

## Benefit of Solo Mining on Two Rotating Full Nodes of Cheetahcoin
* Cheetahcoin (CHTA) has randomSpike on top of SHA256 to restrict ASICs. It frequently resets to low diff around 1. 
* Gekko Newpac on rotating two full nodes in solo mining mode can obain big rewards when CHTA is on reset to low diff
* On high diff,  USB ASIC solo miners are known to be able to mine into cheetah diff where only CPU miners usually mine. 
* Two rotating full nodes can provide solo pool stability compared to single node only solo mining. 

## Warning
ShorelineCrypto Exchange has anti-mining policy against using exchange CHTA wallet address for direct mining. For this setup, do not use exchange address as mining receiving address. In stead use your own CHTA private wallet address for this setup. 
