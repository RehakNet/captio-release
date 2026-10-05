# Captio downloads

**Captio** turns the speech in your audio and video files into subtitles (`.srt`) and text (`.txt`), on your own Windows computer. Your recordings are never uploaded, and there are no per-minute fees: it is a one-time purchase.

This repository only hosts the Windows installers. Captio is commercial software and its source code is not published here.

## Download

Get the latest installer from **[Releases](https://github.com/RehakNet/captio-release/releases/latest)** and download `Captio-x.y.z-x64.msi`.

- **Requires:** 64-bit Windows 10 or 11, and a processor with AVX2 (Intel Haswell, 2013, or newer; AMD Ryzen or newer).
- **License:** Captio needs a license key to activate. Keys are sold on the Captio website. You only need to be online for the one-time activation.
- **Check your download:** every release lists the SHA-256 checksum of the installer. In PowerShell: `Get-FileHash .\Captio-x.y.z-x64.msi -Algorithm SHA256`.
- **Updating:** download the newest installer and run it. It replaces the installed version and keeps your settings and license.

## Support

support@rehaknet.com

## Third-party software

Captio includes open-source components (FFmpeg, whisper.cpp and others). Their licenses are in `THIRD-PARTY-NOTICES.txt` in the installation folder and in the app's About window. The source of the bundled FFmpeg build is available on request at the address above.

---

RehakIT vl. Bruno Rehak (RehakNet), Vinka Rehaka 17, 34550 Pakrac, Croatia
