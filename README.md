# Saturday — releases

Installers for **Saturday**, the local-first desktop agent from MershLab.

**Download:** [the latest release](https://github.com/MershLab/saturday-releases/releases/latest) · Website: <https://saturday.mershlab.com>

This repository holds release installers only; it contains no source code.
Each release lists the SHA-256 of every file it ships, so you can check what you downloaded:

```powershell
Get-FileHash "Saturday-Setup-x64.exe" -Algorithm SHA256
```

The Windows installer is not code-signed yet, so Windows SmartScreen will warn
you the first time: choose **More info → Run anyway**.

Questions and bug reports: open an [issue](https://github.com/MershLab/saturday-releases/issues).
