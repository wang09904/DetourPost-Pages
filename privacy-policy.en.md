# Detour Post Privacy Policy

**Version 1.0 ｜ Effective Date: 2026-09-18 ｜ Last Updated: 2026-09-18 ｜ Online Web: https://wang09904.github.io/DetourPost-Pages/privacy.html**

---

## 1. Introduction

Detour Post (hereinafter referred to as "the App") is operated by Yong Wang (hereinafter referred to as "we", "us", or "our"). We act as the data controller for your personal information.

This Privacy Policy explains what information we collect, why we process it, how it is handled and stored, retention periods, and how you can exercise your privacy rights.

Our fundamental principle is straightforward: **Your letters are private between you and your recipient. We cannot read them, and we have no intention of reading them.**

## 2. Information We Process

### 2.1 Information You Actively Provide

| Information | Details | Necessity |
|---|---|---|
| Account Identifier | Unique identifier obtained via Sign in with Apple or Google | Required for account creation |
| Login Credentials | Session authentication tokens | Required for secure access |
| Date of Birth & Region | Used at registration solely to determine age eligibility | Required for registration. **Date of birth is used only at the moment of evaluation and immediately discarded; we never store it.** Only the rule version and selected region are retained |
| Display Name | Custom name set in your profile, visible to your recipients | Optional |
| City | City selected as departure/arrival point | Optional, but required to send letters |
| Connection Info | Relationship status, invitation codes, and claim secrets | Required to exchange letters |
| Letter Contents | Letter text, stationery choice, attached photos, courier, arrival time | Created only when you choose to send |
| Report Details | Selected violation category (Harassment, Spam, Safety) and target ID. **Contains NO letter text, photos, freeform text, or coordinates**; automatically blocks the party simultaneously | Created only when you file a report |
| Private Notes | Private notes you assign to a contact | Optional. **Stored strictly on your local device, never uploaded** |

**End-to-End Encryption of Letters and Photos.** Letter text and photos are encrypted directly on your local device before transmission. We hold only ciphertext and possess no decryption keys. Consequently, **we cannot read, inspect, or provide your letter text or photos to anyone**—including law enforcement inquiries, where only ciphertext can be provided. See Section 4.

### 2.2 Information Automatically Generated During Use

| Information | Details | Purpose |
|---|---|---|
| Delivery Status | Departure, journey milestones, arrival, recall, termination status | Powering the postal delivery pipeline |
| Account & Safety State | Account standing, reciprocal block lists, report handling status | Account administration and abuse prevention |
| Commerce Ledger | Order records, Coin balances, permanent item ownership, active subscriptions | Billing, fulfillment, and refund handling |
| Push & Device Tokens | Device push tokens and necessary metadata | Dispatching letter status notifications |
| Service Logs | API operational logs, error traces, and performance diagnostics | Security, stability, and troubleshooting |

**No Secrets in Logs or Push Notifications.** Operational logs never contain letter text, photos, invitation codes, or exact coordinates. Push notifications carry only generic status phrases (e.g., "A letter has arrived") without personal identifiers, message text, or cities.

### 2.3 What We NEVER Do

- We do NOT access your full photo library, contacts, or precise GPS location;
- We do NOT collect tracking identifiers (IDFA/IDFV), embed ad SDKs, or engage in cross-app tracking;
- We do NOT feed letter data into AI training models—we have no access to plaintext;
- We NEVER sell your personal information to third parties.

## 3. Why We Process Information

| Purpose | Information Involved | Legal Basis |
|---|---|---|
| Postal delivery and receipt | Account ID, display name, city, connection info, encrypted letter, delivery status | Performance of service contract |
| In-App Purchases and refunds | Purchase ledger, subscription validity | Performance of service contract |
| Delivery push notifications | Push token, delivery state | Your consent (revocable anytime) |
| Safety, abuse prevention, and reports | Safety state, report details, operational logs | Legitimate interest & legal obligation |
| Diagnostics and service stability | Operational logs | Legitimate interest |
| Handling user rights and inquiries | Information provided by you | Legal obligation |

## 4. End-to-End Encryption

This is the most critical technical safeguard of Detour Post:

**Encryption Occurs Locally on Your Device.** When you tap "Seal this letter", all text and photos are encrypted on your device prior to transmission. Decryption keys are held exclusively by you and your designated recipient.

**We Hold Only Ciphertext.** Our servers store only encrypted blobs. We do not retain decryption keys in any form, nor do we provide manual key recovery.

**No Exceptions.** We maintain no administrative backdoors, content inspection channels, or customer service overrides. Because we cannot view plaintext, we cannot perform automated keyword filtering or content recommendation.

