# Detour Post Privacy Policy

**Local review draft · updated 6 October 2026 · Not published or in effect · Legal and language review pending.**

---

## 1. Introduction

Detour Post is operated by Yong Wang, an individual. In this Policy, “we” means Yong Wang, who decides how personal information is handled for the service.

This Privacy Policy explains what information we collect, why we process it, how it is handled and stored, retention periods, and how you can exercise your privacy rights.

Our fundamental principle is straightforward: **Your letters are private between you and your recipient. We cannot read them, and we have no intention of reading them.**

## 2. Information We Process

### 2.1 Information You Actively Provide

| Information | Details | Necessity |
|---|---|---|
| Account and Login Identity | The account identifier, sign-in provider identifier, and verified email returned by Apple or Google | Required to create and authenticate your account |
| Login Credentials | Session authentication tokens; the service stores a hash of each token | Required for secure access |
| Birth month and year, and selected region | The App uses the birth month and year you enter during registration to check age eligibility on your device; eligibility rules also depend on your selected region | Required for registration. The App keeps your birth month and year in account-specific data on your device so you can view and edit them in your profile. They are not sent to or stored on our servers; the service retains the applicable policy version and sign-in region |
| Display Name | The name shown to people you correspond with | Required to complete registration; you can later change it in your profile |
| City | The city you select for sending letters, including the saved place details used by the app | Required to complete registration and send letters |
| Connection Info | Relationship status, invitation codes, and claim secrets | Required to exchange letters |
| Letter Contents | Letter text, stationery and decoration choices, attached photos, courier, and chosen or scheduled delivery time | Created only when you choose to send |
| Report Details | Reporter and reported-account IDs; target type, source and ID; selected reason; audit correlation ID; status and creation time. **Contains no letter text, photos, freeform text, or coordinates.** Filing a report also blocks the reported account and terminates letters that person sent to you which have not yet been delivered | Created only when you file a report |
| Private Notes | Notes you write for a contact | Optional. Stored on your device and included in your personal iCloud backup only if you enable that backup; not uploaded to our service |

**End-to-End Encryption of Letters and Photos.** Letter text and photos are encrypted directly on your device before they are sent to our service. For those letter contents, we hold ciphertext and no decryption keys. Other account and service records described in this Policy are separate. See Section 4.

### 2.2 Information Automatically Generated During Use

| Information | Details | Purpose |
|---|---|---|
| Delivery Status | Departure, journey milestones, arrival, recall, termination status | Sending and delivering letters |
| Account & Safety State | Account standing, reciprocal block lists, report handling status | Account administration and abuse prevention |
| Commerce Ledger | Orders and coin ledger/balances, stamp and timing-service inventory, permanent item ownership, subscriptions, and purchase-restoration state | Billing, fulfillment, restoration, and refund handling |
| Push & Device Tokens | Device push tokens and necessary metadata | Dispatching letter status notifications |
| Service Logs | API operational logs, error traces, and performance diagnostics | Security, stability, and troubleshooting |

### 2.3 What We NEVER Do

- We do NOT access your full photo library, contacts, or precise GPS location;

- The App does not use advertising identifiers for ad targeting or cross-app tracking and does not include an advertising SDK;

- We do NOT feed letter data into AI training models—we have no access to plaintext;

- We NEVER sell your personal information to third parties.

## 3. Why We Process Information

| Purpose | Information Involved |
|---|---|
| Postal delivery and receipt | Account ID, display name, city, connection info, encrypted letter, delivery status |
| In-App Purchases and refunds | Purchase ledger, subscription validity |
| Delivery push notifications | Push token, delivery state |
| Safety, abuse prevention, and reports | Safety state, report details, operational logs |
| Diagnostics and service stability | Operational logs |
| Handling user rights and inquiries | Information provided by you |

The legal basis for each processing purpose depends on the law that applies to you and the facts of that processing. This draft does not yet assign a basis to each purpose; that review must be completed before publication. We will not rely on a basis that does not apply under the relevant law.

## 4. End-to-End Encryption

This is the most critical technical safeguard of Detour Post:

**Encryption Occurs Locally on Your Device.** When you tap "Seal this letter", all text and photos are encrypted on your device prior to transmission. Decryption keys are held exclusively by you and your designated recipient.

**We Hold Only Ciphertext for Letter Text and Photos.** Our service stores letter text and photos in encrypted form and does not hold their decryption keys. We do not provide manual key recovery. We also process the account and service records described in this Policy.

