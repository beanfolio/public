---
layout: default
title: Privacy Policy
---

<p align="right">
  <strong>English</strong> | <a href="../fr/privacy-policy">Français</a>
</p>

<img src="../assets/images/icon.jpeg" alt="Beanfolio Icon" class="header-logo">

# Privacy Policy — Beanfolio

*Last updated: May 3, 2025*

Beanfolio ("the app", "we", "us") is an iOS application for scanning, collecting, and discovering specialty coffee beans. This policy explains what data we collect, why we collect it, and how you can control or delete it.

---

## 1. What We Collect

### Account information
You can sign in with Apple or Google. When you sign in with Apple, we receive a unique user identifier and optionally your name and email address, depending on the sharing option you choose. When you sign in with Google, we receive your Google account name, email address, and profile photo URL. In both cases this information is stored in Firebase Authentication solely to identify your account.

### Profile photo
If you choose to upload a profile photo, the image is stored in Google Firebase Cloud Storage and linked to your account. It is not shared with any third party and is deleted when you delete your account.

### Coffee collection data
Every coffee bean you scan is saved to your personal collection in Firebase Firestore. This includes the roaster name, origin, roast level, tasting notes, sensory scores, your personal rating, and any notes you write. This data is private to your account.

### Coffee preferences
During onboarding you may provide brew methods, flavour preferences, roast preferences, and drink style. This information is stored in Firestore and used exclusively to personalise your Discovery recommendations.

### Coffee bag photos
When you scan a coffee bag, the photo you take is sent to the **Google Gemini API** for AI-powered text and data extraction. The image is transmitted over a secure connection and used only to extract coffee metadata. We do not store the raw scan photos on our servers — they are processed in real time and discarded.

### Discovery and wishlist data
Products you add to your wishlist and roasters you vote for are stored in Firestore under your account. Discovery results (weekly recommendations) are cached in Firestore to avoid redundant processing. URLs of products you have already seen are tracked for up to 45 days to avoid showing you the same suggestions repeatedly.

### Usage analytics
We collect anonymised usage events (such as how many beans you scan or whether you complete onboarding) using Firebase Analytics. These events do not include personally identifiable information and are used only to understand how the app is used so we can improve it.

### Crash reports
If the app crashes, a crash report is sent to Firebase Crashlytics. Crash reports may include the device model, iOS version, and a stack trace. They do not include your name, email, or coffee data.

---

## 2. How We Use Your Data

| Data | Purpose |
|---|---|
| Account identifier | Authenticate you and link your data to your account |
| Profile photo | Display your avatar in the app |
| Coffee collection | Show your personal bean library |
| Coffee preferences | Generate personalised Discovery recommendations |
| Coffee bag photos | Extract structured data from the bag via AI (not stored) |
| Wishlist & votes | Personalise and rank Discovery results |
| Analytics events | Understand app usage to guide improvements |
| Crash reports | Identify and fix stability issues |

We do not sell your data. We do not use your data for advertising. We do not share your data with any third party except the service providers listed below, which are necessary for the app to function.

---

## 3. Third-Party Services

| Service | Provider | Purpose | Privacy policy |
|---|---|---|---|
| Firebase Authentication | Google | Account sign-in | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Firebase Firestore | Google | Storing your collection and preferences | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Firebase Cloud Storage | Google | Storing your profile photo | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Firebase Analytics | Google | Anonymised usage analytics | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Firebase Crashlytics | Google | Crash reporting | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Gemini API | Google | AI extraction from coffee bag photos | [ai.google.dev/gemini-api/terms](https://ai.google.dev/gemini-api/terms) |
| Sign in with Apple | Apple | Account authentication | [apple.com/legal/privacy](https://www.apple.com/legal/privacy/) |
| Sign in with Google | Google | Account authentication | [policies.google.com/privacy](https://policies.google.com/privacy) |

All data transmitted between the app and these services is encrypted in transit using HTTPS/TLS.

---

## 4. Data Retention

Your data is retained for as long as your account exists. You can delete your account at any time from **Profile → Delete Account**. Deleting your account permanently removes:

- Your Firebase Authentication record
- Your entire bean collection
- Your wishlist and roaster votes
- Your coffee preferences and discovery cache
- Your profile photo from Cloud Storage

This action is irreversible.

---

## 5. Children's Privacy

Beanfolio is not directed at children under the age of 13. We do not knowingly collect personal information from children. If you believe a child has provided us with personal information, please contact us and we will delete it promptly.

---

## 6. Your Rights

Depending on where you live, you may have the right to access, correct, or delete the personal data we hold about you. Because all data is tied to your account, you can:

- **Access your data** — it is all visible within the app.
- **Correct your data** — edit bean details, preferences, and your profile at any time.
- **Delete your data** — use the in-app account deletion feature (Profile → Delete Account).

For any other request, contact us at the address below.

---

## 7. User Privacy Choices

We believe you should have control over your data. You can manage your privacy through the following choices:

### Authentication Choices
- **Sign in with Apple:** When creating your account, you can choose to "Share My Email" or "Hide My Email." If you choose to hide it, Apple will create a unique, random email address that forwards to your personal email, keeping your real address private from us.
- **Sign in with Google:** You can manage or revoke access for Beanfolio at any time through your Google Account security settings.

### Device Permissions
- **Camera Access:** We only request camera access to scan coffee bags. You can grant or revoke this permission at any time in your **iOS Settings → Beanfolio → Camera**. If revoked, you will still be able to use the app but will need to enter coffee data manually.
- **Notifications:** We may ask for permission to send you notifications about new weekly discoveries or milestones. You can manage these in **iOS Settings → Notifications → Beanfolio**.

### Data Management
- **Account Deletion:** You can permanently delete your account and all associated data at any time via **Profile → Delete Account** as detailed in Section 4.
- **Anonymized Analytics:** Our analytics are designed to be privacy-first and anonymized. We do not track you across other apps or websites.

---

## 8. Changes to This Policy

We may update this policy as the app evolves. When we do, we will update the "Last updated" date at the top. Continued use of the app after changes constitutes acceptance of the updated policy.

---

## 9. Contact

If you have any questions about this privacy policy or how your data is handled, please contact us at:

**barista@beanfolio.app**
