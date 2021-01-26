# OS-Archive
An archive of operating system versions.

## This is an automated collection of operating systems.
In short, this repository contains:
- Most popular linux distros (an effort is underway to get ALL of them)
- All windows versions
- All Windows 10 Versions
- Some original OEM DOS versions
- OS/2 and other early operating systems

Most versions are collected and uploaded automatically by a bot. However some older operating systems are uploaded automatically.

## Navigating the archive
Operating systems are stored under the following conventions:
Company/Operating System Name/Version/x64-x86/Company-OSName-Version-Bit.json
If the OS is not produced by a corporation and is instead produced as an open source project, the company is ommited. Examples:
- Microsoft/Windows 10/20H2/x64/Microsoft-Windows_10-20H2-x64.json
- Arch Linux/2020-01-01/x64/ArchLinux-2020_01_021-x64.json

An operating system can be referenced under the following convention:
Company.Name.Version.Bitlevel
Again, omit company if nessecary.
Examples:
- Microsoft.Windows10.20H2.x64
- ArchLinux.2020-01-01.x64

Please note that some older operating systems require a certain OEM motherboard to work. Compaq images are provided in this repository.

## How to download an operating system
Access to the archive is achieved through a small python script due to the Git size limitations. To download Windows 10 20H2 multibit, for example, first get the archive identifier, or OSA-ID.
For example, this is the identifier for windows 10 20h2 multibit:
Microsoft.Windows10.20H2.x86-64

To download this OS:
```
python os-archive.py --identifier Microsoft.Windows10.20H2.x86-64 --output ./Windows 10.iso
```

You can also manually download it from the JSON file. The url is contained within this JSON file.

## Full list of included operating systems:
- MS-DOS 1.25
- MS-DOS 2.12
- MS-DOS 3.31
- MS-DOS 4.01
- MS-DOS 5.00
- MS-DOS 6.01
- MS-DOS 6.22
- MS-DOS 7.10
- OS/2 1.00
- OS/2 1.30
- OS/2 2.0
- OS/2 2.1
- OS/2 Warp 3.0
- OS/2 Warp 4.0
- OS/2 Warp 4.52
- eComStation 2.1
- Windows 1.01
- Windows 2.03
- Windows NT 3.1
- Windows 95
- Windows NT 4.0
- Windows 98
- Windows 2000
- Windows ME
- Windows XP (x86-64)
- Windows Vista (x86-64)
- Windows 7 (x86-64)
- Windows 8.1 (x86-64)
- Aero 10 LTSB (x64)
- Windows 10 (1803, x86-64)
- Windows 10 (1809, x86-64)
- Windows 10 (1903, x86-64)
- Windows 10 (1909, x86-64)
- Windows 10 (2004, x86-64)
