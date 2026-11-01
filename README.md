# Fitting Room Desktop Downloads

## Full look update — Windows 0.2.0

Version 0.2.0 adds one combined preview with clothing, shoes, and jewelry.
The older 0.1.0 ZIP does not have the Full look controls.

The 0.2.0 Windows package has been prepared. It becomes publicly downloadable
after the ZIP is attached to its GitHub release and the release is published.
If 0.2.0 is not listed under releases yet, the upload is still pending.

## Install or update Windows

1. Open [Windows releases](https://github.com/learnsakshi93-ship-it/fitting-room-downloads/releases).
2. Choose version **0.2.0 or newer**. Under Assets, download
   **Fitting-Room-Windows-x64.zip**.
3. Extract the whole ZIP into a new folder. Do not run the executable from inside
   the compressed archive. Close the old app before launching the new one.
4. Run **Fitting Room.exe** from the extracted folder. The new package is
   preconfigured for the [published Fitting Room service](https://AIFittingRoom.replit.app).
5. Select **Full look**, upload a full-body photo showing your feet and the
   relevant jewelry area, then add separate clothing, shoe, and jewelry photos.
6. Click **See the fit** to generate one combined preview.

The updated backend must also be published. If you previously configured another
API address, use the desktop app's API configuration menu to change it.
There is no automatic desktop updater; existing users must download the new ZIP.

## Security and platform status

- This is an **unsigned Windows x64 portable build**. Windows may show a warning;
  run it only if you trust the source.
- It was packaged and checked for the new interface in the build environment,
  but has not been launched on a Windows machine here.
- No AI credentials are included.
- macOS installers are not included; they require a separate macOS build and signing.
- This repository contains download documentation, not the standalone app source.

## Which asset should I download?

Download **Fitting-Room-Windows-x64.zip** for the app. GitHub's automatic
**Source code (zip)** and **Source code (tar.gz)** contain this documentation
repository, not an executable. A SHA256SUMS file, when attached, lets you check the
download's integrity.

## SDKs are separate

Retailer developers can download [SDK release 0.2.0](https://github.com/learnsakshi93-ship-it/fitting-room-sdk/releases/tag/v0.2.0).
That SDK-only repository includes JavaScript and Android SDK code and Full look
instructions, not the standalone application or API server.
