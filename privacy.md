---
title: Nerola Privacy Policy
---

# Nerola Privacy Policy

[Türkçe sürüm](./gizlilik)

Effective date: 24 September 2026
Data controller: Tolga Sayan (individual developer; App Store seller name)
Contact: tolgasayan@icloud.com

Nerola is an English vocabulary game played by typing answers. This policy explains what data the Nerola iOS app processes and how. Solo play does not require an account, a name or an email address. Optional friend games (Word Table and friend races) ask for a display name; a nickname is sufficient.

## 1. Data that stays on your device
Except for the competition features described below, the following is stored only on your device: app language, level, onboarding status; round history, scores, learning list, review words and badges; dictionary bookmarks, pronunciation dialect (US/UK) and slow-playback preference; the record of your daily new-round allowance; your daily streak record (the days you practised and the days your streak froze) and unfinished game rounds. Deleting the app deletes this data from your device. If device backup is enabled it may be included in Apple's backup, which is governed by Apple's terms.

### Reminder notifications
Nerola can send optional local reminder notifications. Only you switch them on (the "Want a reminder?" screen in the app or "Practice reminders" in the home menu); iOS asks for notification permission separately. Reminders are scheduled entirely on your device: one notification 24 hours after your last visit and, if you do not return, one more on days 2, 3 and 7, then they stop; opening the app restarts the timer. Once you have a daily streak, the same schedule counts from your last completed practice and the notifications remind you about your streak. There is no push notification, server, device token or usage data transfer; the texts are fixed sentences in the app language. You can turn them off from the menu at any time.

## 2. Written answers
You type your answers into letter spaces using the keyboard. Nerola evaluates the written words on your device. The app does not request microphone or speech recognition permission, activate the microphone or send audio for recognition. Solo written answers stay in your local round history. Word Table and friend-race answers are also sent to the race service described below; answers are not sent to an analytics service. Keyboard features provided by iOS or a keyboard you install are governed by that provider's settings and privacy policy.

### Optional friend games
**Word Table (version 2.0 and later):** When you create or join a table for 2–4 players, Nerola sends your chosen display name and avatar (a symbol and a colour), a table-specific random credential, level, content versions, your ready and connection status and your submitted answers to our Cloudflare-hosted race service. The service stores only a hash of the credential, grades answers and keeps the scores. Everyone at the table sees your name, avatar, ready and connection status, score and your result on each question (such as correct, wrong, passed or time up); when a question closes, the correct word is shown to everyone. The text of your typed answer is shown only to you and is not sent to other players. The person who created the table can remove a disconnected player in the waiting room.

**Friend races (the two-player room in earlier versions):** When you create or join a two-player room, Nerola sends your chosen display name, room-specific random credential, level, content version, submitted answers and race events to our Cloudflare-hosted race service. The service stores a hash of the credential, grades answers and measures elapsed time. Your room partner sees your name and readiness; both players can see scores and answer details after both finish or the race expires. No contact list, telephone number or microphone data is accessed. Sharing uses the iOS share sheet; your chosen messaging app handles the invitation under its own policy.

