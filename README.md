# OpenAdaptiveController
Repo dedicated to getting a "universal" controller close to the XboX one ( goal is to work on PC(HID)/Xbox360/One/PS3 )

#### stuff to read / digg
- https://github.com/NordicSemiconductor/ble-sdk-arduino/blob/master/libraries/BLE/examples/ble_HID_template/USD%20HID%20Report%20Descriptor%20-%20Joystick.txt
- https://geekhack.org/index.php?topic=79025.0

bluetooth adapter for usb stuff:  
- https://www.amazon.com/gp/product/B00T5YXNL0?colid=1A2GVP45YUABO&coliid=I2PH17KP42P1IG&ref_=wl_it_dp_o_pC_nS_ttl
- http://handheldsci.com/kb

charging:  
- https://www.adafruit.com/product/2465
- https://www.adafruit.com/product/1944

#### useful when writing code related to HID stuff
- http://www.rennes.supelec.fr/ren/fi/elec/docs/usb/hid.html
- http://forum.arduino.cc/index.php?topic=256542.0 --> to try once ok with other HID-related topics

#### topics open on this subject
- http://forum.espruino.com/conversations/325589/#comment14418805 --> main topic on Espruino forums
- https://www.cs.indiana.edu/~bhimebau/f3lib/html/usb__desc_8c_source.html --> STMF32 discussion
- https://os.mbed.com/forum/mbed/topic/2655/ --> usb hid string descriptor issue
- https://forum.pjrc.com/archive/index.php/t-23796.html --> serial number solution
- http://www2.ece.rochester.edu/~parihar/pres/Report_MultiMedia-KB.pdf --> to read ?

#### USB-related stuff & reminders
- https://www.beyondlogic.org/usbnutshell/usb6.shtml#StandardEndpointRequests
- https://hackaday.com/2015/12/23/usb-proxy-rats-out-your-devices-secrets/
- https://superuser.com/questions/42022/how-does-usb-device-recognition-work
- https://docs.microsoft.com/en-us/windows-hardware/drivers/usbcon/usb-endpoints-and-their-pipes

#### ps3-related HID stuff
- http://www.slashdev.ca/2010/05/25/ps3-gamepad-with-home-button/
- http://git.slashdev.ca/ps3-teensy-hid/tree/src/usb_gamepad.h?id=35aef5771de9fd4dccadae4ec363a3255e6760ba

#### originalXbox-related stuff
- http://euc.jp/periphs/xbox-controller.ja.html
- https://bunniefoo.com/nostarch/HackingTheXbox_Free.pdf => Bunnie's Book !!! :D
- https://www.iacr.org/workshops/ches/ches2002/presentations/Huang.pdf

#### Xbox360-related stuff
- https://www.withoutthesarcasm.com/using-a-mouse-and-keyboard-for-console-games/4/ --> close to what i did for original xbox
- https://hackaday.com/2015/07/14/using-a-teensylc-to-emulate-the-xbox-360-controller/
- http://www.zlittell.com/2015/07/msf-fightstick-teensylc-xinput-controller-6/ --> this is DOPE !
- http://www.zlittell.com/2015/07/msf-fightstick-teensylc-xinput-controller-8/
- https://github.com/zlittell/MSF-FightStick/blob/master/MSF_FightStick/MSF_FightStick.ino
- https://github.com/zlittell/MSF-XINPUT
- http://www.zlittell.com/2016/05/xinput-library-for-teensyduino/
- https://www.tested.com/tech/gaming/569647-how-build-pinsim-virtual-reality-pinball-machine/
- https://github.com/xxxajk/cores/commit/f8938ec150118ef0aac2d0712f35f176006345bb --> Fix Yield when no Serial on USB
- https://brandonw.net/360bridge/
- https://cronusmax.com/ --> expensive adapter :/

#### Xbox360-security related stuff
- https://www.engadget.com/2010/02/12/christopher-tarnovsky-hacks-infineons-unhackable-chip-we-pre/
- https://www.eastbaytimes.com/2010/02/08/super-security-chip-unlocked/
- https://forums.shoryuken.com/t/xbox-360-controller-authentication-workarounds/145838/13
- https://www.theregister.co.uk/2010/02/17/infineon_tpm_crack/
- https://hackaday.com/2015/12/23/usb-proxy-rats-out-your-devices-secrets/
- http://gimx.fr/wiki/index.php?title=DIY_USB_adapter
- http://blog.gimx.fr/serialusb/
- https://gimx.fr/wiki/index.php?title=DIY_USB_adapter
- https://gimx.fr/wiki/index.php?title=DIY_USB_adapter_for_dummies

#### XboxOne-related stuff
- https://github.com/JRHeaton/XboxOneControllerDev

#### XInput-related stuff ( windows side )
- https://docs.microsoft.com/en-us/windows/desktop/api/xinput/ns-xinput-_xinput_keystroke KeyStroke structure
- https://docs.microsoft.com/en-us/windows/desktop/api/xinput/ns-xinput-_xinput_gamepad GamePad structure
- https://docs.microsoft.com/en-us/windows/desktop/api/xinput/ XInput header
- https://docs.microsoft.com/en-us/windows/desktop/api/xinput/nf-xinput-xinputgetcapabilities
- https://docs.microsoft.com/en-us/windows/desktop/api/_xinput/
- https://docs.microsoft.com/fr-fr/windows/desktop/xinput/programming-guide
- https://docs.microsoft.com/fr-fr/windows/desktop/xinput/getting-started-with-xinput
- https://docs.microsoft.com/fr-fr/windows/desktop/xinput/directinput-and-xusb-devices
- https://docs.microsoft.com/fr-fr/windows/desktop/xinput/xinput-and-controller-subtypes

#### Espruino-related stuff
- https://github.com/espruino/Espruino/tree/master/targetlibs/stm32usb
- https://github.com/espruino/Espruino/blob/master/src/jsvar.h
- https://github.com/espruino/Espruino/blob/master/src/jswrap_espruino.c --> L563 for USB HID & cie

#### STM32F-related stuff
- https://www.st.com/content/ccc/resource/technical/document/user_manual/cf/38/e5/b5/dd/1d/4c/09/DM00108129.pdf/files/DM00108129.pdf/jcr:content/translations/en.DM00108129.pdf
- https://notes.iopush.net/stm32-custom-usb-hid-step-by-step-2/ --> custom HID using CubeMX
- https://damogranlabs.com/2016/03/stm32-custom-usb-hid-device-yes-please/
- https://damogranlabs.com/2018/02/stm32-usb-cdc/
- https://damogranlabs.com/2018/02/stm32-usb-hid-mouse-keyboard/
- http://kevincuzner.com/2018/01/29/bare-metal-stm32-writing-a-usb-driver/
- http://kevincuzner.com/2014/12/12/teensy-3-1-bare-metal-writing-a-usb-driver/
