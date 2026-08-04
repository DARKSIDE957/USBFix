# USB Fix All in One

A Windows app for USB sticks that Windows itself cannot fix.

When Disk Management fails, Format hangs, the drive shows as RAW, write protected, or 0 bytes, this tool steps in and tries the repair path that stubborn flash drives usually need.

Built especially for hard cases, including many SanDisk sticks that look dead in Explorer but still respond at the disk level.

## Download

Grab **USBFix.exe** from this repository, right click it, and run as Administrator.

No installer. One file. Self contained.

## What it does

**Finds your USB drives**
Lists classic USB storage, UASP sticks, and other USB backed disks Windows Storage reports. Shows size, filesystem, bus type, VID/PID, and health status.

**Quick Fix**
The main button. Clears software write protection, assigns a drive letter when needed, formats with the reliable Windows format path, and rebuilds the partition layout when the stick is too broken for a normal format.

**Advanced tools**
- Clear write protect
- Check disk (chkdsk)
- Clean and format
- Capacity probe to catch fake or failing flash

**Honest success check**
After a repair it writes a real test file. It does not trust Storage WMI alone, because some broken sticks lie and claim they are fine.

**Themes**
Black, White, or Match Windows. Match Windows follows your system light or dark app theme.

**Error reports**
If a fix still fails, you can copy or save a full report with drive identity, disk snapshot, and logs so someone can diagnose what the stick is doing.

## Who it is for

- People with a USB stick that Format and Disk Management cannot repair
- SanDisk and other brands stuck on write protect, RAW, or 0 byte capacity
- Anyone who wants one elevated tool instead of hunting through diskpart scripts by hand

## Safety

- Must run as Administrator
- Never targets the Windows system disk
- Asks for confirmation before any wipe
- Clean and format erase all data on the selected USB drive

## Requirements

- Windows 10 or Windows 11 (64 bit)
- Administrator rights

## Version

1.2.0

## License

Use at your own risk. USB hardware fails in messy ways. If the data matters, copy what you can recover before you wipe the drive.
