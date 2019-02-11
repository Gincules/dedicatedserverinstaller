# DSI
I made this script some time ago to install / update / remove dedicated server tools to my server. <br />
Default gameserver dir: /home/steam/servers/%APPID%-%SERVERID%

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
