---
title: Privacy policy
---

# Privacy Policy

**Nasim** ("the app") is a daily Islamic spiritual practice app operated by Imperium Advisors, LLC ("we"). This policy explains what we collect, why, and what we will never do. It is written to be read, not skimmed.

_Last updated: 2026-09-11. Effective for app version 1.0._

## The short version

- We are a subscription product. You are the customer, not the product.
- We do not sell, rent, or trade your data. Ever.
- We do not use advertising SDKs, tracking pixels, or third-party analytics.
- Your location never leaves your device.
- You can export or permanently delete everything we hold, from inside the app, at any time.

## What we store

| Data | Why | Where |
|---|---|---|
| Email address and a password hash, or your Google account identifier | To sign you in | Supabase (our database provider) |
| Display name | To greet you | Supabase |
| Profile photo (optional) | Shown to you on your Today and Profile screens | Supabase Storage, and on your device. The photo is resized to 512 px before upload. Its link is unlisted but, like most profile-photo hosting, not password-protected. Deleting your account deletes it. |
| Daily reminder time and whether reminders are on | To schedule your local reminder | Supabase, and on your device |
| Prayer-time calculation method | So times are computed the way your community does | Supabase |
| Time zone | To compute your streak correctly | Supabase |
| Emotional check-ins (the feeling you select) | To recommend a session and show you your own history | Supabase |
| Sessions you have completed and when | Streak and progress | Supabase |
| Journal entries: reflections and duas you write | They are yours to re-read | Supabase |
| Product events: which onboarding steps you finished, sessions started and completed, whether the paywall was shown | To see where people get stuck and fix it. Never free text, never shared. | Supabase, our own database |

Journal entries are stored as you wrote them. They are protected by row-level security so only your signed-in account can read them, and encrypted in transit. Staff do not read journal entries.

## What we never collect

- **Location.** If you allow it, your location is used on your device to compute prayer times and the Qibla direction. It is not transmitted to us or to anyone else. We store only which calculation method you chose.
- **Your photo library.** If you add a profile photo, you choose it through the system picker, which hands the app only that one image. The app never receives access to your library.
- **Contacts, microphone, camera.** The app does not request them.
- **Advertising identifiers or cross-app tracking.** None.
- **Third-party analytics.** The app contains no analytics or advertising SDK. The product events above go only to our own database.

## Who else touches your data

- **Supabase** hosts our database, authentication, and profile photos. Data is stored in Canada (ca-central-1).
- **Sanity** hosts the content you read (sessions, series). It does not receive any information about you.
- **Google**, only if you choose "Continue with Google". Google's own privacy policy applies to that sign-in.
- **Apple**, for App Store purchases if you subscribe. We never see your payment details.
- **Sentry**, only if crash reporting is enabled in a release: when the app crashes, a technical error report (stack trace, device model, OS version, app version) is sent so we can fix it. It contains no account details, no location, and no journal text.

There are no other recipients.

## Your rights

- **Export.** Profile → Export my data produces a complete JSON copy of everything above.
- **Delete.** Profile → Delete account permanently removes your account and all associated data, including your profile photo. This is immediate and irreversible. It is not tied to your subscription status.
- **Correct.** Edit your name, photo, and reminder from Profile → Edit.
- If you are in the EU, UK, or a jurisdiction with similar rights, the export and delete tools above satisfy access and erasure requests. For anything else, use the support page below.

## Children

The app is not directed at children under 13 and we do not knowingly collect data from them.

## Changes

If this policy changes materially we will show a notice in the app before the change takes effect.

## Contact

Questions about this policy go through the support page: https://atmerlo.github.io/nasim-legal/support
