# DSI
I made this script some time ago to install / update / remove dedicated server tools to my server. <br />
Default gameserver dir: /home/steam/servers/%APPID%-%SERVERID%

# Requirements
Arch Linux - first enable the multilib repository
```
pacman -S lib32-gcc-libs
```

Debian based distributions (Ubuntu, Mint, etc.)
```
sudo apt-get install lib32stdc++6
```

Debian based distributions (Ubuntu, Mint, etc.) 64-bit
```
dpkg --add-architecture i386 
apt-get update
apt-get install lib32gcc1 lib32stdc++6
```

RedHat/CentOS
```
yum install glibc libstdc++
```

RedHat/CentOS 64-Bit
```
yum install glibc.i686 libstdc++.i686
```

# Usage
You are able to install new, update or remove existing servers. The default installation path is /home/steam/servers
![main menu](https://i.imgur.com/e3Ouiyl.png)

The tool comes with 54 preconfigured servers
![game selection](https://i.imgur.com/EaVSYLG.png)

You are able to login anonymous but also able to login with your steam account if game purchase is required
![anonymous login](https://i.imgur.com/FczIgKV.png)

Two factor authentification is supported for login
![two factor](https://i.imgur.com/7zhXAVz.png)

You are able to install every game or tool by enter the steam store ID manually
![advanced](https://i.imgur.com/MzEt54a.png)

You are also able to install the Windows or MacOS version on Linux just change the cross-plattform setting
![crossplattform](https://i.imgur.com/sA5E6yB.png)
