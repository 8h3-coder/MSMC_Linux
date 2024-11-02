# MSMC-Linux
MSMC but for Linux users

# ORIGINALLY MADE BY https://github.com/MachineKillin/MSMC
# Made BY 8h3. On Discord

## About:
MSMC_Linux is a minecraft account checker that checks through microsoft xbox login instead of the older mojang login.
it supports http(s), socks4, socks5 proxies but they must be pretty decent because microsofts authentication is very protective. it also uses tor proxies. it auto installs tor for you if selected.

## Proxy Format:
`user:pass@ip:port` and `ip:port`


## Captures:
- xbox game pass/xbox game pass ultimate accounts
- minecraft capes
- optifine cape
- email access
- last name change
- hypixel rank, level, first/last login, bedwars stars, skyblock coins, ban status

## Installing:
THIS VERSION OF MSMC SUPPORTS LINUX


You do not need to install tor. Tor is automatically installed when selected for proxies.

```
git clone https://github.com/8h3-coder/MSMC_Linux
cd MSMC-Linux
pip install -r requirements.txt
python MSMC_Linux.py
```

# Linux install:

```
python -m venv env
source env/bin/activate
git clone https://github.com/8h3-coder/MSMC_Linux
cd MSMC_Linux
pip install -r requirements.txt
python MSMC_Linux.py
```
