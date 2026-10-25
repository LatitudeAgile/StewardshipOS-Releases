# StewardshipOS

Downloads for StewardshipOS, a desktop app for Windows, macOS and Linux.

## Download

Get the latest version from the [Releases page](https://github.com/LatitudeAgile/StewardshipOS-Releases/releases/latest).
Each release's notes link straight to its downloads. In the file list below the notes, GitHub
may tuck some files under "Show all assets".

| Computer | File |
|---|---|
| Windows | `StewardshipOS-<version>-win-setup.exe` (installs for you only; no administrator rights needed) |
| Mac with Apple silicon (M1 or later) | `StewardshipOS-<version>-mac-arm64.dmg` |
| Mac with Intel | `StewardshipOS-<version>-mac-x64.dmg` |
| Linux (64-bit) | `StewardshipOS-<version>-linux-x86_64.AppImage` (runs without installing) |

On a Mac, open the `.dmg` and drag StewardshipOS to Applications.

The `.zip`, `.blockmap` and `.yml` files, and GitHub's automatic "Source code" archives, aren't
needed: the app uses some of them to update itself.

## Opening it the first time

The app isn't signed with a paid certificate yet, so your computer asks before opening it:

- **Windows:** if you see "Windows protected your PC", choose **More info**, then **Run anyway**.
- **Mac:** open the app once, then go to **System Settings > Privacy & Security** and choose
  **Open Anyway**.
- **Linux:** make the AppImage executable (in your file manager's **Properties > Permissions**,
  or `chmod +x` in a terminal), then open it. Some distributions need FUSE first (the `libfuse2`
  package).

## Updates

After the first install, StewardshipOS updates itself. On Linux, that starts with the release
after 1.2.0: download that one by hand once.
