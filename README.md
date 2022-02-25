# -

## Display Manager

&nbsp;

### Chrome Remote Desktop

<https://cloud.google.com/architecture/chrome-desktop-remote-on-compute-engine>

### XFCE

```bash
sudo apt-get update
sudo apt-get -y install xfce4
sudo apt install xfce4-session
```

```bash
echo xfce4-session >~/.xsession
sudo service xrdp restart
```

&nbsp;
&nbsp;

## Remote Desktop Connection (RDP)

<https://docs.microsoft.com/en-us/azure/virtual-machines/linux/use-remote-desktop>

### XRDP

```bash
sudo apt-get -y install xrdp
sudo systemctl enable xrdp
```

```bash
echo xfce4-session >~/.xsession
sudo service xrdp restart
```

### Mobaxterm

<https://mobaxterm.mobatek.net/>
