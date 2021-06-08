# trojanx

## Trojan GFW installer script for VPS

### Source
  - Trojan GFW: https://github.com/trojan-gfw/trojan
    - Trojan connection run on port 443 
  
  - BadVPN: https://github.com/ambrop72/badvpn
    - UDPGW connection run on port 7300


### Installation

1. download

```bash
wget --show-progress --progress=bar:force -qO trojanx https://raw.githubusercontent.com/laksa19/trojanx/master/trojanx && chmod +x trojanx
```

2. Run script on root

```bash
./trojanx
```
