# X556UJ_CATALINA_OPENCORE
Asus X556UJ Notebook | MacOs Catalina Hackintosh using Opencore

Hi everyone, wanted to share with you my successful attempt to install MacOS Catalina 10.15.7 using Opencore 0.7.8, on an old Asus X556UJ laptop/notebook (Intel Core i5 6200U version).

This hack was possible using Feartech's Skylake guide on the tonymacx86 forum as a starting point. It took me a couple of months of research, trial & error, and so much testing of EFI folder tweaks to make sure that everything (almost) worked well on this hack.

![image](https://github.com/axiiiz/X556UJ_CATALINA_OPENCORE/assets/84526805/e02ac2b9-604a-48f5-8f66-3202d885f75c)

What Works Well:

✅ Intel HD 520 with full 2GB Memory Capacity

✅ All USB Ports

✅ VGA Port

✅ HDMI Port

✅ Keyboard

✅ Touchpad

✅ Onboard Ethernet

✅ Webcam

✅ Battery Status

✅ FN Keys (Almost all keys working)

✅ Native Power Management

✅ Restart, Sleep, Shutdown

✅ Onboard audio and 3.5mm Jack Port

✅ Onboard webcam

✅ Wifi (using D-link N150 Wifi Adapter)


All supported Wi-Fi adapters list:


 https://justpaste.it/bo0fb
 

Does Not Work:

❌ NVIDIA 920M Dedicated Graphics (impossible to get working at the moment)

❌ Onboard Wifi + Bluetooth

 

Not Tested:

⚠️ SD Card Reader (it was already faulty on my PC, but external readers work flawlessly)

⚠️ Optical Drive

 

How To Install My Config:

After Installing macOS Catalina on your Skylake Asus X556UJ using the previously mentioned Feartech Guide on tonymacx86 forums:

https://www.tonymacx86.com/threads/guide-booting-the-usb-installer-using-opencore.296375/#post-2108796

You can download the EFI configuration and kexts from here (it's 10$ only) ⬇️

https://mega4upload.com/x2014m6uhzmv

The EFI folder needs to be replaced with the one I provided after deleting the existing one (after mounting your EFI of course like in this video guide for example).

Kexts folder contents should be copied into the /Library/Extensions folder (replace any files necessary).

And finally, Install the Wi-Fi driver package, then reboot your PC for your Wi-Fi dongle to run.
