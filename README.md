# ECU Diagnostic & Remapping Tool

Windows desktop engineering portfolio project for Honda motorcycle ECU diagnostic and remapping workflow.

## Project Focus

- Desktop engineering application for Windows
- C# / .NET WinForms-style executable application
- FTDI hardware integration
- USB-to-K-Line ECU communication workflow
- Diagnostic scanner and remapping flasher workflow
- Private source code with controlled executable package for recruiter review

## Folder Guide

```text
ecu-diagnostic-remapping/
├── README.md
├── DISCLAIMER.md
├── index.html
├── app/
├── screenshots/
├── video/
├── docs/
├── data/
└── download-package/
```

## Main Application Files

The executable files are located in the `app/` folder:

```text
app/
├── SCANNER BY FRENGKI.exe
├── FLASHER BY FRENGKI.exe
└── FTD2XX_NET.dll
```

Keep `FTD2XX_NET.dll` in the same folder as the executable files when running the application.

## Review Materials

- Portfolio page: `index.html`
- Project walkthrough video: `video/ecu-diagnostic-remapping-walkthrough.mp4`
- User guide: `docs/ECU-Diagnostic-Remapping-User-Guide-ID.pdf`
- Download package: `download-package/ecu-diagnostic-remapping.zip`

## Hardware Requirement for Full Functionality

Full functionality requires:

- Windows laptop or PC
- .NET Framework support
- FTDI driver
- FTDI USB interface
- USB-to-K-Line module
- Compatible Honda ECU
- Stable 12V power supply
- Correct K-Line, 12V, and GND connection

Without hardware, the project can still be reviewed through the portfolio page, screenshots, user guide, and walkthrough video.

## Private Boundary

Source code, ECU BIN/XDF files, ECU backups, checksum logic, seed/key handling, and internal flashing implementation are not publicly disclosed for safety and confidentiality reasons.
