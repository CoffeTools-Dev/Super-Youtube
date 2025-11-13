# Privacy Policy - Super YouTube

**Last updated:** November 13, 2025

---

## 📋 About the Extension

**Super YouTube** ("extension", "we", "our") is a browser extension developed by **CoffeTools** that adds advanced features to YouTube, enhancing the viewing and navigation experience.

This Privacy Policy describes how the extension handles user data.

---

## 🔒 Privacy Commitment

### Super YouTube does NOT collect, store, transmit, or share ANY personal data or browsing information from users.

The extension does not have:
- ❌ Own servers
- ❌ Analytics or tracking
- ❌ Third-party cookies
- ❌ External connections (except specified public APIs)

---

## 💾 Locally Stored Data

The extension stores **ONLY** on the user's device (using `chrome.storage.sync`):

### User Settings
- **Feature preferences:** Which features are enabled/disabled
- **Default quality:** Video quality preference (auto, 1080p, etc.)
- **Default speed:** Playback speed preference (1x, 1.5x, etc.)
- **Content filters:** List of blocked keywords and channels (user-defined)

### Characteristics of this data:
- ✅ Stored **ONLY locally** on the user's browser
- ✅ Synced across devices of the same user (via Chrome Sync)
- ❌ **NEVER** sent to CoffeTools servers
- ❌ **NEVER** shared with third parties
- ✅ Can be deleted at any time by the user (clearing extension data)

---

## 🔐 Requested Permissions

The extension requests the following Chrome permissions:

### 1. `storage`
- **Purpose:** Store user preferences and settings locally
- **Usage:** Save data on user's device using `chrome.storage.sync`
- **Data sent:** None. Everything stays local or synced by Google Chrome
- **Data accessed:** Only the extension's own settings

