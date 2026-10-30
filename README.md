# Mandate for Apple Silicon

![agentleFS logo](assets/afs-icon.png)

Mandate connects to **[agentlefs.com production](https://agentlefs.com)** with your production AgentleFS account and Clerk sign-in. The desktop window opens **[mandate.agentlefs.com](https://mandate.agentlefs.com)**.

**[Download the Apple Silicon Mac app](https://github.com/agentleFS/mandate-downloads/releases/tag/0.13.5-unsigned)** · M1 and later · DMG or ZIP

## Open this unsigned app on your Mac

1. Open the downloaded DMG and drag **Mandate** to **Applications**. For the ZIP, extract it and move Mandate to Applications.
2. Try opening **Applications → Mandate**. Dismiss the warning if macOS blocks the app because its developer cannot be verified or Apple cannot check it.
3. Go to **Apple menu → System Settings → Privacy & Security**. Under **Security**, find Mandate's blocked-app message and click **Open Anyway**.
4. Authenticate with your Mac password or Touch ID if requested, then click **Open**. Future launches work normally from Applications.

This release is **not Developer ID signed or notarized**. It uses an ad-hoc signature for Apple Silicon execution. Use Open Anyway only for the Mandate app downloaded from this repository. If the button is absent, attempt to open Mandate again, then return to Privacy & Security. A managed Mac may require help from its administrator.

[Apple's opening instructions](https://support.apple.com/en-us/102445).

Each release includes **SHA256SUMS** to verify its downloads. Application source is maintained separately in a private repository. Apple signing and notarization setup will follow later.

## Updates in the app

Version 0.13.5 includes the AFS app icon and **Mandate → Check for Updates…**. Updates are downloaded and verified in the app; choose **Quit and Open Installer**, then copy the new app to Applications and reopen it. Install the latest version manually once if you are upgrading from 0.13.3.

## Sign in with passkeys

Mandate 0.13.5 opens AgentleFS sign-in in your default browser. Complete Google sign-in there using your browser's normal passkey, Touch ID or password-manager support. After the connection is verified, Mandate returns to Connections. If a sign-in was saved before restarting the app, start a fresh sign-in when prompted.
