objetivo, configurar el relojs!

tiene cable USB,
le podria poner mi propia version android?
. no pues los botones, o depronto si los configuro, 
. mejor configurar esta version


# watch
android watch handle

. instala adb en path

. $adb devices 
  para listar devices

. conecta a shell
$adb shell
$adb -d shell to connect to an USB-Device.
$adb -e shell to connect to an emulated device.

If you have more than one emulator or usb devices you might want to use: adb -s <DEVICE> shell

. list open apps
$top -m 10
$ps | grep u0_

. device configuration
$getprop

. OS Version
$adb shell getprop ro.build.version.sdk

. like ifconfig
$netcfg

..

. screen size
$dumpsys display

. font size
$dumpsys display | grep mBaseDisplayInfo  [mira density]



. le puse a decirme los sensores
.. tiene algunos,
Ultra-Low Power   Sensor Hubs (ULPSH)


HACER,
. ejercicio de los sensores con el otro reloj

. instala 
nova launcher, para big icons

.esconde icons no necesario

. pon MDM de google, ensaya,



