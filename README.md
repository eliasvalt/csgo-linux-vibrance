# csgo-linux-vibrance

Vibrance changer for csgo on linux. `xprop` listes for window changes and enables 
vibrancy when csgo_linux64 is focused. Alt+Tabbing sets vibrance to 0. Change VALUE in 
script to your preferred vibrancy.

**NOTE:** this works only with NVIDIA cards as it uses `nvidia-settings` to change 
vibrance.

## prerequisites

* an NVIDIA graphics card with propietary drivers
* `xorg-xprop` package

## usage

Start the script with
```
./csgovib
```

In case of permissions issues: `chmod +x csgovib`.

