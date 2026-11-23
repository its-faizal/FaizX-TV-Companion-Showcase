<p align="center"><strong>FAIZX TV COMPANION</strong></p>

<p align="center"><img src="docs/assets/hero.svg" alt="FaizX TV Companion. Your TV. In your hands." width="1200"></p>

<p align="center"><strong>One considered space for your TV.</strong><br>Navigate your screen, type from your phone, organise apps and move files in one focused workspace.</p>

<p align="center"><a href="#the-interface">Interface</a> · <a href="#start-with-your-tv">Get started</a> · <a href="docs/features.md">Explore features</a> · <a href="docs/security.md">Security</a> · <a href="https://github.com/its-faizal/FaizX-TV-Companion-Showcase/releases">Downloads</a></p>

<p align="center"><a href="https://github.com/its-faizal/FaizX-TV-Companion-Showcase/releases/download/v1.0.1/FaizX-Companion-v1.0.1-signed.apk"><strong>Download FaizX Companion 1.0.1</strong></a><br>Android 8.0+ · 13.5 MB · Production-signed</p>

---

## Everyday control, with room to do more

FaizX brings remote control and TV management together without putting every tool in your way. Use the circular pad for navigation, switch to pointer control when your TV supports it, and keep typing, volume and shortcuts within reach.

| Control your screen | Understand your TV | Make it your space |
| :--- | :--- | :--- |
| Circular remote and mouse modes. Keyboard input, voice entry, volume gestures and quick app access. | CPU, memory and storage views, app information and internal or connected storage browsing. | Transfer files, manage apps, set supported FaizX wallpapers and access launcher updates. |

## The interface

<table>
<tr>
<td width="33%" align="center"><a href="docs/assets/screens/remote.png"><img src="docs/assets/screens/remote.png" alt="FaizX circular remote — current development interface with demonstration data" width="260"></a><br><strong>Circular remote</strong></td>
<td width="33%" align="center"><a href="docs/assets/screens/discover.png"><img src="docs/assets/screens/discover.png" alt="FaizX connect your tv — current development interface with demonstration data" width="260"></a><br><strong>Connect your TV</strong></td>
<td width="33%" align="center"><a href="docs/assets/screens/overview.png"><img src="docs/assets/screens/overview.png" alt="FaizX your space — current development interface with demonstration data" width="260"></a><br><strong>Your space</strong></td>
</tr>
<tr>
<td width="33%" align="center"><a href="docs/assets/screens/apps.png"><img src="docs/assets/screens/apps.png" alt="FaizX app library — current development interface with demonstration data" width="260"></a><br><strong>App library</strong></td>
<td width="33%" align="center"><a href="docs/assets/screens/files.png"><img src="docs/assets/screens/files.png" alt="FaizX files & transfers — current development interface with demonstration data" width="260"></a><br><strong>Files & transfers</strong></td>
<td width="33%" align="center"><a href="docs/assets/screens/welcome.png"><img src="docs/assets/screens/welcome.png" alt="FaizX first-run setup — current development interface with demonstration data" width="260"></a><br><strong>First-run setup</strong></td>
</tr>
</table>

*Interface previews are freshly rendered from the current development source with demonstration data. They illustrate the app; they are not a claim of pairing or compatibility with every TV. Previews show development screens; available builds may differ.*

## Start with your TV

<img src="docs/assets/connection-flow.svg" alt="Discover your TV on the same Wi-Fi, approve pairing, then start using the remote." width="1200">

1. **Connect both devices to the same local network.** Open FaizX and select your TV. You can enter an address if discovery does not find it.
2. **Approve the connection on the TV.** Native Wi-Fi remote pairing uses the TV's displayed code. Advanced device-management tools use a separately authorised ADB connection.
3. **Open Control TV.** Use the pad, typing field and volume controls. Open the workspace when you need apps, files or device information.

[Connection guide and troubleshooting →](docs/connecting.md)

## Choose the tools you need

