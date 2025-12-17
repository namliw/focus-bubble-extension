# Privacy Policy

**Deep Focus Bubble**  
*Last updated: December 18, 2025*

## Overview

Focus Bubble is a browser extension that helps you stay focused by blocking distracting websites. We are committed to protecting your privacy. This policy explains what data the extension collects and how it's handled.

**The short version:** All your data stays on your computer. We don't collect, transmit, or share any of your information.

## Data Collection

The extension stores the following data locally on your device:

### Blocked Websites List
- Domain names you choose to block
- The blocking mode selected (Deep Focus, Work Hours, or Brief Pause)
- When each site was blocked

### Work Hours Settings
- Your configured work hours start time
- Your configured work hours end time

### Unblock History
- Domain names you've unblocked
- The reason you provided when unblocking
- When the site was unblocked
- How long the site was blocked

## Data Storage

All data is stored **locally on your device** using Chrome's built-in storage API (`chrome.storage.local`). Your data:

- Never leaves your computer
- Is not transmitted to any servers
- Is not accessible to us or any third parties
- Is synced across your Chrome browsers only if you have Chrome Sync enabled (this is a Chrome feature, not ours)

## Data Sharing

We do not share your data with anyone. Period.

- No analytics or tracking
- No third-party services
- No data collection servers
- No advertising

## Permissions Explained

The extension requests certain permissions to function. Here's why each is needed:

| Permission | Why It's Needed |
|------------|-----------------|
| `storage` | Save your blocked sites list, settings, and history locally |
| `tabs` | Detect when you visit a blocked site and redirect you to the blocked page |
| `alarms` | Automatically unblock sites after 1 hour and check work hours |
| `activeTab` | Show which website you're viewing in the popup so you can block it |
| `declarativeNetRequest` | Manage website blocking rules |
| `<all_urls>` | Monitor navigation to any website you choose to block |

## Data Retention

- **Blocked sites and settings:** Stored until you remove them
- **Unblock history:** Limited to the most recent 100 entries (older entries are automatically removed)
- **All data:** Deleted when you uninstall the extension

## Your Control

You have full control over your data:

- **View all data:** Open the extension settings to see your blocked sites and unblock history
- **Delete blocked sites:** Remove any site from your blocked list at any time
- **Clear history:** Unblock history can be cleared through the settings
- **Uninstall:** Removing the extension deletes all stored data

## Changes to This Policy

If we make changes to this privacy policy, we will update the "Last updated" date at the top. For significant changes, we will update the extension's changelog.

## Contact

If you have questions about this privacy policy or the extension's data practices, please open an issue on our GitHub repository:

[GitHub Issues](https://github.com/namliw/focus-plugin/issues)

*(Update this link with your actual GitHub repository URL)*

---

## Summary

| Question | Answer |
|----------|--------|
| Do you collect my data? | No |
| Is my data sent anywhere? | No, it stays on your device |
| Do you use analytics? | No |
| Do you share data with third parties? | No |
| Can I delete my data? | Yes, through settings or by uninstalling |

