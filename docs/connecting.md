# Connect your TV

[← Overview](../README.md) · [Features](features.md)

## Before you begin

Use a phone running Android 8.0 or later and a compatible Android TV or Google TV. Connect them to the same local network. Guest Wi-Fi, device isolation and VPN routing can prevent discovery or pairing even when both devices can access the internet.

## Native Wi-Fi remote

1. Open FaizX TV Companion and choose your TV from discovery.
2. If needed, enter the TV's local address from its network settings.
3. Complete pairing with the code shown on the TV.
4. Open the remote and test a directional action, Back and volume.

Native remote pairing relies on the TV's compatible remote service. A manufacturer-specific remote protocol is not automatically supported because a TV has Wi-Fi.

## Optional ADB connection

ADB enables advanced management: app information, files, device statistics and supported pointer/capture actions. Enable the debugging option your TV provides, connect through the app and approve the TV's authorisation prompt. Wireless-debugging pairing and classic network debugging are different paths; use the one the TV actually exposes.

Approve persistent access only for your own trusted phone. If you uninstall the Companion or clear its data, the phone's local identity can be removed and pairing may be required again.

## If discovery is empty

Check that both devices use the same network rather than separate guest networks. Confirm the TV's address and try manual connection. Make sure the TV is awake and its required remote service is available. Grant local-network permission if your Android version requests it.

## If the remote works but management does not

A working native Wi-Fi remote does not establish ADB authorisation. Check the management connection and TV prompt separately. Some system paths and per-app statistics remain restricted even with an authorised connection.

## If mouse or capture is unavailable

Keep using directional remote mode. Pointer injection, screen recording and wake controls depend on OEM firmware; a successful connection alone does not guarantee those capabilities.

## Updating without losing settings

Use a signed build with the same application ID and trusted signing certificate as the installed app. A debug build cannot replace a production-signed install. Do not uninstall merely to bypass a signature mismatch if you need to preserve local settings and pairing records.
