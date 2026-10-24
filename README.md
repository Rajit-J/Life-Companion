# Life Companion

A lightweight browser-based task and habit companion built with plain HTML, CSS, and JavaScript.

## Features

- Task and habit tracking interface.
- Browser-based data storage.
- No backend, build tool, or package installation required.

## Run locally on Windows

Open PowerShell in the repository root:

```powershell
py -m http.server 5174 --bind 127.0.0.1
```

Open [http://127.0.0.1:5174](http://127.0.0.1:5174). Stop the local server with **Ctrl+C**. You can also open `index.html` directly, though serving over HTTP is recommended.

## Technology

- HTML
- CSS
- JavaScript

The Font Awesome stylesheet is loaded from a CDN, so icons may require an internet connection. App data is stored in the browser and is not automatically backed up or synchronized.

## Before publishing

Confirm that images, fonts, and other bundled assets may be redistributed. No license is included; add one only after confirming ownership and terms.
