---
layout: prose
title: Privacy Policy
permalink: /legal/privacy/
lang: en
canonical_en: /legal/privacy/
canonical_es: /es/legal/privacy/
redirect_from:
  - /PRIVACY_POLICY
  - /PRIVACY_POLICY/
  - /privacy
  - /privacy/
updated: 2026-07-11
---

# Privacy Policy — Faro

**Effective date**: 2026-06-12
**App**: Faro
**Data controller**: KHASSINX LLC, a Florida limited liability company (United States)
**Contact**: legal@khassinx.com

---

## TL;DR

Faro is a private, end-to-end encrypted space where a trusted adult and a child stay close across a distance. **We do not collect your data.** Your messages, drawings, memories, and calls are sealed end to end and live only on your devices and in your own iCloud — controlled by your Apple ID, not by us. We have no server holding your family's content, no advertising, no analytics, and no trackers. There is nothing for us to sell, because there is nothing collected.

You can report or block a contact from inside the app, and you can access, export, or delete your data at any time.

---

## What we collect

**Nothing.** Faro's App Store privacy label is **Data Not Collected** — the strongest label Apple offers, and an honest one.

| Category | Collected by us? |
|---|---|
| Messages, drawings, time capsules, memories | ❌ No — end-to-end encrypted, stored on your devices + your iCloud |
| Your child's activity or behavior | ❌ No — Faro never profiles a child |
| Contacts / Photos / Microphone / Camera | ❌ No (used only on-device with your permission, never sent to us) |
| Location | ❌ No |
| Advertising identifiers (IDFA) | ❌ No |
| Usage analytics | ❌ No analytics SDKs of any kind |
| Crash logs | ❌ No |
| Email address | Only if **you** write to us — see "If you contact us" below |

The app's `PrivacyInfo.xcprivacy` manifest declares the same thing. Apple verifies this during App Store review.

## Where your data lives

Faro is built so that your family's content never reaches a server we control.

| What | Where |
|---|---|
| Messages, drawings, time capsules, memories, your activity history | On your device + **your personal iCloud** (encrypted by Apple, your Apple ID) |
| Encryption keys | In your device's Secure Enclave and iCloud Keychain — never exported to us |
| Bond / pairing material | Exchanged end-to-end encrypted between the two devices; we never see the keys |

iCloud sync uses **your** Apple ID. We never see, access, or have any way to retrieve it. Apple encrypts it in transit and at rest, and end to end where you have enabled Advanced Data Protection. If you delete the app and remove its iCloud data, your copy is gone — and there is no other copy on any server, because **we do not run a server that stores your content.**

## End-to-end encryption

Everything you and your child share in Faro is **end-to-end encrypted**. Content is sealed on the sending device and can only be opened on the device of the verified bond on the other side.

- The other parent or household **cannot** read a bond that isn't theirs — not as a policy, but by design: the keys simply do not exist anywhere they can reach.
- **We cannot** read your content either. We hold no keys and no copies.
- Calls use **Apple FaceTime**, which is end-to-end encrypted by Apple. Faro never records the audio or video of a call.

## How bonds are created (and kept safe)

A grown-up sets up every bond. To connect an adult's device with a child's device across two different Apple accounts, Faro uses an invitation plus an out-of-band verification step: both screens show a short sequence of symbols, and the adult and child confirm they match — usually on a call together. This defeats impersonation and confirms the two people are who they say they are. No third party is involved, and the verification happens directly between the adult and the child.

## On-device intelligence (Apple Intelligence)

Where your device supports it, Faro uses **Apple Intelligence (Foundation Models)** to help a child express themselves, to gently redirect sensitive topics back to the adult, and to write soft weekly summaries for the adult.

This model runs **entirely on your device**. Your conversations never leave your iPhone, iPad, or Mac for AI processing. We do not send your data to OpenAI, Anthropic, Google, or any third-party AI service, and we run no AI server of our own. On devices without Apple Intelligence, these features are quietly hidden and the rest of Faro works normally.

## Parental consent (children's privacy)

