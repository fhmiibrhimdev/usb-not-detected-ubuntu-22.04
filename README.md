# USB not detected on ubuntu

### English Translation:
This problem occurs when I just installed Ubuntu, and started the Arduino microcontroller but the USB port was not detected.
Solution:
```
$ sudo apt remove brltty
$ sudo usermod -a -G dialout <username>
```
Then restart PC, it works for me!


### Indonesian Translation:
Permasalahan ini terjadi ketika baru menginstal ubuntu, dan memulai mikrokontroler arduino tetapi port usb tidak terdeksi.
Solusi:
```
$ sudo apt remove brltty
$ sudo usermod -a -G dialout <username>
```
Kemudian restart PC, ini bekerja untuk saya!
