# V8 Build Test installer for Windows

[Download installer](Installer-Windows.zip?raw=true) | [English PDF guide](Instructions-English.pdf)

For the matching Carlinkit Mini Ultra 3 in the **ly6238** hardware family. Build number is not used to select installation; the required hardware layout and program files are checked.

## Installation

1. Install 64-bit Python **3.11, 3.12 or 3.13** and download Zadig.
2. Download and extract the installer ZIP into a local folder.
3. Follow the PDF for the confirmed USB FEL entry. Remove the contact bridge. In Zadig, install **WinUSB** for **1F3A:EFE8**.
4. Open `Start-Windows.cmd`. Choose **1** to check the connection, then **2** to back up and install. Type **ULTRA3**, then **INSTALL**, when requested.
5. Reconnect normally when prompted. In Zadig, install **WinUSB** for **Audi-USB-Diagnose, 18D1:D002**.
6. Wait for **V8 BUILD TEST INSTALLED; BYTES AND BOOT VERIFIED**, then unplug and test in the parked Audi.

Keep the installer folder and its `private` folder. Choose **3** to continue after driver setup or **4** and **RESTORE** to restore your own original root filesystem.

The modification provides the V8 zoom, street/junction information and double-OK functions. The Windows installer and build **26022712.6238.2** are not yet physically tested.
