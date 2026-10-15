---
title: TerraJar privacy policy
permalink: /privacy/
---

# TerraJar privacy policy

**Last updated:** 15 October 2026

TerraJar ("the game", "the app") is a puzzle game for iPhone and Android, made by Francesco Mascia ("we", "us"). You can reach us at terrajar.support@gmail.com.

TerraJar is a general-audience game. It is not designed for or directed at children under 13, and we don't knowingly collect their personal data (see "Children" below).

You don't need an account to play, and we never ask for your name, email address, phone number, contacts, photos or precise location. This page lists the little the game and the services it uses do collect.

## 1. What is collected, and why

| What | Where it comes from | Why | Who handles it |
|---|---|---|---|
| **Your game progress** (levels, Dew, the terrarium, settings) | You, as you play | To run the game and keep your place | **Stays on your device.** We never receive it. Export codes you create and share are yours. |
| **Advertising identifier** (Google's advertising ID on Android, the IDFA on iPhone when you allow it), IP address, device model, OS version, app version, and whether an ad was shown or finished | The ad SDK, when it requests or shows an ad | To show ads, limit how often they appear, measure them and prevent fraud | Google AdMob ([Google privacy policy](https://policies.google.com/privacy)) and the ad networks it works with |
| **Your consent choices** about ads and measurement | A consent form shown on first launch where the law requires one (Google's User Messaging Platform), and the iPhone tracking prompt | To respect your choice | Stored on your device by the consent SDK |
| **Purchase records** (which products you bought, when, the store's transaction id) tied to an **anonymous app user id** that RevenueCat creates | The store and the purchase SDK | To deliver what you paid for, restore it on a new device, and keep records | RevenueCat ([RevenueCat privacy policy](https://www.revenuecat.com/privacy)), and Apple or Google, who process the payment. We never see your card details. |
| **App usage events and an app-instance id** (see the list below), device and app basics (model, OS, language, country, app version) | Firebase Analytics | To see which levels are too hard or too easy, whether the game works, and what to fix next | Google Firebase ([Firebase privacy information](https://firebase.google.com/support/privacy)) |
| **Remote configuration**: the game downloads a small settings file and sends the usual connection details (IP address, app and device basics) | Firebase Remote Config | To adjust game balance without a new release | Google Firebase |
| **An anonymous Firebase id and invite records**: your invite code, the code you redeemed (if any), whether that friend reached level 5 and whether the reward was claimed | Firebase Authentication (anonymous, no login), created when the game starts; Cloud Firestore when you create, share or redeem a code, and when the game checks for invite rewards at launch | To make invite-a-friend work and stop one code from being used twice | Google Firebase |
| **A device and app integrity token** | Firebase App Check (Play Integrity on Android, App Attest on iPhone), when the game starts | To keep modified copies of the game out of the invite service | Google (Play Integrity) or Apple (App Attest) |
| **The install referrer** (Android only): the text Google Play recorded when you opened an invite link, for example `c=ABC123` | Google Play Install Referrer | To redeem a friend's invite code automatically on first launch | Google Play. The game reads only the invite code in it. |

The analytics events the game sends are: session start, level start, level win, level fail, continue offered, continue taken (with how: ad, free, Dew or booster), ad shown and ad reward earned (with which placement), purchase (with the product id), plant grown, critter petted, and event reward claimed. Each carries a level or plant id or a number. None carries your name, contacts, location or free text. The game sets no user id and no user properties for analytics.

The game uses **local notifications** (reminders on your device if you allow them). They don't go through any server.

The game does **not** use your precise location, contacts, photos, microphone or camera, and does not sell personal data.

## 2. Ads, consent and your choices

The game shows ads from Google AdMob. Where the law requires it (the EEA, the UK and some other places) we ask for consent first, and ads and measurement follow your answer. You can change it any time in Settings, under Privacy options, where that button appears.

On iPhone the game asks permission to track you across other companies' apps and sites, once, after your first level win. If you say no, ads are not personalised with your IDFA. You can change this in iOS Settings, Privacy and Security, Tracking.

On Android you can reset or delete your advertising ID in Settings, Privacy, Ads. Buying **Remove Ads** removes the ads the game shows. Purchases and the services above keep working as described.

## 3. How long we keep it

- **Game progress:** on your device until you delete the app or its data.
- **Analytics:** Firebase keeps event data for 14 months (the retention we have set), then deletes it.
- **Purchase records:** as long as we need them for support, accounting and tax, and as long as RevenueCat and the stores keep them under their own policies.
- **Invite records and the anonymous id:** until you ask us to delete them (see section 6).
- **Ad data:** under Google's and the ad networks' own policies.

## 4. Who else receives data

We use these providers to run the game. Each handles data under its own terms and privacy policy:

- Google AdMob and Google Firebase (Analytics, Remote Config, Authentication, Cloud Firestore, App Check, Play Integrity): <https://policies.google.com/privacy> and <https://firebase.google.com/support/privacy>
- RevenueCat: <https://www.revenuecat.com/privacy>
- Apple App Store and Google Play (payments, installs): <https://www.apple.com/legal/privacy/> and <https://policies.google.com/privacy>
- The ad networks AdMob works with (Google's list shows which): <https://policies.google.com/technologies/partner-sites>

Google and RevenueCat process data in the United States and elsewhere. Where the law requires it, transfers rely on the EU-US Data Privacy Framework or standard contractual clauses.

We may disclose information if the law requires it. We do not sell your personal data for money. In some places (for example California), showing personalised ads can count as "sharing" or "selling" under privacy laws; you can opt out with the ad choices above.

## 5. Your rights

Under the EU and UK GDPR you can ask us to give you access to your data, correct it, delete it, restrict or stop its use, or send it to you in a portable form, and you can withdraw consent at any time (withdrawing doesn't affect what happened before). Our legal bases are: your consent for ads and measurement where the EEA and UK require it; the contract with you for purchases; and our legitimate interest for the anonymous invite service, game balance and keeping the app working. You can complain to your data protection authority, for example the Information Commissioner's Office in the UK (<https://ico.org.uk>). Residents of California and some other US states have similar rights to know, delete and opt out; write to us to use them.

## 6. How to ask us to delete your data

Because there is no account, we find your data by the identifiers below. Email terrajar.support@gmail.com with the subject "TerraJar data request" and:

- for **invite records:** the invite code shown on the Invite screen (and the code you redeemed, if any). We delete the records tied to it.
- for **purchase records:** the order id from your store receipt. We ask RevenueCat to delete the matching customer.
- for **analytics:** on Android, your advertising ID or app-instance id if you can give it; otherwise deleting the app and resetting your advertising ID ends the link.

We answer within one month. Your game progress is on your device only, so deleting the app deletes it.

## 7. Children

TerraJar is a general-audience game, not designed for or directed at children under 13. We don't knowingly collect personal data from them. If you are a parent and think a child has used the game, email us and we will delete what we hold.

## 8. Security

Data travels over encrypted connections. The invite service is protected by Firestore security rules and App Check. No method is perfectly secure.

## 9. Changes

If we change this policy in a way that matters, we will update the date above and, where the law requires, tell you in the game.

## 10. Contact

Francesco Mascia
terrajar.support@gmail.com