**No Exceptions.** We maintain no administrative backdoors, content inspection channels, or customer service overrides. Because we cannot view plaintext, we cannot perform automated keyword filtering or content recommendation.

**Implications:**

- Only you can see the content prior to delivery;

- Only you and your recipient can see the content after delivery;

- If you lose your device and lack a personal iCloud backup, we cannot recover your letters—we do not have the keys;

- A safety report records its selected reason and associated account or letter identifiers, triggers a two-way block, and terminates letters sent by the reported person to you that have not yet been delivered. The report does not expose letter content. If Yong Wang becomes aware of a report, he will make reasonable efforts to review it and take appropriate action where warranted. No specific review or response time is promised; any further account action depends on review.

**Personal Backup.** If you enable it, selected vault data—including private contact notes, drafts, pending invitation material, and saved letter data—is encrypted on your device and backed up to your personal iCloud through CloudKit. The backup is encrypted with a key kept in your device's Keychain. After a backup is verified, a recovery key is stored in iCloud Keychain so it can be available on your other Apple devices. We do not receive either key and cannot decrypt the backup.

## 5. System Permissions

The App may request notification permission after you first send or receive a letter, and you can also request it in Settings. It requests add-only Photos permission if you choose to save a generated traveler card to your photo library.

| Permission | When Requested | Purpose |
|---|---|---|
| Notifications | After your first sent or received letter, or when you choose to enable alerts in Settings | The visible alert uses generic wording. The payload also contains a notification category and an opaque event identifier used to open the relevant app screen; it excludes letter text and location |
| Photos (add-only) | When you choose to save a generated traveler card | Saves that image to your photo library; it does not grant access to browse your library |

The App syncs your in-app notification preferences to the service, which uses them when deciding whether to send the corresponding alerts. Turning off iOS notification permission controls whether alerts can appear on that device. Neither action by itself deletes or deactivates the device-token record on our service. Refusing an optional system permission does not by itself prevent basic sending or receiving.

**Other permission behavior:**

- **Photos:** When you attach a photo to a letter, the system photo picker gives the App access only to the image you select; the App does not browse your full library. Saving a generated traveler card to Photos uses the separate add-only Photos access and its system permission prompt.

- **Location:** You choose the city for each letter. We do not collect device location or track movement. The app includes a built-in set of country and city names and coordinates for some local search suggestions, limited offline fallback results, and map labels. City search checks this catalog first and uses a catalog match without sending that search term to MapKit. If there is no catalog match, the app requests place-search results from Apple MapKit. When the built-in catalog has no center for a selected country or region, the app may send that country or region name to Apple through Core Location geocoding to set the map view. Reverse-geocoding a map point also uses Core Location; if Apple's result is unavailable, the app may use a nearby catalog city as a limited fallback. These Apple services receive the search text, country or region name, or map-point coordinates involved in the request. These features do not require location permission.

- **Contacts, Camera, Microphone, App Tracking (ATT):** Not requested and no corresponding code exists.

## 6. Third Parties

We do not sell personal information. Information is processed by the service providers needed to provide the features you use. For letter text and photos handled through our service’s server-side storage and processing, these providers receive ciphertext, and we do not provide them with decryption keys:

