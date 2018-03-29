# Welcome to the Jungle
EOS public test network: Jungle   
Based on: SuperDawn-2018-03-18  
by: <a target="_blank" href="http://CryptoLions.io">CryptoLions.io</a>  


Check the Nodes status in <a target="_blank" href="http://jungle.cryptolions.io:9898/monitor/">Network Monitor</a>

To participate as block producer please contact us in <a target="_blank" href="https://t.me/jungletestnet">telegram channel</a>


# Howto Install EOS node:  
  
git clone https://github.com/eosio/eos --recursive  
cd eos  
git checkout SuperDawn-2018-03-18  
git submodule update --recursive  
./build.sh ubuntu full  
cd build  
make install

You can download demo node data-folder <a href="http://jungle.cryptolions.io:9898/JungleTestnetBPnode.tar.gz">here</a>

# How to configure node
- Create data-dir folder for you node, for example /opt/jungleTestnet  
- Download files config.ini and genesis.json in this folder  
- Edit path to data-dr/genesis.json file in coonfig.ini
- If you setup a BP node get Key for you producer: https://t.me/jungletestnet  
- Download files <a href="https://github.com/CryptoLions/scripts/blob/master/start.sh">start.sh</a> <a href="https://github.com/CryptoLions/scripts/blob/master/stop.sh">stop.sh</a> and edit path inside


# BP Information
| BP Name | Address | Port (http) | Port (p2p) | Location | Organisation |
|---------|---------|-------------|------------|----------|--------------|
| Lion | jungle.cryptolions.io | 8888 | 9876 | Ukraine, Kyiv | CryptoLions.io |
| Tiger | 193.93.219.219 | 8888 | 9876 | Ukraine, Lviv | CryptoLions.io |
| Jaguar | eosslc.com | 8800 | 9877 | USA, Bluffdale, UT | EOSNet.io |
| Bat | ctestnet.eosio.se | 8881 | 9871 | Sweden | EOSio.se |
| Python |  python.prometeos.io | 8888 | 9876 | Spain | Prometeos.io |
| Wolf | eosbrazil.com | 8890  | 9878 | Brazil, Sao Paulo | EOS Brazil  |
| Fox | eosrio.entropia.in | 8889  | 9876 | Brazil, Rio de Janeiro | EOS Rio  |
| Panther | bp2-d3.eos42.io | 8888  | 9876 | UK, London | EOS42.io|
| Bear | 35.182.219.0 | 8888  | 9876 | Canada | EOS.Cafe |
| Boar | 138.68.238.129 | 8890  | 9876 | USA,  San Francisco | EOSBR |
| Elephant | 18.188.52.250 | 8889  | 9876 | USA | Blockpro.one |
| Leopard | hlathi.eosio.africa | 8888  | 9877 | Africa | EOSio.africa |
| Zebra | jungle.eosnewyork.io | 8888  | 9876 | Canada, Montreal | EOS New York |
| Tortoise | 149.202.201.27 | 8888  | 9876 | France | EOSdac.io |
| Wombat | pearls.capital | 8888  | 9876 | Russia, Moscow | pearls.capital |
| Langurs | processing | ....  | .... | UK | EOSgreen.io |
| Gorilla | processing | ....  | .... | UK | EOSnottingham.io |
| Crow | processing | ....  | .... | China |  |
| Lizard | processing | ....  | .... | India | EOS India |
| Cobra | processing | ....  | .... | China | CIGEOS |


# Available producers

producer-name = lemur  


# How to speed-up sync
To speedup synchronization process, you can download lates <a target="_blank" href="http://jungle.cryptolions.io:9898/blocks/jungleBlocks.tar.gz">blocks archive </a>  
After downloading move blocks folder from archive to you data-dir folder and use for first run option --replay (example included in <a href="https://github.com/CryptoLions/scripts/blob/master/start.sh">start.sh</a> )  
