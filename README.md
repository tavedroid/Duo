
# RedBear Duo
---

![image](docs/images/RB_Duo.png)

The [RedBear Duo](http://www.redbear.cc/duo) is a thumb-size development board designed to simplify the process of building Internet of Things (IoT) products. It provides everything you need -- Wi-Fi, BLE and a powerful Cloud backend, all in a compact form factor that makes it ideal for your first prototype, a finished product, and everything in between. [More >>](docs/duo_introduction.md) 

Purchase your RedBear Duo now: 

* [RedBear Store](https://store.redbear.cc/product.html)
* [Worldwide Resellers](http://redbearlab.com/buy/)


## Directories and Files

* `certs/`: FCC & CE certifications
* `docs/`: Documentation for improving your experience on the Duo
* `driver/`: Duo Windows USB driver
* `firmware/bootloader/`: Released bootloader images for Duo
* `firmware/dct/`: Some configuration files can be applied to Duo's internal DCT
* `firmware/javascript_interpreter/`: Released JavaScript interpreter images for Duo
* `firmware/python_interpreter/`: Released Python interpreter images for Duo
* `firmware/system/`: Released system firmware images
* `firmware/wifi/`: Wi-Fi firmware for the wireless module 
* `hardware/`: Hardware design files, datasheets and pin mapping
* `scripts/`: Useful scripts for playing with the Duo


## Documentation

#### References

* [Duo Introduction](docs/duo_introduction.md)
* [RBLink Introduction](docs/rblink_introduction.md)
* [Arduino/C/C++ Programming Reference Manual](docs/programming_reference_manual.md)
* [Firmware Architecture Overview](docs/firmware_architecture_overview.md)
* [How It Works](docs/how_it_works.md)
* [WiFi/BLE/USBSerial Setup Protocol in Listening Mode](docs/listening_mode_setup_protocol.md)
* [System Firmware Change-log](docs/system_firmware_changelog.md)
* [Arduino Board Package Change-log](https://github.com/redbear/STM32-Arduino/blob/master/CHANGELOG.md)
* [JavaScript Interpreter Change-log](docs/javascript_interpreter_changelog.md)
* [JavaScript Programming Reference Manual](docs/javascript_programming_reference_manual.md)
* [Python Programming Reference Manual](docs/python_programming_reference_manual.md)
* [Troubleshooting](docs/troubleshooting.md)

#### Tutorials

* [Out-of-Box Experience](docs/out_of_box_experience.md)
* [Getting Started with Arduino IDE](docs/getting_started_with_arduino_ide.md)
* [Getting Started with Particle Build (Web IDE)](docs/getting_started_with_particle_build.md)
* [Firmware Deployment Guide](docs/firmware_deployment_guide.md)
* [Arduino Board Package Installation Guide](docs/arduino_board_package_installation_guide.md)
* [dfu-util Installation Guide](docs/dfu-util_installation_guide.md)
* [Windows Driver Installation Guide](docs/windows_driver_installation_guide.md)
* [Devices Provisioning Guide](docs/devices_provisioning_guide.md)

#### 3rd Party

* [Particle Documentation](https://docs.particle.io/guide/getting-started/intro/photon/)
* [Espruino Documentation](http://www.espruino.com/)
* [MicroPython Documentation](http://docs.micropython.org/en/latest/pyboard/)


## Resources

* [Application Examples](https://github.com/redbear/STM32-Arduino/tree/master/arduino/libraries/RedBear_Duo)
* [Arduino IDE](https://www.arduino.cc/en/Main/Software)
* [Particle Build (Web IDE)](https://build.particle.io/)
* [Particle Dashboard](https://dashboard.particle.io/)
* [Modified Particle Firmware Source Code](https://github.com/redbear/firmware)
* [Modified Espruino Source Code](https://github.com/redbear/Espruino)
* [Modified MicroPython Source Code](https://github.com/redbear/micropython)
* [WICED SDK](https://community.broadcom.com/community/wiced-wifi/wiced-wifi-documentation)
* [WICED SDK Patch for Duo](https://github.com/redbear/WICED-SDK)
* [BTStack Source Code](https://github.com/redbear/btstack)


## Supports

* [RedBear Discussion](http://discuss.redbear.cc)
* [Arduino Forum](https://forum.arduino.cc/)
* [Particle Community](https://community.particle.io)
* [Broadcom Community](https://community.broadcom.com/welcome)
* [Espruino Forum](http://forum.espruino.com/)
* [MicroPython Forum](http://forum.micropython.org/)
* [BlueKitchen](https://bluekitchen-gmbh.com/)


## ToDo

* Add more BLE examples to the Particle Build (Web IDE) and Arduino IDE.

	The BLE examples are not completed yet, for Web IDE, we have not yet added any examples for BLE, if you want to try BLE using Web IDE, please browse [this](https://github.com/redbear/STM32-Arduino/tree/master/arduino/libraries/RedBear_Duo/examples/03.BLE), copy & paste the code to the Web IDE.

* Reduce power consumption for BLE

	We will work with Broadcom to reduce the power consumption for the Duo BLE.


## License

Copyright (c) 2016 Red Bear

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

