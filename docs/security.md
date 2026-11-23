# Security & verification

[← Overview](../README.md) · [Connection guide](connecting.md) · [Privacy](privacy.md)

## Practical safeguards

| Area | Protection |
|---|---|
| **Saved authorisation** | Sensitive local credentials are sealed with AES-GCM using Android Keystore-backed protection. App backup is disabled. |
| **TV access** | Pairing and debugging approval remain separate. Advanced actions require the corresponding authorised connection. |
| **Updates** | The private update path checks package identity, signing-certificate identity, file size and SHA-256 metadata before installation. Android enforces signature compatibility for upgrades. |
| **App imports** | Staged and extracted APKs have streamed byte and file-count limits, safe destination checks and partial-file cleanup. |
| **Images** | Large panoramic and portrait images are sampled before decoding to avoid unnecessary memory pressure. Normal 4K input remains unsampled. |
| **App boundaries** | Internal activities, update components and the sharing provider are not exported. Shared files are restricted to designated cache paths. |

Transport capabilities vary by TV and connection method. A working remote connection does not grant every device-management permission, and firmware restrictions still apply.

## Verification record

The reviewed implementation passed 331 transport-module tests and 49 focused app tests covering updates, protected key storage, TV access, PIN handling, input validation, imports and image sampling. These are local regression results, not a production penetration-test certificate. Release-specific packaging checks are recorded with each published build.

The dependency checks returned no advisories for the reviewed 91-package backend lockfile and 19 explicitly versioned direct Android dependencies. This does not cover every transitive Android dependency or guarantee that no vulnerability exists.

## Install with confidence

1. Download the production-signed APK from this repository's Releases page when available.
2. Compare its SHA-256 against the checksum published with that exact release.
3. Install through Android's package installer and review the requested permissions.
4. Approve only your own phone on the intended TV. Preserve the installed app when updating so its pairing state can be retained.

A checksum helps detect file changes; it is not a substitute for a trusted signing identity. Do not install a development/debug APK as a production update.

## Scope and reporting

No software can promise immunity from compromise. Physical-TV compatibility and production service configuration require their own verification. Local tests alone do not establish either.

For a suspected security problem, share the app version, affected feature and a redacted description through [private vulnerability reporting](https://github.com/its-faizal/FaizX-TV-Companion-Showcase/security/advisories/new). Do not post passwords, pairing tokens, private keys, personal files or unredacted diagnostics in public issues.

## Source availability

This app includes GPL-covered components. The relevant notices are retained in the application. Matching source is supplied separately with binary releases; it is not placed in the showcase file tree. Keys, private release credentials and internal records are excluded.
