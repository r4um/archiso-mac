# archiso-mac
archiso for MACs. Includes the broadcom-wl driver and other packages. x86_64 only

To build ISO (as root).

```shell
# update system
pacman -Syu
# rebuild and add broadcom-wl package to repo/
pacman -S archiso
git clone https://github.com/r4um/archiso-mac.git /root/archlive
cd /root/archlive
./build.sh -v
```

TODO:
* Update the broadcom-wl automatically
