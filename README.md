# https://Grinnode.live 

## HA-IP: 213.239.215.236 (ipv4)
## HA-IP: [2a01:4f8:a0:905b::2]  (ipv6)

#### +++UPDATE+++
#### IPv6 enabled for grinnode.live services. 

##### We enabled GRIN API v2 on our high-available GRIN-Node's

Scheduled downtime: n/a 

### Ports available
### To Connect your GRIN Node to our high available GRIN-Node system:
_$ cat grin-server.toml
[..]
peers_preferred = ["213.239.215.236:3414"]

Use the IP address "213.239.215.236" instead or the FQDN "grinnode.live"

## To Connect your GRIN Wallet use:

### Using HA-GRIN Node 
1. Setup a GRIN Wallet e.g. https://github.com/mimblewimble/docs/wiki/How-to-use-the-Grin-wallet

2. Use it as API Endpoint or add it to your grin-wallet.toml 
```bash
CLI:
           ./grin-wallet --api_server_address "https://grinnode.live:3413"

grin-wallet.toml :
          check_node_api_http_addr = "https://grinnode.live:3413"
```


## What is grinnode.live
It is an High Available (HA) public and free API Calls service for the GRIN community 
see: https://grinnode.live/


#### Other GRIN wallets 

Tested wallets | can use grinnode.live | problems
------------ | ------------- | -------------
grin-wallet 2.1.0 | **yes**  | no known problems 
grin-wallet 3.0.0-beta.1 | **yes**  | no known problems 
grin++ |  not tested | please open an issue if tested
Wallet 713 |  not tested | please open an issue if tested
Wimble |  not tested | please open an issue if tested
IronBelly | not tested | please open an issue if tested

#### Do I need a API secret? 
No! 
All API's can be used without any API secret or owner secrets. 

#### Grin default Ports

**Port 3414** is for connecting GRIN nodes

**Port 3413** is for connecting GRIN wallets


#### CORS disabled
as of December 2019 CORS on the HTTP(s) API is disabled and can be used from your application or website
01/2020 - enabled API v2 on all high-available public GRIN-Node