### 2. `tabs`
- **Purpose:** Detect when user navigates on YouTube pages
- **Usage:** Reinitialize features after navigation (YouTube is SPA)
- **Data accessed:** Tab URL (only to check if it's youtube.com)
- **Data sent:** None

### 3. `contextMenus`
- **Purpose:** Add options to context menu (right-click)
- **Usage:** Create quick shortcuts (screenshot, loop, settings)
- **Data accessed:** None
- **Data sent:** None

### 4. Host Permission: `*://*.youtube.com/*`
- **Purpose:** Execute scripts only on YouTube pages
- **Usage:** Add buttons, modify interface, apply features
- **Data accessed:** YouTube page DOM structure (read-only)
- **Data sent:** None

### 5. Host Permission: `https://sponsor.ajay.app/*`
- **Purpose:** SponsorBlock integration (skip sponsors)
- **Usage:** Fetch sponsor segments marked by community
- **Data sent:** Only YouTube video ID (public information)
- **Data received:** List of sponsor timestamps (public data)
- **Note:** SponsorBlock is a third-party service. See their privacy policy at: https://sponsor.ajay.app/privacy

---

## 🚫 What We DON'T Do

### Super YouTube does NOT:
- ❌ Collect browsing history
- ❌ Track watched videos
- ❌ Monitor user activity
- ❌ Collect personal data (name, email, etc.)
- ❌ Use tracking cookies
- ❌ Send data to own servers
- ❌ Share data with third parties (except public SponsorBlock)
- ❌ Sell or rent user information
- ❌ Display ads
- ❌ Monetize user data

---

## 🌐 Data Sharing

### Super YouTube does NOT share, sell, rent, or transfer user data to third parties.

The extension has no integration with:
- ❌ Analytics services (Google Analytics, etc.)
- ❌ Advertising networks
- ❌ Tracking services
- ❌ Monetization platforms

### Exception: SponsorBlock (Optional)
- If user enables "Skip Sponsors" feature
- Extension fetches public data from SponsorBlock API
- **Data sent:** Only YouTube video ID (public information)
- **Data received:** Sponsor timestamps (marked by community)
- This feature is **disabled by default**
- User has full control to enable/disable

---

## 🛡️ Security

Since the extension **does not collect or transmit personal data**, there is no risk of private information leakage.

All settings remain on the user's device, protected by Chrome browser.

### Security Measures:
- ✅ Auditable code (will be open source)
- ✅ Manifest V3 (most secure version)
- ✅ Minimum required permissions
- ✅ No remote code execution
- ✅ No `eval()` or dangerous dynamic strings
- ✅ Content Security Policy respected

---

## 🔄 Policy Updates

This policy may be updated occasionally to reflect changes in the extension.

The **"Last updated"** date will always be visible at the top of this page.

Significant changes will be communicated:
- In the Chrome Web Store extension description
- In the extension's CHANGELOG
- In the official repository (when available)

---

## 📜 Legal Compliance

This extension complies with:
- ✅ **Google Chrome Web Store Privacy Policies**
- ✅ **GDPR** (General Data Protection Regulation - European Union)
- ✅ **CCPA** (California Consumer Privacy Act - USA)
- ✅ **LGPD** (Lei Geral de Proteção de Dados - Brazil)

---

## 🔓 Transparency and Open Source

The extension's source code will be publicly available, allowing:
- ✅ Complete security audit
- ✅ Verification of no data collection
- ✅ Community contributions
- ✅ Full transparency about functionality

**License:** MIT (Open Source)

---

## 👤 User Rights

Users have the right to:

### 1. Full Control
- ✅ Enable/disable any feature
- ✅ Configure preferences individually
- ✅ Choose which features to use

### 2. Data Deletion
- ✅ Clear settings at any time
- ✅ Uninstall extension (removes all local data)
- ✅ Reset to factory defaults (Reset button)

### 3. Transparency
- ✅ Access extension source code
- ✅ Verify requested permissions
- ✅ Understand exactly what each feature does

### 4. Privacy
- ✅ Use extension without creating account
- ✅ No personal information required
- ✅ Incognito mode fully supported

---

## 📞 Contact

For privacy questions, support, or suggestions:

### GitHub
- **Issues:** [github.com/coffetools-dev/super-youtube/issues](https://github.com/coffetools-dev/super-youtube/issues)
- **Discussions:** [github.com/coffetools-dev/super-youtube/discussions](https://github.com/coffetools-dev/super-youtube/discussions)

### Chrome Web Store
- Use the **"Support"** tab on the extension page

### Email
- **Support:** support@coffetools.dev

### Buy Me a Coffee
- [buymeacoffee.com/Nightkiller](https://www.buymeacoffee.com/Nightkiller)

---

## ✅ Privacy Summary

In summary, Super YouTube guarantees:

- ✅ **No personal data collection**
- ✅ **No activity tracking**
- ✅ **No analytics or telemetry**
- ✅ **Data stored locally only**
- ✅ **No third-party sharing**
- ✅ **No ads or data monetization**
- ✅ **Auditable code (open source)**
- ✅ **Total privacy guaranteed**
- ✅ **Compliance with GDPR, CCPA, and LGPD**
- ✅ **Full user control**

---

## 📝 Feature-by-Feature Details

### Features that DO NOT access external data:

**Video Player (8 features):**
- Loop Video - Local
- Loop Playlist - Local
- Volume Scroll - Local
- Default Quality - Local
- Default Speed - Local
- Fix Shortcuts - Local
- Audio Visualizer - Local (WebAudio API)
- Next/Prev Buttons - Local

**Tools (5 local features):**
- Screenshot - Local (canvas API)
- Picture-in-Picture - Local (PiP API)
- Disable Auto-Pause - Local
- Block End Screens - Local
- Expand Description - Local

**Interface (8 features):**
- Old Layout - Local (CSS)
- Hide Comments - Local (CSS)
- Hide Live Chat - Local (CSS)
- Hide Shorts Shelf - Local (CSS)
- Redirect Shorts - Local (URL redirect)
- Hide Shorts Button - Local (CSS)
- Auto-Scroll Shorts - Local (JS)
- Block Content - Local (user filters)

### Only feature with external access:

**Skip Sponsors (SponsorBlock):**
- ⚠️ Fetches data from public SponsorBlock API
- Data sent: YouTube video ID (public)
- Data received: Sponsor timestamps (public)
- Disabled by default
- User controlled
- Third-party API: https://sponsor.ajay.app

---

## 🏢 About CoffeTools

**CoffeTools** is an independent project developing tools and extensions that improve user productivity and experience.

**Mission:** Create useful, free tools that respect user privacy.

**Values:**
- 🔒 Privacy first
- 🆓 Free and open software
- 💎 Quality and usefulness
- 🌐 Open source and transparent
- 🤝 User respect

---

## ⚖️ Legal Provisions

### Limitation of Liability
Super YouTube is provided "as is", without warranties of any kind. CoffeTools is not responsible for:
- Changes in YouTube interface that may break features
- Incompatibilities with other extensions
- Misuse of the extension by third parties

### Service Modifications
CoffeTools reserves the right to:
- Add, modify, or remove features
- Update extension for YouTube policy compliance
- Discontinue extension (with prior notice)

### Agreement
By installing and using Super YouTube, you agree to this Privacy Policy.

If you do not agree, please do not install or uninstall the extension.

---

## 📅 Policy Version History

### v1.0 (November 13, 2025)
- Initial policy published
- Chrome Web Store compliance
- GDPR, CCPA, and LGPD compliance

**CoffeTools**  
Super YouTube - YouTube Enhancement Extension  
Version 1.0  

© 2025 CoffeTools. All rights reserved.  
License: MIT (Open Source)

---

*This privacy policy is effective as of November 13, 2025.*
