# FrameFlow by Vertecza

**Record. Refine. Share.**

This public repository hosts desktop installers and release notes for FrameFlow. Application source and GitHub Actions live in a separate private repository.

Download installers from [Releases](https://github.com/vertecza/frameflow-releases/releases):

| Platform | Packages |
| --- | --- |
| Windows x64 | `.exe` installer |
| macOS Apple Silicon | `mac-arm64.dmg` / `.zip` |
| macOS Intel | `mac-x64.dmg` / `.zip` |
| Linux x64 | `.AppImage` / `.deb` |

Version 0.x is an engineering preview. Compilation is separate from native capture, permission, installer, and signing validation. Unsigned previews can trigger operating-system warnings. macOS requires version 13 or later; system sound requires macOS 14.2 or later and OS permission. Linux Wayland uses the system screen-sharing portal and has no pointer metadata in this preview.

FrameFlow has exactly two product plans: **FrameFlow Free** and **FrameFlow Pro**. The preview provides the local Free recording workflow. Pro activation and advanced features are planned.

Recordings stay on your computer. Project folders include unredacted originals; share the reviewed exported video, rather than a project folder, when protecting sensitive content.

Each release includes SHA-256 checksums and third-party license/build notices. FFmpeg is used as a separate encoder process; consult the attached notices for its GPL license and upstream source/build information.

No application source, recording, license key, signing certificate, or publishing token belongs in this repository. GitHub's automatic source archives contain only these public repository documents.
