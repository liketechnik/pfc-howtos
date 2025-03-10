# This repo includes all the HowTos available for PFC

# Overview of existing HowTos

| Name                               | for Version | Description |
| :--------------------------------- | :---------- | :---------- |
| AccessRetainVariables              | FW17   | Accessing retain variables using C or C++ |
| AddPerfTool                        | FW12   | Adding perf tool |
| AddTRDP                            | FW12   | Adding TRDP/TCNopen |
| AddSQLiteCommandLineTool           | FW12   | Install the command-Line-Tool "sqlite3"|
| ADI-MyKBusApplikation              | FW12   | Demo C Application for KBUS |
| ADI-DALwithSerialTerminal750-652   | FW20.1 | Utilize serial terminal 750-652 via DAL/ADI |
| AutoCopySD-CardImage2InternalFlash | FW12   | Automaticaly copies SD card image to internal flash |
| BuildRustExecutables               | FW17   | Cross-compile RUST executables |
| Certmonger                         | FW20.1 | Daemon monitors certificates for impending expiration |
| HowTo_GenerateWUPFile              | FW12   | Generate WAGO-Upload-File |
| KbusModbusSlave                    | FW14 | Adding KbusModbusSlave |
| Mono                               | FW14   | Mono is a runtime implementation|
| mosquittoBroker                    | FW12.1 | Adding a Mosquitto Broker |
| OpenDDS                            | FW18   | Open source C++ implementation of DDS |
| ReadOperatingModeSwitches          | FW12   | Reads out the switch position |
| Ser2Net                            | FW13   | Serial to Network Proxy |
| ZeroMQ                             | FW18   | High-performance asynchronous messaging library |
| Libkbus-register-settings          | FW20.1 | Precompiled version of kbus-register-settings |
| Register-access-65x-demo           | FW20.1 | Demo usage of the `libkbus-register-settings` library |

---

You will find in any specific HowTo a dedicaded README.md which included a table that shows you the compatibiliy
of this how to.

For example:

| PFC | Compatible |
|:-------------|:------------:|
| **PFC 100** | |
| 750-8100 | Y |
| 750-8101 | Y |
| 750-8102 | Y |
|  |  |
| **PFC 200** | |
| 750-8202 | Y |
| 750-8203 | Y |
| 750-8204 | Y |
| 750-8206 | Y |
| 750-8207 | Y |
| 750-8208 | Y |
|  |  |
| **PFC 200 G2** | |
| 750-8212 | Y |
| 750-8213 | Y |
| 750-8214 | Y |
| 750-8216 | Y |

Also you will find a version information that show exactly the firmware version on which this
Howto was created. This means if you will find an older HowTo for a newer firmware it might 
require a little extra effort to transfer it to the actual firmware version.
Pleasw keep in mind that some HowTos includes a precompiled package. Those could work on older versions but we recommend to recompile them within the actual firmware.

A version Information looks like this:


---
**HowTo XY - For Version BSP2017.17.1**

---

Inside the HowTo directory you will find for older HowTos a **HowTo_XY.txt** file. This file contains a setup guide and provides some extra informations.