Faro is always set up by an adult, on the child's behalf. The adult who installs the child's app and consents must attest that they are the child's **parent, legal guardian, or a legally authorized adult**. Faro captures that attestation during setup.

Because an adult sets up and consents to every bond, we treat **every** child as requiring parental consent. This satisfies the strictest reading of children's privacy law — including **COPPA** (United States) and **GDPR-K** (European Union) — with a single, consistent flow.

We never knowingly collect personal data directly from a child for our own purposes. A child's content stays within the encrypted bond, on their devices and the adult's.

## Subscriptions and purchases

If you choose a paid unlock or an optional subscription, it is processed entirely by **Apple StoreKit**. We receive only a signal from Apple that an Apple ID has an active entitlement — never your name, payment method, or billing address. Apple handles all of that. Manage or cancel anytime in Settings → Apple ID → Subscriptions. All of Faro's safety and emergency features are free and never behind a paywall.

## Notifications

Push notifications are opt-in. If you allow them, your device receives an Apple Push Notification token used only to deliver the signals you turn on (a new message, an incoming call). We do not send marketing notifications. Faro has no mailing list.

## This website

This site is static. It sets no cookies of its own, runs no analytics or tracking of any kind, embeds no third-party scripts or pixels, and has no forms. We do not track anyone, so there is nothing for a "Do Not Track" signal to turn off, and no third party is permitted to collect information about your activity across sites through this website. The site is served by GitHub Pages with DNS and delivery by Cloudflare; like any web host, those providers process standard technical request data (such as your IP address) to deliver and protect the site, as independent companies under their own privacy policies. We do not receive, keep, or use that data.

## If you contact us

If you write to any `@khassinx.com` address, we receive your message and reply address through our email provider, and we keep that correspondence to handle your request. We do not add you to any list. That is the only situation in which we hold any personal data about you, and only because you chose to write to us.

## Your rights

You are always in control of your data:

- **Access** — your content is visible in the app at all times.
- **Export** — export your data from in-app Settings.
- **Delete** — delete your account and content from in-app Settings. Because we hold no copy on a server, deletion is complete once removed from your device and your iCloud.
- **Report or block** — report or block a contact from inside the app at any time.
- **Object / withdraw consent** — stop using Faro and delete its data at any time.

For region-specific rights — the EU/EEA (GDPR), the UK, Spain (LOPDGDD), California (CCPA/CPRA), other US states, and the rest of the world — see KhassinX's [Privacy Rights](https://khassinx.com/legal/your-rights/). To exercise any of them for Faro, use the in-app controls above or email [`legal@khassinx.com`](mailto:legal@khassinx.com).

## Apple App Privacy Nutrition Labels

In the App Store listing, Faro declares **Data Not Collected** across every category. This is verified against the in-app `PrivacyInfo.xcprivacy` manifest and the actual code: no analytics SDKs, no third-party trackers, no advertising frameworks, no backend collecting your content.

## Security

- All content is **end-to-end encrypted** with Apple's CryptoKit; keys live in the Secure Enclave and iCloud Keychain.
- Faro stores **no** family content on any server we control.
- iCloud sync uses Apple's encryption, end to end where you have enabled Advanced Data Protection.
- To report a vulnerability, see our [Security & Responsible Disclosure](/security/) policy.

## International use

Because Faro does not collect your data or store your content on our servers, there is no cross-border transfer of your content by us. Your content stays on your devices and in your own iCloud, where Apple handles residency and encryption.

## Changes to this policy

We may update this policy when adding features that materially change data handling, reflecting changes in Apple's policies, or correcting errors. Material changes will be reflected with a new "Effective date" at the top, and a notice will appear in-app at next launch.

## Jurisdiction

This policy is governed by the laws of the **State of Florida, United States** — the jurisdiction in which KHASSINX LLC is formed.

## Contact

- **Email**: legal@khassinx.com
- **Mail**: Available on written request via email

We aim to respond within seven business days.

---

*Last updated: 2026-06-12 · Version 1.0*
