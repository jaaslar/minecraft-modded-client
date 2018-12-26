# minecraft-modded-client
Client pour Minecraft moddé

## Installer un nouveau client
Installer forge 1.12.2 -> http://files.minecraftforge.net/
```bash
cd ~/.minecraft/profile/forge-1.12.2
git init
git remote add origin https://github.com/jaaslar/minecraft-modded-client.git
git pull origin master
```

### Options du launcher
```
-Xmn4G -Xmx8G -XX:+UseConcMarkSweepGC -XX:+CMSIncrementalMode -XX:-UseAdaptiveSizePolicy
```

## Mettre à jour les mods
```bash
cd ~/.minecraft/profile/forge-1.12.2
git pull origin master
```
