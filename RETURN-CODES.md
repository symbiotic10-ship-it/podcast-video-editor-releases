# Podcast Video Editor – Installer return codes

Applies to: `PodcastVideoEditorSetup-1.0.0.exe` (NSIS installer, x64)

Silent install command: `PodcastVideoEditorSetup-1.0.0.exe /S`

| Return code | Meaning |
|---|---|
| `0` | Installation successful. Also returned when an existing installation is updated or reinstalled. |
| `1` | Installation cancelled by the user. |
| `2` | Installation aborted by the installer. This happens when another instance of the installer is already running, or when a previous version could not be uninstalled. Close other installer windows and try again. |

Any other non-zero value indicates the installer could not complete. Re-run the installer, and if the problem continues, contact support.

Notes:
- The installer is fully offline; it does not download anything during installation.
- The installer does not require a reboot.