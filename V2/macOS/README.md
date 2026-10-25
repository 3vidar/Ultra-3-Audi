# V8 installer for macOS

[Download installer](Installer-macOS.zip?raw=true) | [English PDF guide](Instructions-English.pdf)

Build Test edition for matching Carlinkit Mini Ultra 3 hardware in the ly6238 family. The Audi cluster extension must already work over an iPhone cable.

## Installation

1. Download and extract the ZIP into a local folder.
2. Install Python 3.10+, Apple Command Line Tools, Homebrew `libusb` and Android Platform Tools as shown in the PDF.
3. Follow the PDF to enter the confirmed USB FEL mode. Remove the contact bridge before continuing.
4. Open `Start-Mac.command`. Type **YES** if setup asks. Select **1** to check the connection, then **2** to back up and install. Confirm with **ULTRA3**, then **INSTALL** when requested.
5. Reconnect normally when prompted. Wait for **V8 BUILD TEST INSTALLED; BYTES AND BOOT VERIFIED**.
6. Unplug and test in the parked Audi.

Keep the complete folder, including `private`, for recovery. Select **3** to resume activation or **4**, then **RESTORE**, to restore your own original root filesystem.

V8 restores steering-wheel zoom, street and junction information, and double-OK switching. These functions worked on the reference V8 setup; this adaptive installation flow and build **26022712.6238.2** have not been physically tested.
