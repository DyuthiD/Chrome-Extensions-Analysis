# Chrome Extensions Analysis

This repository contains an analysis of Chrome browser extensions installed on the system, identifying their purpose and security status.

## 📋 Task Summary
The objective of this task was to:
1. Examine all installed Chrome extensions.
2. Identify their purpose and any associated security warnings.
3. Document extensions flagged as potentially harmful.

## 🖇️ Installed Extensions Overview

| Extension Name                          | Description                                                      | Security Status                                  |
|------------------------------------------|--------------------------------------------------------------------|--------------------------------------------------|
| **Flash Player for Web**                 | Allows playback of Flash content in the browser.                  | ⚠️ *Not trusted by Enhanced Safe Browsing.*      |
| **Forest: stay focused, be present**     | Helps users stay focused by blocking distractions.                | ✅ *Safe.*                                        |
| **Google Docs Offline**                  | Enables offline editing and viewing of Google Docs.               | ✅ *Safe.*                                        |
| **Kaspersky Protection**                 | Provides security features for safe browsing.                     | ✅ *Safe.*                                        |
| **Momentum**                             | Replaces new tab page with a personal dashboard for productivity. | ✅ *Safe.*                                        |
| **Nucleus: A Pomodoro Timer and Blocker**| Timer and website blocker for productivity.                       | ❌ *Flagged: This extension contains malware.*   |

## 🚨 Security Observations
- **Flash Player for Web**: Marked as "Not trusted" by Chrome Enhanced Safe Browsing. May pose a security risk.
- **Nucleus: A Pomodoro Timer and Website Blocker**: Explicitly flagged as containing malware. Immediate removal is recommended and done.

## ✅ Steps done
- **Removed** any extensions flagged as unsafe or containing malware.
- Audited extensions to ensure browser security.
- Using only trusted extensions from the official Chrome Web Store.

---

### 📌 Tools Used
- Google Chrome (Extensions Management)
- Manual Security Review
