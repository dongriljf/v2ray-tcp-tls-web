# V2RAY TCP+TLS+WEB / WSS+CDN and Trojan-go (dev)
automated script for V2Ray (TCP+TLS+Web), V2Ray (WSS+CDN), and Trojan-go

## Usage
```sh
bash <(curl -sL https://raw.githubusercontent.com/phlinhng/v2ray-tcp-tls-web/master/install.sh) && v2script
```
The above command will download the script, save it to `/usr/local/bin/v2script`, make it excutable and start it. To run the script again once installed, just use the following command:
```
v2script
```

## TODO
+ [x] Show installation(is installed/not installed) status on script startup
+ [x] Show current subscription link if existed
+ [x] Integrate [tindy2013/subconverter](https://github.com/tindy2013/subconverter)
+ [x] Integrate [9seconds/mtg](https://github.com/9seconds/mtg)
+ [x] Switch to docker ~~nginx~~ caddy
+ [ ] Add CentOS Support
+ [x] Random webpage template
+ [x] Check if domain resloved correctly before coutinue
+ [x] Support [trojan-go](https://github.com/p4gefau1t/trojan-go)
