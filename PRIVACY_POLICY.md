# Privacy Policy — Spooky Stories

**Last updated:** March 23, 2026  

**Applies to:** the Spooky Stories game as distributed for **Android** (Google Play).

---

## Summary

Spooky Stories is designed to work **without accounts, sign-in, or our servers**. We **do not** run analytics, ads, or crash-reporting services in the app as published from this project. Information you create while playing (such as saved games and deck progress) stays **on your device** unless your **device or browser** syncs or backs it up through **Google, Apple, or another provider you use**—that is outside our control.

---

## Who we are

The app is published as **Spooky Stories** (package / listing identifiers may include `com.spookystories.app` on Android).  

**Contact:**
spooky-stories-app@googlegroups.com

---

## What data the app processes

### Data stored locally on your device

- **Game state:** current card index, shuffled deck order, and optional **saved games** (story progress) are stored using **browser or WebView storage** (e.g. `localStorage` in the web/extension build, equivalent storage in the embedded WebView on Android).
- **Same-deck codes:** if you enter or generate a shared play code, it is used **only on-device** to derive a deck order; it is **not** sent to us.

We **do not** receive this data on our own systems because **we do not operate a backend** for gameplay in the builds described above.

### Data we do not intentionally collect

We do **not** intentionally:

- Ask for your name, email, phone number, or precise location for the core game  
- Sell your personal information  
- Use advertising or marketing SDKs in the open-source build  
- Use in-app analytics or crash SDKs in the open-source build  

If a **specific store build** ever adds optional services (e.g. Play app signing, store-provided crash reports), **Google** or **other platform providers** may process data under **their** policies; that is separate from data sent to us.

---

## Network access

### Android app

The Android app may declare **`INTERNET`** permission (common for WebView-based shells). **Gameplay assets are bundled locally** in the release described in this repository; the app is not designed to load remote game code or send your saves to our servers.

Your device may still use the network for **operating-system or Play Store services** (updates, security, backups if enabled).

---

## Backups and device sync

- **Android:** If **backup** or **device transfer** is enabled, your OS may copy app data (including WebView storage) according to **Google’s** and your **device settings**.  

We do not control those features.

---

## Children’s privacy

The game is a **light spooky storytelling party game** (not graphic violence). It is **not** directed at collecting information from children. We do not knowingly ask children for personal information. If you believe we have inadvertently collected such information, contact us via the GitHub repository above.

---

## Third-party content and inspiration

The app may reference that it is **inspired by** a commercial storytelling card game and states **no affiliation** with the publisher. That is for **clarity only** and does not imply endorsement.

---

## Changes to this policy

We may update this policy when the app or store requirements change. The **“Last updated”** date at the top will change when we do. Continued use of the app after changes means you accept the updated policy.

---

## Your rights

Depending on where you live (for example the **EEA** or **UK**), you may have rights to access, correct, delete, or restrict processing of personal data. **Because we do not operate a central account system or receive your gameplay data**, most requests are best handled **on your device** (clear app data / uninstall / clear extension storage) or with **Google** for Play or account-related processing.

For questions, contact the email address above.

---

*This policy describes the open-source project’s intent and typical behavior. It is not legal advice.*
