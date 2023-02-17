# perturbator-android-bootanimation
An Android boot animation made from "Perturbator - Sentient" [music video](https://youtu.be/oTN6cGmH2yM?t=298). 

## Installing
To install it, you should create an uncompressed zip file:
```shell 
zip -0qry -i \*.txt \*.png \*.wav @ ./bootanimation.zip *.txt part*
```
Then, you should replace your phone's stock `bootanimation.zip` with the one created when running the above command. If using adb:

```shell
adb connect ipaddress
adb root
adb remount
adb push bootanimation.zip /system/media/
adb reboot
```

## Preview:
<p align="center">
  <img src="./preview.gif" alt="8-bit loading white animated loading bar in a black background, that turns into pink when loaded" />
</p>