Table records are deleted within 24 hours of creation. A table that stays idle for 20 minutes in the waiting room or on the results screen, or whose players have all been disconnected for more than 2 minutes, closes and is deleted sooner. Room records are also deleted within 24 hours of creation; unused lobbies expire after 15 minutes. Your own learning history remains on your device. The service processes request IP addresses to limit abuse; IP addresses are not stored in the table or room record. Cloudflare also processes network requests to deliver and protect the service. See [Cloudflare's privacy policy](https://www.cloudflare.com/privacypolicy/). To request deletion of a table or room before it expires, contact us with its code.

### Optional Game Center competitions
The app does not ask you to sign in to Game Center when it first opens. The first time you open the daily wheel it asks once whether you want to join the rankings; if you do not connect, the wheel still opens and your result stays on your device. If you connected before, the app reconnects to Game Center at launch. If you use Game Center, Apple receives the submitted daily competition score and associates it with your Game Center player identity. Leaderboard visibility follows your Game Center settings. Nerola does not send individual written answers to Game Center.

## 3. Pronunciation audio
In version 1.0, pronunciation uses your device's speech synthesizer. From version 1.1, selected English word and story recordings are created in advance with ElevenLabs and included in the app. Listening plays these files on your device; your text, answers and identity are not sent to ElevenLabs. Other accents, missing recordings and newly generated story wording use the device's speech synthesizer. No network connection is needed for this audio playback.

## 4. Purchases and Nerola Plus
If you buy Nerola Plus, payment is handled by the Apple App Store; we never see your card details. We use two providers to manage purchases: RevenueCat (stores your purchase record and Plus access status) and Superwall (shows the Nerola Plus offer screen). These providers receive a random identifier generated when the app is installed (it contains no name or email). The identifier persists for that installation; reinstalling creates a new one. Your purchase history is linked to it.
SDK processing does not begin only after a purchase. In the current implementation, RevenueCat starts at app launch and checks access status when its public key is configured. Superwall starts when sales and its keys are enabled; it may also process data about free users who see an offer.
To operate, the providers' SDKs also process:
- RevenueCat: the App Store purchase receipt and Plus access status, app version, device platform and OS version. RevenueCat uses these for receipt validation and for aggregate statistics in its dashboard; no advertising identifier (IDFA) is collected.
- Superwall: device attributes used to decide where to show the offer screen and to keep offer-screen statistics (Apple's vendor-scoped device identifier, device model, OS version, language and region, time zone, app version and install date, network type, low-power mode, light/dark appearance), interactions with the offer screen (view, dismiss, purchase attempt) and Plus access status. Superwall may derive an approximate country/region/city from the request IP address; this is not precise location and the app never asks for location permission.
The current app integration does not use this data for advertising or cross-app tracking as defined by Apple. Provider information: [RevenueCat privacy policy](https://www.revenuecat.com/privacy) and [data processing addendum](https://www.revenuecat.com/dpa); [Superwall privacy policy](https://superwall.com/legal/privacy-policy) and [data processing addendum](https://superwall.com/legal/dpa). The providers retain this data for the periods set out in their own policies; if you want your purchase record deleted, write to the address in section 7 and we will forward the request to the providers.
In the free version the dictionary, pronunciation audio, learning list, badges, the daily wheel and Word Table are available to everyone; Plus removes the daily limit on new rounds and unlocks the chapters after the first three in A2, B1, B2 and C1, 60 narrated stories and unlimited rounds in the three mini games. The A1 chapter path and 40 stories remain free.

## 5. Advertising, tracking and analytics
Nerola shows no ads, shares no data with ad networks and does not track you across apps or websites (in the sense of Apple's "tracking" definition).

**Version 1.0:** The app has no usage-analytics or crash-reporting service of its own; your in-game behaviour, answers and voice are never sent to an analytics service. The only exception is the purchase providers in section 4: purchase and offer-screen data are also declared under the "Analytics" purpose in the App Store privacy label.

**Version 1.3 — unlinked usage counts:** A previous decision to switch sharing off is preserved. The existing consent flow remains for App Store storefronts in the EU/EEA, United Kingdom and Switzerland, and when the storefront is unknown. In other storefronts, usage counts without a persistent analytics identity are on by default for people who have not made a choice. A home-screen notice explains this and the home menu can turn it off. The storefront is used only on-device for this decision and is not sent; interface language is not used as a location. Each event has a different random identifier. Installation, session and run identifiers, installation dates, device model, operating system, time zone and screen dimensions are excluded. These counts do not link a person's activity across days. They may include event type, app version, interface language, level, content, aggregate results and active time. Explicitly consented analytics continues to use the installation-specific identifier described below. New events record onboarding steps, explicitly leaving the first wheel (which can be resumed), and closing a Plus offer. Backgrounding is not treated as abandonment. Network requests still technically expose an IP address to the provider; discarding IP data is a separate safeguard from the absence of persistent identifiers.

**Version 2.0:** The start and end of Word Table matches are also counted, with the number of players at the table (2–4) and how the match ended (completed, abandoned, or you left). Player names, avatars, table codes and typed answers are not sent. Your daily streak record stays on your device and is not sent to analytics.

**Consented analytics (1.1/1.2 and people who explicitly consent in 1.3):** To improve the app, Nerola can collect product analytics with PostHog (PostHog Inc., project hosted in the European Union). This starts only if you choose **Share usage data** on the in-app "Help us improve Nerola" screen; until you decide, and if you choose **Don't share**, nothing is sent. You can change your decision at any time from the home-screen menu; switching it off stops sending, and usage from the period it was off is never uploaded later.

What is sent: session start, welcome and level choice, the start and completion of a wheel, chapter, story, daily wheel, mini game, friend race or Word Table match (content identifier, replay flag, active time and aggregate correct/wrong/pass counts; for Word Table also the number of players and how the match ended), the Plus offer being shown and the purchase outcome (started, pending, cancelled, failure category, verified success, restore), an invite link being opened; plus technical context such as app version, OS version, device model, interface language, time zone and screen size. This data is tied to a **random, install-specific analytics identifier**; it does not identify you directly, but because it is persistent it is not fully anonymous data. Switching sharing off and on again creates a new identifier.

What is never sent: your typed answers, dictionary searches, room and table codes, invite links, your name, your avatar, e-mail, Game Center identity, advertising or device identifiers, audio or screenshots. Location derived from the IP address is disabled; session recording, automatic screen/tap capture and surveys are not used. Provider information: [PostHog privacy policy](https://posthog.com/privacy) and [data processing addendum](https://posthog.com/dpa). Usage events are retained for up to one year on our current free PostHog plan. Switching sharing off deletes the unsent device queue; it does not automatically erase events already sent to the server. For analytics data requests, contact us using section 7.

Before you decide, up to 50 usage events may wait in memory for that running app session only. They are sent if you agree and discarded if you decline or the app closes.

## 6. Children
Nerola is intended for a general audience and is not designed for children under 13. The app does not ask for an email address or location. Optional friend games ask for a display name; a nickname is sufficient. If you believe the random identifier described in section 4 belongs to a child, write to the address in section 7 and we will have the record deleted.

## 7. Your rights
Because the app does not associate data with an account, you can delete on-device data yourself by deleting the app. For requests about your purchase record (access, deletion), contact tolgasayan@icloud.com with your random identifier. Because the app does not currently display this identifier, include your purchase date and the details from your App Store receipt. We will try to match the record with this information; a match is not possible in every case, and we will tell you the outcome. This policy is written under Türkiye's Personal Data Protection Law (KVKK, Law No. 6698); if you are in the European Economic Area or the United Kingdom, you can exercise your GDPR/UK GDPR rights of access, rectification, erasure and objection through the same address.

## 8. Changes
When this policy changes, the effective date is updated; material changes are announced in the app.

## 9. This website
These pages are hosted on GitHub Pages. GitHub may log visitor IP addresses for security purposes; that processing is independent of the app and governed by [GitHub's privacy statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement). This site uses no cookies or analytics.
