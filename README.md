# USB Fix All in One

<p align="center">
  <strong>Repair stubborn USB sticks when Windows Format and Disk Management give up.</strong>
</p>

<p align="center">
  <a href="https://github.com/DARKSIDE957/USBFix/releases/latest"><img src="https://img.shields.io/github/v/release/DARKSIDE957/USBFix?style=for-the-badge&label=Download&color=C8102E" alt="Latest release"></a>
  <a href="https://github.com/DARKSIDE957/USBFix/releases/latest"><img src="https://img.shields.io/github/downloads/DARKSIDE957/USBFix/total?style=for-the-badge&color=141414" alt="Downloads"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%2F%2011-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="Windows">
  <img src="https://img.shields.io/badge/Admin-Required-C8102E?style=for-the-badge" alt="Admin required">
</p>

<p align="center">
  <a href="https://github.com/DARKSIDE957/USBFix/releases/latest"><strong>↓ Download USBFix.exe</strong></a>
</p>

---

## Why this exists

Some USB drives stop behaving like normal storage.

Windows shows them as RAW. Format fails. Disk Management hangs. The stick reports write protect or 0 bytes. Explorer looks useless, but the disk is still there.

**USB Fix All in One** is a single elevated Windows app built for those cases. It walks the repair path stubborn flash drives usually need, across SanDisk, Kingston, Lexar, Samsung, Transcend, PNY, Corsair, Sony, Toshiba/Kioxia, Phison/SMI OEM sticks, and unknowns.

No installer. One EXE. Run as Administrator.

## Download

1. Open the [latest release](https://github.com/DARKSIDE957/USBFix/releases/latest)
2. Download **USBFix.exe**
3. Right click the file and choose **Run as administrator**

Current version: **1.3.0**

## What you get

### Fix Everything
One primary button. Confirms the selected USB, clears software write protect, formats or rebuilds when needed, verifies with a real write test on that disk only, then health checks every USB on the PC. A live step log sits under the button so you can see each stage as it runs.

### Health scan
Every listed stick gets a real present + usable check. Badges show **OK**, **Not writable**, **No letter**, **Locked**, or **Missing**.

### Multi brand detection
VID and model catalog for SanDisk, Kingston, Lexar, Samsung, Transcend, PNY, Corsair, Sony, Kioxia/Toshiba, ADATA, Verbatim, Phison, Silicon Motion, Alcor, IronKey, and more. Unknown sticks still get the same repair path.

### Advanced tools
| Tool | Purpose |
| --- | --- |
| Clear write protect | Clears software write protect flags |
| Check disk | Runs chkdsk on the selected volume |
| Clean and format | Full wipe and rebuild of the USB disk |
| Capacity probe | Catches fake or failing flash with real read/write checks |
| Rescan | Forces Windows to refresh disks after a stick drops |

### Honest outcomes
After repair, the app writes a real test file on the selected disk. It never declares success from another stick’s drive letter. If the controller is hardware locked, you get a clear “dead / warranty” style message instead of a fake success.

### Updates
Use **Update** in the title bar to check GitHub Releases and install the latest EXE.

### Themes
Choose **Black**, **White**, or **Match Windows**. Match Windows follows your system light or dark app theme.

### Report a problem
If a fix fails, click **Report on GitHub**. The app opens a new issue with the exact USB device details already filled in (model, VID/PID, size, serial, and status), copies the full log to the clipboard, and lets you submit it in one step.

## Who it is for

- People stuck with a USB stick that Format and Disk Management cannot repair
- Sticks locked on write protect, RAW, or 0 byte capacity
- Anyone who wants one clean tool instead of hand writing diskpart scripts

## Safety

| Rule | Detail |
| --- | --- |
| Administrator | Required |
| System disk | Never targeted |
| Wipe confirm | Asked before any destructive rebuild |
| Data loss | Clean and format erase everything on the selected USB drive |

If the files matter, recover what you can before you wipe the stick.

## Requirements

- Windows 10 or Windows 11, 64 bit
- Administrator rights

## Please read this

This app is free to use.

Important points in plain words:

1. **You use it at your own risk.** If something goes wrong with your USB stick or your files, that risk is yours.
2. **Wiping deletes everything** on the USB stick you select. Save your files first if they still matter.
3. **Not every stick can be fixed.** If the chip inside the drive is broken or locked, no Windows app can bring it back.
4. **This is not a data recovery lab.** It tries to make the stick usable again. It does not promise to recover lost files.

If you are unsure, stop and get help before you wipe anything.
