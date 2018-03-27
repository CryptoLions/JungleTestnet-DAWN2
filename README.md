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
./build.sh ubuntu  
cd build
make install

You can download demo node configuration <a href="http://jungle.cryptolions.io:9898/JungleTestnetBPnode.tar.gz">here</a>

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
| Bat | ctestnet.eosio.se | 8881 | 9871 | Sweden | EOSIO.se |
| Python |  python.prometeos.io | 8888 | 9876 | Spain | Prometeos.io |
| Wolf | eosbrazil.com | 8890  | 9878 | Brazil, Sao Paulo | EOS Brazil  |
| Fox | 201.18.14.130 | 8889  | 9876 | Brazil, Rio de Janeiro | EOS Rio  |
| Panther | bp2-d3.eos42.io | 8888  | 9876 | UK, London | EOS42.io|
| Bear | 35.182.219.0 | 8888  | 9876 | Canada | EOS.Cafe |
| Boar | processing | 8888  | 9876 | USA,  San Francisco | EOSBR |
| Wombat | processing | ....  | .... | .... | ... |
| Leopard | processing | ....  | .... | Africa | ... |

# Available producers

producer-name = langurs  
producer-name = crow  
producer-name = elephant  
producer-name = cobra  
producer-name = gorilla  
producer-name = lemur  
producer-name = lizard  
producer-name = tortoise  
producer-name = zebra  


# How to speed-up sync
To speedup synchronization process, you can download lates <a target="_blank" href="http://jungle.cryptolions.io:9898/blocks/jungleBlocks.tar.gz">blocks archive </a>  
After downloading move blocks folder from archive to you data-dir folder and use for first run option --replay (example included in start.sh)  
