# WinMTR-No-Official

Thank you for downloading WinMTR v0.93 Chinese version!
This is an unofficial Chinese translation version. If there is any infringement, please contact us for deletion.

## About

WinMTR is a free Microsoft Windows visual application that combines the functionality of the traceroute and ping in a single network diagnostic tool. WinMTR is Open Source Software, (barely) maintained by Dragos Manac.

It was started in 2000 by Vasile Laurentiu Stanimir as a clone for the popular Matt's Traceroute (hence MTR) Linux/UNIX utility.

## License & Redistribution

WinMTR is offered as Open Source Software under GPL v2.

- [Read more about the licensing conditions](http://www.gnu.org/licenses/gpl-2.0.html)
- [Download the code](https://github.com/WinMTR/WinMTR-Official)

## Installation

Select the version supported by your computer and click to download the.exe file below.



- [Go to Release_x32 Directory](./Release_x32)
- [Go to Release_x64 Directory](./Release_x64)


<<<<<<< HEAD
=======
- [Go to Release_x32 Directory](./Release_x32)
- [Go to Release_x64 Directory](./Release_x64)
>>>>>>> abd417d44a5d507a1718c5b2cc7e98cdf2a3d936




## Usage

### Visual

1. Start WinMTR
2. Write the name or IP of the host (e.g. `github.com`)
3. Press the **Options** button to configure ping size, maximum hops and ping interval (the defaults are OK)
4. Push the **Start** button and wait
5. Copy or export the results in text or HTML format — useful if you want to document or file a complaint with your ISP
6. Click on **Clear History** to remove the hosts you have previously traced

### Command Line
```
winmtr --help        # See available options
winmtr github.com    # Trace a host
```

## Changelog

| Date | Version | Changes |
|------|---------|---------|
| 2026-08-19 | v0.93 | 修改中文 |
| 2011-01-31 | v0.92 | Fixed reporting errors for very slow connections |
| 2011-01-11 | v0.91 | Released under GPL v2 by popular request |
| 2010-12-24 | v0.9 | Support for 32 and 64 bit OS. Works on Windows 7 as regular user. Various bug fixes. |
| 2002-01-20 | — | Last entered hosts and options now stored in registry. Moved to SourceForge. |
| 2001-09-05 | v0.7 | Combo box for host history. Fixed memory leak causing crashes. |
| 2000-11-27 | v0.6 | Added resizing support and flat buttons |
| 2000-11-26 | v0.5 | Copy to clipboard, save as text/HTML |
| 2000-08-03 | v0.4 | Double-click host for detailed info |
| 2000-08-02 | v0.3 | Fixed ICMP error codes handling |
| 2000-08-01 | v0.2 | Full command-line support |
| 2000-07-28 | v0.1 | First release |

## Bug Reports

Let us know if you identify bugs. Please include:

- WinMTR version
- Operating System and setup details

Before submitting, make sure it's not related to your specific configuration (antivirus, firewalls, etc.).

## Feature Requests

If you need functionality that others could also benefit from, let us know. We'll try to integrate it in future releases.

If you're a developer planning to extend the code, please reach out so we can integrate it into the official tree.


