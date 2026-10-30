# Mandate for Apple Silicon

![agentleFS logo](assets/afs-icon.png)

Mandate connects to **[agentlefs.com production](https://agentlefs.com)** with your production AgentleFS account and Clerk sign-in. The desktop window opens **[mandate.agentlefs.com](https://mandate.agentlefs.com)**.

**[Download the Apple Silicon Mac app](https://github.com/agentleFS/mandate-downloads/releases/tag/0.13.7-unsigned)** · M1 and later · DMG or ZIP

## Open this unsigned app on your Mac

1. Open the downloaded DMG and drag **Mandate** to **Applications**. For the ZIP, extract it and move Mandate to Applications.
2. Try opening **Applications → Mandate**. Dismiss the warning if macOS blocks the app because its developer cannot be verified or Apple cannot check it.
3. Go to **Apple menu → System Settings → Privacy & Security**. Under **Security**, find Mandate's blocked-app message and click **Open Anyway**.
4. Authenticate with your Mac password or Touch ID if requested, then click **Open**. Future launches work normally from Applications.

This release is **not Developer ID signed or notarized**. It uses an ad-hoc signature for Apple Silicon execution. Use Open Anyway only for the Mandate app downloaded from this repository. If the button is absent, attempt to open Mandate again, then return to Privacy & Security. A managed Mac may require help from its administrator.

[Apple's opening instructions](https://support.apple.com/en-us/102445).

Each release includes **SHA256SUMS** to verify its downloads. Application source is maintained separately in a private repository. Apple signing and notarization setup will follow later.

## Updates in the app

Version 0.13.7 includes the AFS app icon and **Mandate → Check for Updates…**. Updates are downloaded and verified in the app; choose **Quit and Open Installer**, then copy the new app to Applications and reopen it. Install the latest version manually once if you are upgrading from 0.13.3.

## Sign in with passkeys

Mandate opens AgentleFS sign-in in your default browser. Complete Google sign-in there using your browser's normal passkey, Touch ID or password-manager support. In 0.13.7, sign-in started in the desktop app brings Mandate back to the foreground after verification. The browser completion page offers **Return to Mandate app**; you can close that tab afterward. Sign-in started in the website returns to its **Connections** page. Failed sign-in provides a recovery action for the original experience. If a sign-in was saved before restarting the app, start a fresh sign-in when prompted.

## Loading and fresh page state

Sessions, Decisions and Connections show loading or refreshing feedback immediately. Returning to a page or session context fetches current data, keeps confirmed content visible during refresh, and preserves unsent drafts and selections. Failed reads show an error and recovery guidance instead of an empty page.
