# AMD-YL Game Studio Releases

Official public release channel for **AMD-YL Game Studio**.

This repository is intentionally limited to release metadata and distributable builds. The application source code is not published here.

## Update channel

AMD-YL Game Studio checks:

`update-preview.json`

The manifest identifies the newest Preview build, its download location, file size, and SHA-256. Game Studio verifies the downloaded installer against that SHA-256 before any update is started.

## Security

- No telemetry is hosted here.
- No save files or user data are uploaded here.
- Release binaries are distributed separately from the source project.
- Windows builds remain unsigned until a legitimate Authenticode certificate is available.