**Implications:**
- Only you can see the content prior to delivery;
- Only you and your recipient can see the content after delivery;
- If you lose your device and lack a personal iCloud backup, we cannot recover your letters—we do not have the keys;
- Safety reports trigger relationship blocks and account penalties, without human operators reading letter content.

**Personal Backup.** Letter data backups occur exclusively through your personal iCloud if enabled. Backups reside entirely within your Apple ID ecosystem. We have no access to your iCloud backup or Keychain keys.

## 5. System Permissions

The App requests only one system permission:

| Permission | When Requested | Purpose |
|---|---|---|
| Notifications | When you opt in to letter alerts | Alerts you when letters depart or arrive. Payloads contain only generic phrases |

Disabling notifications does not affect sending or receiving letters.

**Permissions We Do NOT Request:**
- **Photos:** Photo selection uses the native system photo picker. Only the single selected image is passed to the App; full photo library access is neither requested nor required.
- **Location:** Cities are selected manually from a list. We never track your device coordinates.
- **Contacts, Camera, Microphone, App Tracking (ATT):** Not requested and no corresponding code exists.

## 6. Third Parties

We never sell personal data. Information is shared strictly with necessary infrastructure providers:

| Third Party | Data Processed | Purpose | Notes |
|---|---|---|---|
| Apple | Account ID, StoreKit purchases, push dispatch, MapKit geocoding | Authentication, in-app billing, notifications, map display | Subject to [Apple Privacy Policy](https://www.apple.com/legal/privacy/) |
| Google | Account ID | Optional authentication | Subject to [Google Privacy Policy](https://policies.google.com/privacy) |
| Apple Push Notification service (APNs) | Push token, generic alert payload | Notification dispatch | Payloads contain no letter text or recipient identities |
| Cloud Infrastructure Providers | Encrypted letter blobs, account ledger | Cloud compute and secure storage | Processed strictly under our instruction |

The iOS App contains zero third-party tracking, advertising, or analytics SDKs.

## 7. Data Storage and International Transfers

- **On Your Device:** Local letters, drafts, and preferences.
- **In Your Personal iCloud:** Encrypted database backups within your private Apple account.
- **On Our Servers:** Account IDs, display names, encrypted letter payloads, and transaction ledgers stored in secure overseas cloud infrastructure. Data may be transferred and processed internationally under strict contractual safeguards.

## 8. Data Retention Periods

| Information | Retention Period |
|---|---|
| Date of Birth | Not stored. Evaluated once at registration and immediately discarded |
| Account ID, Display Name, City, Connections | Duration of account lifecycle; deleted or irreversibly anonymized upon account deletion |
| Letter Ciphertext | Deleted immediately upon delivery confirmation by recipient; unclaimed letters cleaned up after 90 days |
| Purchase Ledger | Retained as required by financial, tax, and consumer protection laws |
| Push Tokens | Removed from servers immediately upon notification opt-out or account deletion |
| Service Logs | Retained for a short diagnostic window and automatically deleted. Contains no private secrets |

## 9. Your Privacy Rights

You may exercise the following rights regarding your personal information:

| Right | How to Exercise |
|---|---|
| Access & Portability | View profile, purchases, and assets in "My Profile"; request export via detourpost@aivolo.studio |
| Rectification | Edit display name and city in Profile Settings; contact us for other records |
| Deletion | Use the in-app "Delete Account" feature, or contact us for specific data requests |
| Withdraw Consent | Toggle off notifications in App Settings or iOS System Settings |
| Account Deletion | Navigate to "My Profile" → "Account Deletion & Isolation" → "Delete Account" |
| Questions & Inquiries | Contact detourpost@aivolo.studio |

**What Happens on Account Deletion:** Undeparted letters are terminated; departed letters continue to their destination; profile records, block relations, and device tokens are immediately and permanently erased.

We respond to all privacy requests within **48 hours**.

## 10. Minors

The App is intended for users aged 13 and older (or higher depending on local jurisdiction requirements). We do not knowingly collect personal data from minors below the applicable registration age. If you believe a minor has registered without authorization, contact detourpost@aivolo.studio and we will promptly delete the account.

## 11. Security Measures

- End-to-end encryption for letter text and photos;
- Encrypted transport channels (TLS/HTTPS);
- Credentials and keys stored in secure system storage (iOS Keychain);
- Principle of least privilege for server infrastructure;
- Continuous vulnerability scanning and configuration audits.

## 12. Policy Updates

We may update this Privacy Policy periodically. Significant changes will be notified prominently within the App. If you disagree with modified terms, you may delete your account.

## 13. Contact Us & Complaints

- **Operator:** Yong Wang
- **Email:** detourpost@aivolo.studio

We respond to inquiries within **48 hours**. You also have the right to lodge a complaint with your local data protection supervisory authority.

---

© 2026 Yong Wang. All rights reserved.