| Feature | What it does | Connection or device requirement |
| :--- | :--- | :--- |
| **Remote & typing** | Directional navigation, select, Back, Home, volume and text entry. | Compatible native Wi-Fi remote service or authorised ADB. |
| **Pointer mode** | Mouse movement, clicks, holds and separate directional rails. | Authorised ADB and a TV firmware input interface that supports it. |
| **Voice & shortcuts** | Dictate text and open TV apps from the phone. Cast opens the phone's system Cast controls. | Microphone permission for voice; compatible phone services and TV connection. |
| **Apps & device tools** | Browse apps, inspect details and use supported maintenance actions. | Authorised ADB; system protections and vendor restrictions still apply. |
| **Files & transfers** | Browse storage and move files between your phone and TV. | Authorised ADB; writable storage and file permissions. |
| **Device health** | View TV-reported CPU, RAM and storage information. | Authorised ADB. Detail and refresh availability depend on the TV. |
| **Capture tools** | Request screenshots or recordings and select an available destination. | TV capture and encoder support. Protected content may not be capturable. |
| **FaizX TV integration** | Manage supported launcher installation, wallpapers and approved updates. | Compatible FaizX TV launcher and authorised update access where required. |

[Full feature guide →](docs/features.md)

## Thoughtful by design

A quiet dark palette, clear hierarchy and a circular control surface keep the remote focused. Open the workspace for app management, storage and transfers; return to the controls without changing the visual language.

## Built around your permission

- **You approve TV access.** Debugging authorisation is separate from normal native remote pairing.
- **A clear separation of roles.** The Companion phone app, TV launcher and update service are separate components.
- **Updates are checked before installation.** Use the intended package and signing identity; Android asks you to confirm installation.
- **Voice is your choice.** Speech recognition uses the service configured on your phone, subject to that service's availability and privacy behaviour.

Read the [Privacy Policy](docs/privacy.md) and [Terms of Use](docs/terms.md) for the app's detailed terms. Never include passwords, pairing codes, private keys or unsanitised device logs in an issue.

## Compatibility

**Phone:** Android 8.0 or newer. **TV:** compatible Android TV or Google TV devices, with features determined by their remote service, firmware and granted permissions. Native remote control does not require TV root. ADB is optional for normal Wi-Fi control and required for the advanced management paths described above.

FaizX does not claim compatibility with every proprietary smart-TV operating system. A feature being visible in the interface does not override restrictions imposed by the TV.

## About this repository

This is the product showcase for FaizX TV Companion. It contains product information, interface previews and user guides. The file tree contains no application source, backend configuration, credentials or internal development records. Matching source packages accompany published software releases as separate downloads where required by their licences.

## Downloads & support

**Available now: 1.0.1**, released 23 November 2026. Download the [production-signed APK](https://github.com/its-faizal/FaizX-TV-Companion-Showcase/releases/download/v1.0.1/FaizX-Companion-v1.0.1-signed.apk) for Android 8.0 or newer.

[Release notes](https://github.com/its-faizal/FaizX-TV-Companion-Showcase/releases/tag/v1.0.1) · [SHA-256 checksums](https://github.com/its-faizal/FaizX-TV-Companion-Showcase/releases/download/v1.0.1/SHA256SUMS.txt) · [Signature & packaging verification](https://github.com/its-faizal/FaizX-TV-Companion-Showcase/releases/download/v1.0.1/RELEASE-VERIFICATION.json) · [Matching application source](https://github.com/its-faizal/FaizX-TV-Companion-Showcase/releases/download/v1.0.1/FaizX-Companion-v1.0.1-source.zip)

Use only the signed APK for a normal installation. Keep the existing app installed when updating: Android requires a compatible package and signing certificate to preserve its data. Review the [security and verification notes](docs/security.md) and [changes](CHANGELOG.md) before installing.

For help connecting a TV, start with the [connection guide](docs/connecting.md). When reporting a problem, include the app version, TV model and steps to reproduce it. Remove device addresses, pairing codes, personal information and private logs before sharing a report.

## Privacy & terms

Read the [Privacy Policy](docs/privacy.md) and [Terms of Use](docs/terms.md). Software licence acknowledgements are provided with the application. Third-party app names and logos in demonstration screens identify their respective services and do not imply endorsement.
