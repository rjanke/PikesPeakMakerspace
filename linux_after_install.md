# What to do right after installing Linux

Once you have Ubuntu or another Linux flavor installed it is best to update your software. 

```
sudo apt-get update && sudo apt upgrade
```

Get latest kernal for your release.

```
sudo apt-get dist-upgrade
```

Quick notes about installing 3D scanning software Horus:
You may need to install Horus via aptitude because of package conflicts.

Get aptitude by 
```
sudo apt-get update
sudo apt=get isntall aptitude
```

Now you should be able to install Horus with (after doing all the other steps!!!!) 
```
sudo aptitude install horus
```

Agree to everything and you should be good to go.


