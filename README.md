# TranslateMe — Releases

Public download host for the **TranslateMe** Windows installer.

TranslateMe is the #1 real-time translator for meetings — it translates your
speech into any language, in real time, so you can focus on the meeting, not the
language. The application source lives in a separate private repository; this
repo exists only to serve the installer as a publicly downloadable release asset.

## Download

**[Download TranslateMe for Windows](https://github.com/Falcon0000111111/translateme-releases/releases/latest/download/TranslateMe-Setup.exe)**

That link is **stable**: it always resolves to the latest release's
`TranslateMe-Setup.exe`, so the asset can be replaced in future releases without
the URL ever changing. The TranslateMe website's `Get for Windows` action points
at this URL (via a `/download/windows` redirect).

## Heads up: SmartScreen warning (unsigned MVP build)

The installer is **not yet code-signed**. On first download and run, Windows
SmartScreen may show a *"Windows protected your PC"* / *"unrecognized app"*
warning. This is expected for the unsigned MVP release. To proceed, choose
**More info → Run anyway**. Code signing is planned for a later release.

## Install

`TranslateMe-Setup.exe` is a one-click per-user installer — no administrator
rights required. It installs the app, adds a Start Menu shortcut, and registers
the `translateme://` handler used to return to the app after sign-in.
