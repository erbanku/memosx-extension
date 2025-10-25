# Privacy Policy for MemosX

*Last updated: October 25, 2025*

## 1. Introduction

MemosX is a third-party Chrome extension designed to integrate with the open-source [Memos](https://github.com/usememos/memos) application (compatible with version 0.21 and earlier).
This extension allows users to quickly create and manage memos directly from their browser. MemosX is independently developed and not affiliated with or endorsed by the official Memos project.

## 2. Information Collection

MemosX does **not** collect, transmit, or share any personally identifiable information (PII), browsing data, or user analytics.

The extension only processes data necessary to perform its core functionality — connecting with a user’s self-hosted Memos instance.

Specifically:

-   **Server URL and API token** — stored locally using Chrome’s `storage` API.
-   **Memo content** (text, selected data, or links) — sent **only** to the user’s configured Memos server instance.
-   No other user data is collected, stored, or sent externally.

## 3. Permissions

MemosX uses the following Chrome extension permissions:

-   **`tabs` / `activeTab`** — to access the current tab’s URL or selected content when the user triggers the extension.
-   **`storage`** — to save user preferences (server address, token).
-   **`contextMenus`** — to display right-click menu options for quick memo creation.
-   **Host permissions (`https://\*/api/\*`)** — to send requests only to the user’s configured Memos server.

These permissions are used solely to enable core functionality. No external website data is read, modified, or tracked.

## 4. Data Sharing

MemosX does **not share data** with any third party, analytics service, advertiser, or developer-owned server.
 All data transmitted occurs exclusively between the user’s browser and their self-hosted Memos server.

## 5. Security

User information such as the Memos API token is stored securely within Chrome’s local extension storage and is never exposed externally.
 The extension performs no code injection, tracking, or cross-site communication.

## 6. Remote Code Policy

MemosX includes all scripts and assets within the packaged extension and does **not** load or execute any remote code, scripts, or modules from external servers.

## 7. User Control

Users can delete all locally stored information at any time by:

1.  Removing the extension from Chrome.
2.  Clearing extension data via Chrome settings.

## 8. Updates

This policy may be updated if new functionality is added or if Chrome Web Store requirements change. Updates will be reflected in this document and in the Chrome Web Store listing.

## 9. Contact

For questions, feedback, or concerns about this privacy policy or the extension, please contact:

**Developer:** *Erban Ku*
**Email:** cws@erbanku.com
**Project Page:** https://github.com/erbanku/memosx-extension