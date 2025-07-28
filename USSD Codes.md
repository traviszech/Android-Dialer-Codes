# Samsung USSD Code List

A comprehensive compilation of USSD (Unstructured Supplementary Service Data) codes for Samsung Galaxy devices. These codes provide access to various hidden menus, diagnostic tools, and system information.

**Disclaimer:** Use these codes with extreme caution. Some codes can perform irreversible actions, such as factory resets, or reveal sensitive device information. I am not responsible for any damage, data loss, or privacy issues that may arise from the use of these codes. Always back up your data before attempting any code that modifies system settings.

## Table of Contents

* [General Information & Version Codes](#general-information--version-codes)
* [Service/Engineering/Diagnostic Menus](#serviceengineeringdiagnostic-menus)
* [Sensor & Hardware Tests](#sensor--hardware-tests)
* [Battery & Power Codes](#battery--power-codes)
* [Network/Carrier Control Codes](#networkcarrier-control-codes)
* [System / Debug / Logs Codes](#system--debug--logs-codes)
* [Camera / Multimedia Test Codes](#camera--multimedia-test-codes)
* [Special Feature Modes](#special-feature-modes)
* [Danger & Factory Reset Codes](#danger--factory-reset-codes)
* [Android Manufacturer-Specific ADB Engineering Codes](#android-manufacturer-specific-adb-engineering-codes)
* [Final Notes](#final-notes)

---

## General Information & Version Codes

These codes provide details about your Samsung device's identity, software, and hardware versions.

| Code           | Function                                      | Description                                                 |
| :------------- | :-------------------------------------------- | :---------------------------------------------------------- |
| `*#06#`        | Show IMEI number(s)                           | Displays your International Mobile Equipment Identity (IMEI) number(s). |
| `*#1234#`      | Show PDA / firmware version                   | Shows the current software version (AP, CP, CSC).             |
| `*#*#4636#*#*`  | Phone Info, Usage Stats, Wi-Fi Info           | Accesses a hidden menu with comprehensive phone, battery, usage statistics, and Wi-Fi details. |
| `#12580369#`   | Detailed software/hardware version + RF CAL date | Provides in-depth software/hardware info, including RF Calibration date. |
| `*#9999#`      | Software version check                        | Alternative code for checking the software version.           |
| `*#8888#`      | FTA Hardware/Manufacture software version     | Displays FTA (Field Test Application) hardware and manufacturing software versions. |
| `*#2222#`      | FTA Hardware/Software Version                 | Shows FTA hardware and software versions. (Often `*#1111#` for software). |
| `*#1111#`      | FTA Software Version                          | Shows FTA software version. (Often `*#2222#` for hardware). |
| `*#44336#`     | Builds date, changelist, time info            | Provides detailed build information, including date, changelist, and time. |
| `*#07#`        | SAR (radiation) info                          | Displays Specific Absorption Rate (SAR) radiation information. |
| `*#03#`        | NAND Flash S/N                                | Displays the NAND Flash serial number.                      |
| `*#2663#`      | TSP / TSK Firmware Update                     | Displays and allows firmware updates for the Touch Screen Panel (TSP) and Touch Screen Key (TSK). |
| `*#*#232338#*#*`| Display Wi-Fi MAC Address                     | Shows the Wi-Fi MAC (Media Access Control) address.         |
| `*#*#232337#*#*`| Display Bluetooth Device Address              | Shows the Bluetooth device address.                         |

---

## Service/Engineering/Diagnostic Menus

These codes grant access to various service, engineering, and diagnostic menus for testing and configuration.

| Code              | Function                                | Description                                                 |
| :---------------- | :-------------------------------------- | :---------------------------------------------------------- |
| `*#0*#`           | Testing: display, vibration, speaker, cam, sensor, touch, RGB | Enters a general test mode for various hardware components. |
| `*#0011#`         | Serving Cell info                       | Displays serving cell information: signal strength, band, CA status. |
| `*#197328640#`    | Service Mode (main)                     | Accesses the main service mode for advanced settings.         |
| `*#2683662#`      | Engineering Service mode – Network, diagnostics | Enters an engineering service mode for network and diagnostics. |
| `*#26833662#`     | Engineering Service mode – Network, diagnostics (Alt) | Alternate code for engineering service mode.                 |
| `*#9090#`         | Diagnostic configuration                | Allows configuration of diagnostic settings.                |
| `*#2263#`         | RF Band selector                        | Accesses a menu to select RF bands.                         |
| `#0523#`          | Display color calibration test          | Initiates a test for display color calibration.             |
| `#0842#`          | Test vibration & backlight              | Tests the device's vibration and backlight functions.       |
| `##0842##`        | Test vibration & backlight (Alt)        | Alternate code for testing vibration and backlight.         |
| `*#7353#`         | Quick Test menu                         | Provides a quick menu for various tests (alternate to `*#0*#`). |
| `*#0289#`         | Melody Test Mode / Audio Test           | Initiates an audio test or melody test.                     |
| `#2732832553282#` | Data dump/upload/test menu              | Accesses a menu for data dumping, uploading, and testing.   |
| `*#7284#`         | USB I2C Mode Control                    | Allows control over USB I2C (Inter-Integrated Circuit) mode. |
| `*#4238378#`      | GCF Configuration                       | Accesses GCF (Global Certification Forum) configuration settings. |
| `*#3214789650#`   | LBS Test Mode                           | Enters Location Based Services (LBS) test mode.             |
| `*#745#`          | RIL Dump Menu                           | Accesses the Radio Interface Layer (RIL) dump menu for network-related logging. |
| `*#746#`          | Debug Dump Menu                         | Accesses a general debug dump menu.                         |
| `#78`             | Testing mode (short form)               | A short-form testing mode, rarely used and often carrier-modified. |
| `*#3588#`         | Engineering/QA menu                     | Accesses an engineering/QA menu on select firmware versions. |
| `#7412365`        | Camera Module Version Check             | Checks the version of the camera module.                    |
| `*#4562580#`      | OIS (optical image stabilization) Auto Test | Initiates an automatic test for Optical Image Stabilization. |
| `*#15987#`        | Color LCD Test                          | Performs a test of the LCD colors.                          |
| `*#0763#`         | Sensorhub firmware service              | Accesses sensorhub firmware service (rarely used).          |
| `*#19242022#`     | CDSP restriction check                  | Checks CDSP (Cellular Digital Signal Processor) restrictions. |
| `*#66336#`        | CP (core processor) debug level         | Displays or allows setting of the core processor's debug level. |
| `*#727728#`       | Call Receive Test                       | Performs a test for call receiving functionality.           |
| `*#663366#`       | Debug switch test                       | Tests debug switches.                                       |
| `*#2929#`         | Network Unlock test submenu             | Accesses a network unlock test submenu (used by carriers/Samsung tools). |
| `#0514#`          | Access sysdump (alternate)              | An alternate path to access the system dump.                |
| `#01110000000#`   | SIM unlock                              | Used for SIM unlocking after inserting a new SIM card.      |

---

## Sensor & Hardware Tests

Codes to test various sensors and hardware components of your Samsung device.

| Code        | Function                         | Description                                                 |
| :---------- | :------------------------------- | :---------------------------------------------------------- |
| `*#0588#`   | Proximity sensor test            | Tests the functionality of the proximity sensor.            |
| `*#0589#`   | Light sensor test                | Tests the functionality of the ambient light sensor.        |
| `*#1106#`   | Grip sensor test (edge touch feedback) | Tests the grip sensor, often related to edge touch feedback. |
| `*#0283#`   | Audio loopback test              | Tests audio loopback for microphone and speaker.            |
| `*#77692#`  | Proximity test (alternative)     | An alternative code for testing the proximity sensor.       |
| `#77694#`   | ADC (Analog-Digital Converter) Service | Accesses the Analog-Digital Converter service.              |
| `*#35789#`  | MCD Component Diagnostic         | Performs diagnostic checks on MCD (Multi-Chip Device) components. |
| `*#0827#`   | Auto hardware test (limited build) | Initiates an automatic hardware test (may be limited to specific builds). |

---

## Battery & Power Codes

Codes related to battery status and power management.

| Code        | Function                     | Description                                                 |
| :---------- | :--------------------------- | :---------------------------------------------------------- |
| `*#0228#`   | Battery status               | Displays detailed battery information: voltage, temperature, and calibration info. |
| `*#0782#`   | RTC (Real-time clock) test   | Tests the Real-time Clock functionality.                    |
| `*#22558463#` | Reset total call time        | Resets the total call time counter on the device.           |

---

## Network/Carrier Control Codes

These codes are for managing network settings, call features, and carrier-specific configurations.

| Code            | Function                                | Description                                                 |
| :-------------- | :-------------------------------------- | :---------------------------------------------------------- |
| `*#004#`        | Call forwarding (retrieve/disconnect/reset) | Used to retrieve, disconnect, or reset call forwarding settings. |
| `#004#`         | Call forwarding (retrieve/disconnect/reset) | Used to retrieve, disconnect, or reset call forwarding settings. |
| `##004#`        | Call forwarding (retrieve/disconnect/reset) | Used to retrieve, disconnect, or reset call forwarding settings. |
| `*#21#` + call  | Check unconditional forwarding           | Checks if unconditional call forwarding is enabled.          |
| `*#61#` + call  | Check Call Forwarding (No Answer)       | Checks the number to which calls are forwarded when there's no answer and the delay time. |
| `*#62#` + call  | Check call forwarding when unreachable    | Checks if call forwarding when unreachable is enabled.      |
| `*#67#` + call  | Check Call Forwarding (Busy)            | Checks the number to which calls are forwarded when the line is busy. |
| `*#43#`         | Call waiting: enable / disable / check  | Enables, disables, or checks the status of call waiting.    |
| `#43#`          | Call waiting: enable / disable / check  | Enables, disables, or checks the status of call waiting.    |
| `*#43#`         | Call waiting: enable / disable / check  | Enables, disables, or checks the status of call waiting.    |
| `#31#`          | Show/hide caller ID                     | Toggles showing or hiding your caller ID for outgoing calls. |
| `*31#`          | Show/hide caller ID                     | Toggles showing or hiding your caller ID for outgoing calls. |
| `#135#`         | Own number check                        | Displays your own phone number.                             |
| `#77467#`       | IMS setting viewer (VoLTE, RCS config)  | Views IMS (IP Multimedia Subsystem) settings, including VoLTE and RCS configurations. |
| `#8827766#`     | Galaxy Store Diagnostic: On             | Toggles Galaxy Store diagnostics to ON.                     |
| `#88277633#`    | Galaxy Store Diagnostic: Off            | Toggles Galaxy Store diagnostics to OFF.                    |
| `#6628378#`     | OMC Feature Menu (One UI CSC configuration) | Accesses the OMC (Original Manufacturer Customization) Feature Menu for One UI CSC configuration (carrier dependent). |
| `#32489#`       | Ciphering Information                   | Displays ciphering information.                             |
| `7465625638#`   | Network Subset/Region Lock info         | Shows information about network subset or region locks.     |
| `746562577/27/782/228#` | SIM locks: SP, CP, SUBSET, ACTIVA | Displays various SIM lock statuses (SP, CP, SUBSET, ACTIVA) for advanced use only. |
| `*7465625*638*#` | Network Lock Keycode                    | Used for network lock keycode operations (advanced carrier-specific use). |
| `#7465625*782#` | Partial Network Lock Keycode            | Used for partial network lock keycode operations.           |

---

## System / Debug / Logs Codes

Codes for accessing system-level information, debugging tools, and logs.

| Code         | Function                             | Description                                                 |
| :----------- | :----------------------------------- | :---------------------------------------------------------- |
| `*#9900#`    | System dump/log tools                | Provides access to system dump and logging tools, including logs, traces, and cache cleaning. |
| `*#0514#`    | Sysdump (alt path)                   | An alternate path to access the system dump.                |
| `*#22558463#` | Reset Call Timer                     | Resets the total call time on the device.                   |
| `*#872564#`  | USB logging (enable/disable)         | Enables or disables USB logging.                            |
| `*#0808#`    | USB Settings                         | Allows you to change USB connection settings (e.g., MTP, PTP, charging only). |
| `*#278886#`  | Auto Answer settings                 | Configures auto answer settings.                            |
| `*#77692#`   | Proximity test                       | Tests the proximity sensor.                                 |
| `*#7785#`    | Factory reset (dangerous)            | Initiates a factory reset (dangerous, may not prompt confirmation). |
| `#77694#`    | ADC Configuration menu               | Accesses the Analog-Digital Converter (ADC) configuration menu. |
| `*#2683662#` | Service Mode Command 1000            | Executes Service Mode Command 1000.                         |
| `##2627##`   | Cell Broadcast Test Mode             | Enters Cell Broadcast Test Mode for messaging signal testing. |
| `*#66336#`   | CP Debug Level                       | Displays or allows setting of the Core Processor's debug level. |
| `##8255##`   | GTalk Service Monitor                | Accesses the GTalk (Google Talk) Service Monitor.           |
| `##7594##`   | Direct Power OFF configuration toggle | Toggles the direct power off configuration, potentially allowing power off without confirmation. |
| `*#7594#`    | Remap Shutdown to End Call TSK       | Toggles whether the power button (TSK - Touch Screen Key) can end calls. |
| `#8827766#`  | Galaxy Apps Debug Toggle: ON         | Toggles Galaxy Apps debug mode to ON.                       |
| `#88277633#` | Galaxy Apps Debug Toggle: OFF        | Toggles Galaxy Apps debug mode to OFF.                      |

---

## Camera / Multimedia Test Codes

Codes for testing camera and other multimedia functionalities.

| Code          | Function                              | Description                                                 |
| :------------ | :------------------------------------ | :---------------------------------------------------------- |
| `*#34971539#` | Camera firmware version and settings  | Displays camera firmware version and allows access to settings. |
| `*#7412365#`  | Camera module info check              | Checks information about the camera module.                 |
| `##1472365##` | GPS Test                              | Initiates a GPS test.                                       |
| `##1575##`    | Advanced GPS testing                  | Provides advanced GPS testing functionalities.              |
| `#7412365#`   | Module version check (camera, GPS, light/audio) | Checks the module version for various components like camera, GPS, light, and audio. |

---

## Special Feature Modes

These input methods launch specific debug or diagnostic modes within Samsung apps.

| Input (App)                    | Function                                      | Description                                                 |
| :----------------------------- | :-------------------------------------------- | :---------------------------------------------------------- |
| `+30012012732+` (on Samsung Calculator) | Launch DRParser Mode                          | Launches DRParser Mode, an advanced menu for internal debugging and system manipulation. Must be typed exactly. |
| `#00rtsp00`                    | Smart View Debug Menu (One UI 5.1 and newer)  | Accesses the Smart View debug menu for One UI 5.1 and newer versions. |
| `#00sv00`                      | Smart View Debug (Legacy One UI 4.xx, <5.0)   | Accesses the Smart View debug menu for older One UI versions (4.xx, <5.0). |

---

## Danger & Factory Reset Codes

**WARNING:** These codes can perform irreversible actions, including erasing all data on your device. Use with extreme caution and ensure you have backed up any important data.

| Code          | Function                                  | Description                                                 |
| :------------ | :---------------------------------------- | :---------------------------------------------------------- |
| `#7780#`      | Factory reset with confirmation           | Initiates a factory reset, typically with a confirmation prompt. |
| `##7780##`    | Factory reset with confirmation (Alt)     | Alternative code for factory reset with confirmation.       |
| `*2767*3855#` | Full factory reset — no confirmation, immediate wipe! | **Performs a full factory reset, immediately wiping all data and reinstalling firmware without confirmation.** |
| `#272IMEI#`   | CSC/Sales Code Change — resets the device | Changes the CSC (Country Specific Code)/Sales Code, which will reset the device and can change regional settings/firmware. |

---

## Android Manufacturer-Specific ADB Engineering Codes

These are often useful across various Android brands for activating USB Debugging or hidden diagnostic tools, but are not exclusive to Samsung.

| Brand      | ADB/Engineering Menu Code |
| :--------- | :------------------------ |
| Huawei     | `##2846579##`             |
| Xiaomi     | `##6484##`                |
| Vivo       | `##225##`                 |
| Oppo       | `*#899#`                  |
| Infinix    | `##49##` or `*#85#`       |
| Tecno      | `##49##` or `*#85#`       |
| Alcatel    | `*#2886#`                 |
| Lenovo     | `##4636##`                |
| Sony       | `##737378423##`           |
| Motorola   | `##2486##`                |
| Honor      | `##2345##`                |
| OnePlus    | `##2346579##`             |

---

## Final Notes

* Most codes require dial pad insertion in the stock **Phone** app.
* **Carrier-branded phones** (e.g., Verizon, AT&T) may disable some codes due to firmware restrictions.
* Some codes require pressing the **call button** to activate after dialing.
* Check **Auto Blocker** (under Security settings or Device Ca