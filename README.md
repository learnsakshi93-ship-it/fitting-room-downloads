# Fitting Room Desktop Downloads

## Install the Windows app

1. Open the [latest release](https://github.com/learnsakshi93-ship-it/fitting-room-downloads/releases/latest).
2. Under **Assets**, download **Fitting-Room-Windows-x64.zip** only.
3. Extract the whole ZIP, then run **Fitting Room.exe** from the extracted folder.
4. On first launch, enter the HTTPS origin for the deployed Fitting Room API, for example `https://api.example.com`. Enter the API origin, not the `/api/try-on` path.
5. Choose a category, select a photo of yourself and a product photo, and create the preview.

The current Windows package is unsigned, so Windows may show a security warning. Run it only if you trust the source. macOS is not included in this release.

## Why are there three assets?

Download **Fitting-Room-Windows-x64.zip**. GitHub automatically adds **Source code (zip)** and **Source code (tar.gz)** to releases. Those are repository source archives, not app installers; they do not replace the Windows ZIP.

The API must be publicly reachable over HTTPS. The API origin is public configuration, not a password or AI credential.