| Third Party | Data Processed | Purpose | Notes |
|---|---|---|---|
| Apple | Sign-in identifier and verified email, in-app purchases and subscriptions, push token and notification delivery, encrypted personal-vault backups and recovery keys if enabled, search terms sent with MapKit place-search requests, country or region names sent for map positioning when the built-in catalog has no center, and map-point coordinates sent with Core Location reverse-geocoding requests | Authentication, billing, notifications, backup, and map/search features | Subject to [Apple Privacy Policy](https://www.apple.com/legal/privacy/) |
| Google | Sign-in provider identifier and verified email, when supplied | Optional authentication | Subject to [Google Privacy Policy](https://policies.google.com/privacy) |
| Apple Push Notification service (APNs) | Push token, generic alert text, notification category, and opaque event identifier | Notification dispatch | The alert text is generic; the payload contains no letter text, photos, or precise location |
| Cloudflare | Encrypted letter data, account/login records, selected city data, purchase and delivery records, push tokens, and service logs | Cloud compute, database, and object storage | Subject to [Cloudflare Privacy Policy](https://www.cloudflare.com/privacypolicy/) |

The iOS App does not include third-party SDKs for tracking, advertising, or usage analytics.

## 7. Data Storage and International Transfers

- **On Your Device:** Local letters, drafts, private contact notes, and preferences.

- **In Your Personal iCloud:** If enabled, an encrypted backup of selected vault data, including private contact notes, drafts, pending invitation material, and saved letter data.

- **On Our Servers:** Account and login identifiers, verified email, display names, selected city snapshots, relationship and delivery records, encrypted letter payloads, purchase records, push tokens, and service logs. Our cloud infrastructure is operated outside some users’ countries or regions, so this information may be processed internationally.

## 8. Data Retention Periods

| Information | Retention Period |
|---|---|
| Birth month and year | Kept in account-specific app data on your device; you can view and edit them in your profile. They are not sent to or stored on our servers |
| Account and login identity | Account deletion disables the account, revokes its sessions, and removes profile and notification data. The deleted-account record and sign-in provider identity remain in the current service design; a fixed deletion deadline for those records has not been defined. |
| Letter Ciphertext | A complete recipient-device save acknowledgement starts server-side ciphertext cleanup. If no complete save occurs, the letter becomes unavailable 90 days after it becomes available to the recipient (for a scheduled letter, from its scheduled delivery time) and enters the server-side ciphertext cleanup process. A deleted sender account is not restored when this period expires. |
| Purchase and fulfillment records | Retained to administer purchases, refunds, and delivery obligations. The applicable retention period has not yet been specified in the current product rules. |
| Push Tokens | In-app notification preferences control which alerts are sent. Turning off iOS notification permission controls display on that device. Account deletion removes its device-token record; tokens reported invalid by APNs are deactivated |
| Safety Reports | Selected reason, associated account or letter identifiers, status, and creation time. A fixed retention period and deletion trigger have not been defined |
| Service Logs | May be created for security, reliability, and troubleshooting. They may include technical request or error details. A fixed retention period is not specified in the current product rules. |

## 9. Your Privacy Rights

Depending on where you live, applicable law may give you rights to access, correct, delete, or obtain a copy of personal information, object to or restrict some processing, or withdraw consent. Nothing in this Policy limits rights that apply to you under law. Contact us at detourpost@aivolo.studio to make a request; we may ask for information needed to verify your identity.

| Right | How to Exercise |
|---|---|
| Access or copy | Open "Me" to view account details, purchases, and assets; contact us about a request that is not available in the App |
| Correction | Open "Me" → "Profile" to edit your display name and city; contact us about other information |
| Deletion | Use the in-app "Delete Account" feature, or contact us for specific data requests |
| Withdraw consent | Contact us at detourpost@aivolo.studio if you want to withdraw consent for processing that relies on your consent; applicable law determines the effect on prior processing |
| Account Deletion | Open "Me" → "Delete Account" → "Delete account" |
| Questions and requests | Contact detourpost@aivolo.studio |

**What Happens on Account Deletion:** The account is disabled, its sessions are revoked, and profile and notification data are removed. Letters that have not yet departed are terminated; departed letters continue under their existing delivery plan. Deleting your App account does not cancel an Apple-billed membership; manage or cancel it in your Apple account subscription settings. The current service design retains a deleted-account record and sign-in provider identity; see the retention table above.

To submit a privacy request, email detourpost@aivolo.studio. Response timing depends on the nature of the request and applicable law; no general response time is promised here.

## 10. Minors

The App is intended for users who meet the minimum age that applies to them, which is at least 13 and may be higher in some jurisdictions. If you believe someone may have registered below the applicable minimum age, contact detourpost@aivolo.studio. If Yong Wang becomes aware of the concern, he will make reasonable efforts to review it and take steps required by applicable law. No fixed review or response time is promised.

## 11. Security Measures

- End-to-end encryption for letter text and photos;

- Encrypted transport channels (TLS/HTTPS);

- Credentials and keys stored in secure system storage (iOS Keychain);

- The App uses device-protected storage for local credentials and encryption keys.

No security measure can guarantee absolute security. If a data security incident occurs, we will provide notices and take steps as required by applicable law.

## 12. Policy Updates

We may update this Privacy Policy. The current text and update date will appear on this page. We will not use personal information for a purpose incompatible with those described here. Where applicable law requires notice of a material change or a new use of information, we will provide that notice using an appropriate method.

## 13. Contact Us & Complaints

- **Operator:** Yong Wang, an individual

- **Email:** detourpost@aivolo.studio

For questions or complaints, you may email Yong Wang at detourpost@aivolo.studio. Response times are not guaranteed. You may also lodge a complaint with a supervisory authority that has jurisdiction over your matter.

A final retention schedule for deleted-account records and provider identities, purchase and fulfillment records, safety reports, and service logs has not been established. This draft is not ready for publication until the retention rules and the legal basis for each processing purpose are reviewed and finalized.
