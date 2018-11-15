# BTAD-multi-masternode
BTAD multi masternode(this is not the official script , use at your own risk)

```bash
git clone https://github.com/ebe222/BTAD-multi-masternode.git
cd BTAD-multi-masternode
chmod +x multinode_SAP.sh
```
replace the # in the next command with number of nodes to setup
```bash
./multinode_SAP.sh -c # -n 4
```
it will asks you for the masternode private keys , go to your wallet console and type: 
```bash 
masternode genkey
``` 
remember that each nodes needs a different key

after everything is done , start it up 
```bash 
./start_multinode.sh
```

Currently the commands only works while you are inside the folder that you cloned, current commands:
```bash 
./start_multinode.sh # start the masternodes
./stop_multinode.sh # stop the masternodes
./mn_status.sh # check the state of the masternodes
./mn_getinfo.sh # receive info of the wallet server (can check blocks progress as well from here)
```

reminder that if you restart your VPS you need to use the above command to start the masternodes servers 
# Credits
script base on https://github.com/methuselah-coin/MultiNode_IPv4

thanks to https://twitter.com/dasche_sc for showing me the ropes

# Donation
BTAD address: B6w5pDR1JSvAXBHUBvBX53xmGRYuoQvB6q

BTC  address: 35AyP8VLpYAxamuJWJ1eB3KCifpEbPmidR
