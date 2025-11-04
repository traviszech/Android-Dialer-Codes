# 📱 Android Secret Codes (MMI/USSD/Dialer Codes) Master List

A comprehensive, categorized, and de-duplicated list of Android **MMI (Man-Machine Interface)** codes, focusing on manufacturer-specific diagnostics, hidden menus, and testing tools.

***

## 🤝 CONTRIBUTIONS & ATTRIBUTION

If you are aware of an Android secret code for any manufacturer that is not included in this list, please contact the original author.

* **Author:** Travis L. Zech
* **Email:** traviszech@hotmail.com
* **GitHub Repository:** [https://github.com/traviszech/Samsung-Dialer-codes](https://github.com/traviszech/Samsung-Dialer-codes)

### License and Attribution

This list is provided under the **Creative Commons Attribution 4.0 International (CC BY 4.0) License**.

**Original Source Credit:** Travis L. Zech

### ⚠️ CRITICAL WARNINGS & DISCLAIMER

#### Code Syntax Variations

**IMPORTANT:** Due to manufacturer and carrier variations, some codes may not work as listed. If a code fails, try these common variations:

* **If listed as `*#XXXX#`:** Try typing it as `*#*#XXXX#*#*`
* **If listed as `*#*#XXXX#*#*`:** Try typing it as `*#XXXX#`
* **If listed as `##XXXX##`:** Try typing it as `*#*#XXXX#*#*`

#### ⚖️ LIABILITY AND INDEMNITY DISCLAIMER

**THIS LIST IS PROVIDED "AS IS," WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHOR, CONTRIBUTORS, OR COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE USE OF THIS LIST OR THE CODES CONTAINED WITHIN.**

* **No Legal Advice:** This list and its associated documentation are for **educational, informational, and experimental purposes only**. It does not constitute, and should not be relied upon as, professional advice (legal, technical, financial, or otherwise).
* **Assumption of Risk:** By using any code from this list, the user **voluntarily assumes all risks** associated with such use, including, but not limited to, data loss, device malfunction, voiding of warranties, and potential legal complications arising from misuse.

***

## I. Samsung / General Android Codes (Core List)

This section contains codes primarily for **Samsung Galaxy** devices (One UI), plus core MMI codes common across most Android phones.

| Code | Function | Category | Notes |
| :--- | :--- | :--- | :--- |
| `*#0*#` | **General Test Mode** (LCD, Sensor, Touch, Speaker, etc.) | Hardware/System Diagnostics | Primary comprehensive test menu. |
| `*#0011#` | Serving Cell Info / Service Mode Tests | Network/Service Menu | Detailed signal and network status. |
| `*#0228#` | **Battery Status** (Voltage, Temp, Calibration Info) | Power/Diagnostics | Provides health and technical battery data. |
| `*#06#` | Show **IMEI Number(s)** (International Mobile Equipment Identity) | Universal Info | Universal code to retrieve your unique device ID. |
| `*#0808#` | USB Configuration Settings (MTP, ADB, Modem) | Configuration | Changes how the device connects to a PC. |
| `*#1234#` | Show PDA / Firmware Version (AP, CP, CSC) | Firmware/Info | Displays the main software, phone, and region code versions. |
| `*#12580*369#` | Detailed Software/Hardware Version + RF CAL date | Firmware/Info | Shows internal hardware revision and calibration details. |
| `*#197328640#` | Service Mode Tests (Main) | Service Menu | Access to the main service test index. |
| `*#2663#` | Device Firmware (TSP/Touch, Bootloader, etc.) | Firmware/Update | Displays and manages hardware component firmware. |
| `*#34971539#` | Camera Firmware Version and Settings | Firmware/Update | Detailed information about the camera modules. |
| `*#44336#` | Builds Date, Changelist, Time Info | Firmware/Info | Shows compilation details of the current build. |
| `*#7353#` | Quick Test Menu (Alternate #0#) | Hardware/System Diagnostics | Faster access to common component tests. |
| `*#9090#` | Diagnostic Configuration / Service Menu | Debugging/Configuration | Advanced configuration for engineers. |
| `*#9900#` | **SysDump** (Access Debug Logs, Cache Clean) | Debugging | Allows deletion of system logs and dumps. |
| `*2767*3855#` | **Full Factory Reset** (Immediate Wipe) | **DANGEROUS / Reset** | Performs an immediate, irreversible full wipe and firmware reinstall. |
| `*#*#4636#*#*` | Phone Information / Testing Menu (Usage Stats, Battery, Network) | Universal Diagnostics | Standard Android hidden menu. |
| `*#*#7780#*#*` | Factory Soft Reset (with Confirmation) | Reset | Initiates a factory data reset with a prompt for confirmation. |

<details>
<summary>View All Samsung/General Codes (Click to expand)</summary>

| Code | Function | Category |
| :--- | :--- | :--- |
| `#0#` | Testing: display, vibration, speaker, cam (Alt) | Hardware/System Diagnostics |
| `*#0283#` | Audio Loopback Test | Hardware/System Diagnostics |
| `*#0289#` | Melody Test Mode | Hardware/System Diagnostics |
| `*#0673#` | Audio Test Mode | Hardware/System Diagnostics |
| `*#07#` | SAR (Radiation) Information | Universal Info |
| `*#1575#` | Full GPS Test Settings | Location/Diagnostics |
| `*#21# + call` | Check Unconditional Call Forwarding Status | Network Settings |
| `*#232331#` | Bluetooth Test Mode | Hardware/System Diagnostics |
| `*#232337#` | Display Bluetooth Device Address | Universal Info |
| `*#232338#` | Display WLAN MAC Address | Universal Info |
| `*#232339#` | WLAN Test Mode | Hardware/System Diagnostics |
| `*#301279#` | HSDPA/HSUPA (3G Data) Control Menu | Network/Configuration |
| `*#3264#` | RAM Version Check | Universal Info |
| `*#*#426#*#*` | FCM Diagnostics / Google Play Services Info | Debugging |
| `*#*#0842#*#*` | Vibration and Backlight Test | Hardware/System Diagnostics |
| `*#*#2664#*#*` | Touch Screen Test | Hardware/System Diagnostics |
</details>

***

## II. Manufacturer-Specific ADB/Engineering Codes

These codes are unique to the brand and designed for diagnostics, service, or advanced configuration.

### 🇺🇸 Google Pixel (Stock Android)

| Code | Function | Category | Notes |
| :--- | :--- | :--- | :--- |
| `*#*#7287#*#*` | **Pixel Diagnostics App** | Dedicated Diagnostics | Opens the built-in Pixel diagnostics application. |
| `*#*#2845#*#*` | **RIL (Radio Interface Layer) Test** | Network/Service Menu | Advanced testing for the communication stack. |
| `*#*#284#*#*` | **Save Snapshot Log** | Debugging | Forces the creation of a bug report (log file). |
| `*#*#426#*#*` | FCM Diagnostics / Google Play Services | Debugging | Shows Firebase Cloud Messaging status. |

### 🇹🇼 ASUS (Zenfone / ROG Phone)

| Code | Function | Category | Notes |
| :--- | :--- | :--- | :--- |
| `.12345+=` | **Open Engineering Mode** | Engineering/Service Menu | **Must be entered in the stock Calculator app.** |
| `*#*#7262626#*#*` | **Field Test Mode** | Network/Diagnostics | Shows network/cell tower data. |
| `*#07#` | Regulatory Labels (SAR, etc.) | Universal Info | Displays compliance and regulatory information. |

### 🇨🇳 Xiaomi (MIUI / HyperOS)

| Code | Function | Category | Notes |
| :--- | :--- | :--- | :--- |
| `*#*#6484#*#*` | **Hardware Test Menu** (CIT Menu) | Hardware/System Diagnostics | The official Xiaomi quality control test suite. |
| `*#*#6485#*#*` | Charging and Battery Info | Power/Diagnostics | Detailed battery health and charging parameters. |
| `*#*#86583#*#*` | **Enable VoLTE Carrier Check** | Network/Configuration | Forces the device to check for VoLTE support. |

### 🇨🇳 OnePlus / Realme

| Code | Function | Category | Notes |
| :--- | :--- | :--- | :--- |
| `*#808#` | **Engineering Mode** (Hardware Diagnostics) | Engineering/Service Menu | Access to the main component testing suite. |
| `*#*#2947322243#*#*` | **Wipes Internal Memory** | **DANGEROUS / Reset** | **IMMEDIATELY** and fully wipes the device. Use with extreme caution. |

### 🇰🇷 LG

| Code | Function | Category |
| :--- | :--- | :--- |
| `3845#*\[Model No.]#` | **Secret Menu / Service Menu** | Service Menu |
| `*#*#372733#*#*` | Service Mode / FQC (Factory Quality Check) Menu | Service Menu |

### 🇨🇳 Huawei / Honor

| Code | Function | Category | Notes |
| :--- | :--- | :--- | :--- |
| `*#*#2846579#*#*` | **Project Menu / Engineering Mode** | Engineering/Service Menu | The main hidden configuration menu for Huawei/Honor. |

### 🇺🇸 Motorola

| Code | Function | Category |
| :--- | :--- | :--- |
| `*#*#2486#*#*` | Engineering Mode / Service Menu | Engineering |
| `##3424#` | Diagnostic Mode | Diagnostics |

### 🇨🇳 TCL / Alcatel / BlackBerry (TCL-made Android Phones)

| Code | Function | Category | Notes |
| :--- | :--- | :--- | :--- |
| `*#2886#` | **Test Menu** (General hardware diagnostics) | Diagnostics | TCL/Alcatel common code. |
| `*#*#2886#*#*` | Hardware Test Mode (BlackBerry Android) | Diagnostics |

### 🇯🇵 Sony

| Code | Function | Category |
| :--- | :--- | :--- |
| `*#*#737378423#*#*` | Service Menu (Specific Models) | Service |

### Other Manufacturers (Misc.)

| Code | Manufacturer | Function | Category |
| :--- | :--- | :--- | :--- |
| `*#899#` | **OPPO** | Engineering Mode | Engineering |
| `*983*3641#` | **ZTE** | Run Automatic Hardware Functional Test | Diagnostics |
| `*#*#49#*#*` | **INFINIX/TECNO** | Engineer Mode / Testing | Engineering |

***

## IV. Universal MMI Codes (Network & Call Management)

| Code | Function | Category | Notes |
| :--- | :--- | :--- | :--- |
| `*#21#` | Check Unconditional Call Forwarding Status | Call Management | See where calls are diverted to immediately. |
| `*#62#` | Check Call Forwarding When Unreachable Status | Call Management | See where calls go when the phone is off or out of range. |
| `*43#` | **Enable** Call Waiting | Call Management | Enables notification for an incoming second call. |
| `#43#` | **Disable** Call Waiting | Call Management | Disables the second incoming call notification. |
| `#31#` | Hide Caller ID (Temporary) | Call Management | Prevents your number from showing on the next outgoing call. |
| `*31#` | Show Caller ID (Temporary) | Call Management | Ensures your number shows on the next outgoing call. |
