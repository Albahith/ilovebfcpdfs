# iLoveBFCpdfs

PDF tools that never leave your device.

Created by Abdulla Albraheem, 2026.

**[Download the latest version](https://github.com/Albahith/ilovebfcpdfs/releases/latest)** — Windows 10 or 11, 64-bit.

This repository hosts the downloads. The source is not published.

---

## What it does

Merge, split and compress PDFs. Convert between PDF, Word, Excel and JPG. Read scanned pages with built-in text recognition, in English and Arabic.

All of it runs on your own computer. There is no account, nothing is uploaded, and every tool works with no internet connection at all.

## Installing

Run the `.exe` from the [latest release](https://github.com/Albahith/ilovebfcpdfs/releases/latest). It installs for the current user, so Windows will not ask for an administrator password.

### The SmartScreen warning

Windows will show **"Windows protected your PC"**. Press **More info**, then **Run anyway**.

That warning does not mean something is wrong with the file. It means the installer is not code signed, so Windows has no publisher to attribute it to and has not seen the file often enough to recognise it. Code signing requires a certificate issued to a verified identity, which is a paid, yearly thing; until that is in place the warning will appear.

What you can do instead is check that the file you downloaded is the file that was built. Every release publishes a SHA-256 checksum:

```powershell
Get-FileHash .\iLoveBFCpdfs_0.1.0_x64-setup.exe -Algorithm SHA256
```

If it matches the one on the release page, the file was not altered on its way to you.

## Updates

Open the **ⓘ** button in the top right of the app and press **Check for updates**.

That check is the only thing in the application that uses the internet, and it only happens when you press it. It sends a version number — never a file, a filename, or anything about you. Any update it offers is verified against a key built into the app before it is installed, so a tampered download is refused rather than run.

## Privacy

Your documents are opened, changed and saved by the app, on your machine. They are never transmitted anywhere.

The application stores nothing except what you opt into: your theme, your chosen output folder, and a list of recently used file names. File contents are never saved. Clearing that list is one click, and turning it off stops it being written at all.

## Reporting a problem

Use **Contact** inside the app — it fills in the version and system details so they do not have to be asked for. It opens a message in your own email program; nothing is sent without you pressing send.

You can also open an [issue](https://github.com/Albahith/ilovebfcpdfs/issues).

## Licence

MIT. Copyright © 2026 Abdulla Albraheem.
