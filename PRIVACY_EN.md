# Klone Launcher Privacy Policy

**Effective date:** November 17, 2026
**Last updated:** November 17, 2026

This Privacy Policy describes how **Klone Launcher** (the "Launcher", "Software") handles information when it is used on your device.

## 1. Core principle

Klone Launcher is a **local application**. We operate no servers, databases, or analytics systems. We **do not collect or store** any data about you on our servers — because no such servers exist. Requests to third-party services (see section 3) are made directly from your device.

## 2. Data stored on your device

The Launcher stores on your computer only the data required for it to function:

- **Minecraft account data** — username, UUID, and access tokens obtained via Microsoft authentication. Stored in the local database (`%APPDATA%\.klone` / `~/.klone` and similar directories).
- **Launcher settings** — game path, allocated memory, launch parameters, etc.
- **Local logs** — launch history and error messages, stored on your device.
- **Installed versions, modpacks, and Java** — game files in the standard `.minecraft` directory, the modpacks folder, and the Launcher's directory.

This data is used exclusively for the Launcher's operation and **never leaves your device** (except for the network requests described below).

## 3. Network requests to third parties

To perform its functions, the Launcher contacts third-party services. Those services process data under their own policies and, like any network service, can see your IP address.

| Service | Purpose | What is sent |
|---|---|---|
| Microsoft / Mojang (login.live.com, xboxlive.com, minecraftservices.com, piston-meta.mojang.com, libraries.minecraft.net) | Authentication, profile, Minecraft version downloads | Auth tokens, file download requests |
| Modrinth API (api.modrinth.com) | Modpack information and downloads | Search queries, project identifiers |
| CurseForge / Overwolf CDN | Modpack file downloads | File download requests |
| GitHub (github.com, api.github.com) | Checking for and downloading Launcher updates | Requests for release information and release files |
| Java sources (Mojang, Eclipse Adoptium) | Downloading a Java runtime | File download requests |
| Discord (local IPC channel) | Rich Presence — displaying game status | Application name, "In launcher" / "In game" status text, launched version ID |

We **do not send** your personal data to third parties beyond what is necessary to fulfill each request.

When you connect to Minecraft game servers, the server operator receives your username, UUID, and IP address. The Launcher does not control how servers handle this data.

## 4. Launcher's local server

To operate its interface, the Launcher runs an internal server reachable only on your computer (`127.0.0.1`). It does not accept connections from the network.

## 5. Discord Rich Presence

If Discord RPC is enabled in the settings, the Launcher reports the following to your local Discord client:

- the application name ("Klone Launcher");
- status text ("In launcher", "Launching game", "In game");
- the identifier of the launched Minecraft version;
- session start time.

This data is visible only to members of your Discord servers and on your Discord profile. You can disable the feature in the Launcher settings.

## 6. What we do NOT do

- No analytics, telemetry, or usage statistics;
- No advertising and no advertising SDKs;
- No cookies;
- No sharing of data with third parties for marketing;
- No registration on our own servers.

## 7. Data storage and protection

- All data is stored only on your device.
- Access tokens are stored in the Launcher's local database. Anyone who gains access to your OS profile or the `.klone` directory can use these tokens, so do not share such access with others.
- Logs may contain file paths (including your OS username). Review logs before publishing them, for example in GitHub Issues, and never post tokens.
- You can delete your account and all data at any time by removing the Launcher and the `%APPDATA%\.klone`, `~/.klone`, and `.minecraft` directories.

## 8. Your rights

Because we neither receive nor store your data, requests for access, correction, or deletion do not apply to us: you control all data yourself on your device. For data processed by third-party services (Microsoft, Modrinth, GitHub, etc.), contact them directly.

## 9. Children

The Launcher is not intended for children and does not knowingly collect personal information from minors. Use of Minecraft by minors is governed by Microsoft's rules.

## 10. Changes to this Policy

The current version of this Policy is always available in the project repository: https://github.com/DIMAPLAY1221/klone-launcher. The date of the last update is shown at the top of this document. Continued use of the Launcher after changes constitutes acceptance of the updated Policy.

## 11. Languages

This Policy is published in Russian and English. In case of discrepancy, the Russian version prevails.

## 12. Contact

For privacy-related questions, contact us via:

- GitHub Issues: https://github.com/DIMAPLAY1221/klone-launcher/issues

Do not post personal data or tokens in Issues.

---

*This document is provided for informational purposes and does not constitute legal advice.*
