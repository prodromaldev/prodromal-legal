# Prodromal — Privacy Policy

**Last updated:** April 19, 2026
**Effective:** April 19, 2026

## Summary (the short version)

- Your health data never leaves your iPhone except in end-to-end encrypted form
- We don't sell your data. We don't run ads. We don't share with brokers
- You can delete everything any time from Settings → Delete Account
- Questions: privacy@prodromal.ai

## Who we are

Prodromal ("Prodromal", "we", "us", "our") is operated by **Jonathan Huang**, a sole proprietor registered in **Singapore**. Prodromal is a consumer iOS app that coaches users through the prodromal phase of illness.

## What we collect

### Health data (via Apple HealthKit)

With your explicit permission, Prodromal reads the following from Apple Health:

- Heart rate variability (HRV, SDNN)
- Resting heart rate
- Respiratory rate
- Body temperature
- Blood oxygen saturation (SpO₂)
- Heart rate

**How it's used:** to compute your personal baseline and detect early-warning drift 24–36 hours before symptoms.

**Where it lives:** all HealthKit readings are processed **on your device**. Raw HealthKit data is never transmitted to our servers.

### Symptom and episode data (entered by you)

When you log symptoms, take a check-in, or resolve an illness, the following is stored locally on your device via Apple's SwiftData framework:

- Symptom type and severity
- Free-text notes
- Trigger contexts (stress, travel, etc. if selected)
- Protocol action completions
- Peak severity on resolution

**Where it lives:** on your device only, in an iOS-managed local database. It is backed up via your iCloud backup if you have that enabled (controlled entirely by you).

### AI chat messages

When you use the chat feature to ask Prodromal questions, your message is sent to **Anthropic (claude.ai)** via their API for processing. Prodromal does not retain copies of your chat messages server-side.

Anthropic's data processing terms apply to those messages. As of the current date, Anthropic does not train on API inputs. See [anthropic.com/privacy](https://www.anthropic.com/privacy).

### Account data

We do not require an account for core functionality. If you subscribe to Prodromal Pro or Family:

- Your subscription is managed entirely by Apple (App Store). We do not receive your credit card, email, or Apple ID.
- We receive only a subscription receipt confirming your entitlement tier.

### Analytics (anonymous, aggregated)

We use analytics software to understand how people use Prodromal. We track events like:

- First open
- Onboarding completion
- Episode start / resolve
- Paywall view / conversion
- Chat message sent (count only, not content)

**What we do not track:**
- Your health data values (HRV, temperature, etc.)
- Your symptom content
- Your chat message content
- Your name, email, phone number, or Apple ID

Analytics events are tied to an anonymous device-scoped identifier. You can opt out in Settings → Privacy → Analytics.

### Crash reports

We use **Firebase Crashlytics** to capture crash reports. Crash reports include:

- iOS version
- Prodromal version
- Anonymized device model
- Stack trace at time of crash

No personal data or health data is included.

## What we don't do

- We don't sell your data to anyone, ever
- We don't share your data with advertisers
- We don't share your data with data brokers
- We don't use your data to train AI models
- We don't request tracking permission under App Tracking Transparency — we don't track you across apps

## Apple Family Sharing (Family plans)

If you subscribe to Prodromal Family, up to 5 Apple Family members can access Pro features. Each member's health data remains **entirely private to them** — no one on your family plan can see anyone else's data, including you. The Family plan only shares the *subscription entitlement*.

## Your rights

You can:
- **Export all your data:** Settings → Export My Data → generates a JSON file
- **Delete all your data:** Settings → Delete Account → wipes everything from your device and revokes analytics ID
- **Revoke HealthKit access:** iOS Settings → Privacy & Security → Health → Prodromal → toggle off
- **Cancel subscription:** iOS Settings → Apple ID → Subscriptions → Prodromal

### GDPR / Singapore PDPA / California privacy rights

If you're in the EU, UK, Singapore, or California, you have additional rights:
- Right to access: we'll send you a copy of all data we hold about you within 30 days
- Right to erasure: we'll delete everything within 30 days
- Right to data portability: your export includes all personal data in JSON
- Right to object: contact privacy@prodromal.ai

## Children

Prodromal is not intended for users under 13. If we discover an under-13 account, we delete it.

## Changes to this policy

We'll email subscribers and show an in-app notice at least 30 days before any material change.

## Contact

- **Privacy:** privacy@prodromal.ai
- **Support:** support@prodromal.ai
- **Legal entity:** Jonathan Huang, Singapore
