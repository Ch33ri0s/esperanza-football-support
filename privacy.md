---
permalink: /privacy/
---

# Privacy Policy — Esperanza Football

**Effective date:** 2026-04-20
**Last updated:** 2026-08-28

This policy explains what data the Esperanza Football mobile app ("the app") collects, why, and what your choices are. The app is a community tool for the Esperanza High School football program in Anaheim, California. It is maintained by a volunteer from the program, not by the school district itself.

## The short version

- **No accounts for regular users.** Families and fans can browse roster, schedule, news, and sponsors without signing up. Nothing is collected about you.
- **No location, contacts, microphone, or camera access.**
- **No advertising networks. No third-party analytics. No crash reporting.**
- **Push notifications are opt-in.** If you turn them on, our push provider (OneSignal) gets a device token so the app knows where to deliver messages. You can turn them off in the app Settings at any time.
- **Only program staff have logins.** The admin sign-in exists so a small number of volunteers can update content. Staff use their email address with a one-tap "magic link" — no passwords.

## What data we collect

### If you use the app without signing in (everyone except staff)

- **Push notification identifiers**, only if you opt in to notifications. When you tap "Turn on" in the app and allow notifications, our push provider (OneSignal) receives a device token plus your platform (iOS/Android). OneSignal uses these to deliver messages addressed to this device. No message content is stored by the app itself.
- **OS-level diagnostic data.** Apple and Google automatically collect crash reports and usage data at the platform level; neither the app nor its developer receives this. You control it in your device settings.

We do **not** collect your name, email address, phone number, location, contacts, photos, or any other personal information.

### If you are a program staff administrator

Administrators sign in with a "magic link" sent to their email. For admins only:

- **Email address.** Stored by our backend provider (Supabase) in its authentication system. Used to send the magic-link email and to identify the admin's session.
- **Session token.** A short-lived credential stored on the device to keep you signed in. Cleared when you sign out.

Administrator accounts exist because a volunteer needs to be able to update the roster, post news, and edit sponsors. Families and fans never need to sign in.

### Content the app displays

The app displays publicly available information about the football program: team roster, game schedule, sponsors, and announcements. Player roster entries include name, grade, position, jersey number, and optionally a photo — the same information that would appear in a game-day program or a school-athletics website. All roster content is entered by program staff. The app does not scrape this information; it does not collect it from users; and it does not share it with any third party beyond what is necessary to display it to you.

## Third-party services we use

| Service | Purpose | Data shared |
|---|---|---|
| **Supabase** (supabase.com) | Backend database + administrator authentication | Administrator email addresses; all public roster/schedule/news/sponsor content |
| **OneSignal** (onesignal.com) | Push notification delivery | Device push token, platform, subscription state — only for devices that opted in to notifications |
| **Apple Push Notification service** | Delivers notifications on iOS | Relay only — Apple does not retain message content for this app |
| **Google Firebase Cloud Messaging** | Delivers notifications on Android | Relay only — Google does not retain message content for this app |

Each of the above providers has its own privacy policy; links on request.

**Fonts.** The app's typefaces (Plus Jakarta Sans and Inter, both open-source) are bundled inside the app. It does not download fonts from Google — or contact any font server — at runtime, so no font request ever leaves your device.

## How long data is kept

- **Roster, schedule, news, sponsor content:** until program staff remove it.
- **Administrator accounts:** until the administrator requests removal, or until they are no longer involved with the program.
- **Push tokens (OneSignal):** until you opt out of notifications in the app, uninstall the app, or revoke notification permission in your device settings. OneSignal keeps the record of a previously opted-out device so we can re-enable delivery if you opt back in; you can request full deletion via the contact email below.

## Your choices

- **Turn off push notifications.** Open the app, go to Settings, toggle "Push notifications" off. You can also revoke permission in your device settings; the app will stop receiving notifications.
- **Remove your administrator account.** If you are a staff administrator, follow the instructions on the [data deletion page](./data-deletion/). We will delete your authentication account and administrator authorization after verifying the request.
- **Request deletion of a push token.** Follow the instructions on the [data deletion page](./data-deletion/) with your platform, device model, and approximate notification opt-in date so the OneSignal subscription can be located.

Because no accounts are created for regular users, there is nothing to delete for families or fans who simply use the app to follow the team.

## Children's privacy

The app is intended for a general audience including minors — it is a high school football program app, and players, students, and younger siblings are expected to use it. The app does **not** collect personal information from any user who does not create an administrator account. Administrator accounts are restricted to adult program volunteers. If you believe a minor has somehow created an administrator account, please contact us and we will delete it.

The app complies with the Children's Online Privacy Protection Act (COPPA) by not collecting personal information from children.

## Data location

Supabase stores data in the United States (US East region). OneSignal processes push delivery data in the United States. This app is intended for a Southern California high school community; data is not intentionally transferred outside the United States.

## Security

Administrator authentication uses one-time magic-link emails; there are no passwords to leak. Connections between the app and our providers use TLS. Roster and content data are protected by row-level security policies in the database, so only authenticated administrators can modify them. No security system is perfect; if you believe you have discovered a vulnerability, please report it via the contact email below.

## Changes to this policy

We will update this page in place if practices change. The "Last updated" date at the top of this document reflects the most recent revision. Material changes will be announced via an in-app notification.

## Contact

Questions, account deletion requests, or security reports:

**Email:** tenysonpartridge@gmail.com
**Subject line:** Please begin with "Esperanza Football app:"

**Data deletion instructions:** [https://ch33ri0s.github.io/esperanza-football-support/data-deletion/](./data-deletion/)

The app is operated by a single volunteer. Responses may take a few days. For urgent issues involving the school or the football program itself, contact Esperanza High School's athletic department directly.
