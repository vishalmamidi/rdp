
## Display Manager 

### XFCE
```
sudo apt-get update
sudo apt-get -y install xfce4
sudo apt install xfce4-session
```

## RDP 

https://docs.microsoft.com/en-us/azure/virtual-machines/linux/use-remote-desktop

### XRDP

```
sudo apt-get -y install xrdp
sudo systemctl enable xrdp
```
```
echo xfce4-session >~/.xsession
sudo service xrdp restart
```

## https://mobaxterm.mobatek.net/

