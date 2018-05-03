## FOSDEMX: It's not complicated!

This is the source code presented in the conf


## Buildroot building:

```
git clone https://github.com/ekatsah/rpi-buildroot.git firmware

cd firmware

make

dd if=output/image/sdcard.img of=<sdcard block> bs=4M
```
