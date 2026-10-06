# Privacy Policy — Drop & Evolve

**Effective date:** 2026-09-06
**Last updated:** 2026-10-06

Drop & Evolve ("the app", "the game") is developed by **GC Apps** ("we", "us").

Contact for any privacy question or request: **gcapplicationdev@gmail.com**

This policy explains what the app collects, why, and what you can do about it.
It is written to be read, not to be survived.

---

## The short version

- The app has **no accounts, no sign-in, and no real-money purchases.** We never ask for
  your name, email address, phone number, contacts, photos or precise location.
- **Your game progress never leaves your phone.** Your collection, coins,
  levels and settings are stored on the device and are deleted when you
  uninstall the app.
- **Analytics is off until you switch it on.** Nothing is sent to us unless you
  explicitly opt in, and you can opt back out at any time in Settings.
- **No ad ever interrupts play.** Video ads are rewarded videos you tap to
  start; the only other ad is a small banner in a strip at the bottom of the
  screen.

---

## What the app collects

### 1. Gameplay analytics — only if you opt in

Analytics collection is **disabled by default**. It is enabled only if you
explicitly agree, and you can disable it again at any time from the in-app
Settings screen. If you decline, or if you never answer, nothing in this
section is collected.

If you opt in, the app uses **Google Firebase Analytics** to record these ten
events, and nothing else:

| Event | What it records |
|---|---|
| `level_start` | Which level was started |
| `level_complete` | Which level was completed, the star rating, and how many of its drops were used |
| `level_fail` | Which level was failed, the star rating, how many of its drops were used, and whether it ended on the drop limit, a full jar or the clock |
| `creature_discovered` | Which creature tier and variant was discovered |
| `endless_game_over` | The run's score and your best score |
| `rewarded_shown` | That a rewarded ad was displayed, and which reward |
| `rewarded_completed` | That a rewarded ad was watched to the end |
| `rewarded_failed` | That a rewarded ad could not be shown |
| `rescue_used` | That a lost level or Endless run was rescued, and whether with in-game coins or a rewarded ad |
| `shop_purchase` | Which item was bought in the in-game shop, and its price in in-game coins (never real money) |

These payloads contain only numbers and short internal labels. They contain no
personal information and nothing you have typed.

Alongside these, Firebase Analytics automatically collects a standard technical
set: a randomly generated **app instance identifier** (a pseudonymous ID for the
installation, not for you), your device model, operating system version, app
version, device language, and an **approximate region derived from your IP
address** — country level, not a location.

We use this to understand which levels are too hard, which are too easy, and
whether players reach the end of the creature chain. It is never used to
identify you and is never sold.

### 2. Advertising — Google AdMob

The app shows two kinds of ad. **Rewarded videos**, which you always start
yourself by tapping an offer, and a **banner** in a fixed strip at the bottom
of the screen. No ad ever interrupts a run: there are no pop-up or full-screen
ads you did not choose.

To serve these, **Google AdMob** processes your device's **advertising ID**,
your **IP address**, and your interactions with the ad. Whether you see
**personalised** or **non-personalised** ads depends on the choice you make in
the consent form the app shows you.

Non-personalised ads still require the advertising ID for frequency capping and
fraud prevention, but are not selected based on a profile of your interests.

You can reset or delete your advertising ID at any time in your device's
**Settings → Privacy → Ads**.

### 3. Stored on your device only — never sent to us

The following is written to a save file inside the app's private storage on your
phone. It is **not transmitted anywhere**, not backed up to us, and is removed
when you uninstall the app:

- Which creatures you have discovered, and their variants
- Your level progress, star ratings and best scores
- Coins, purchased cosmetics and boosters
- Your settings: language, haptics, sound, music, and your analytics choice

### 4. What we never collect

No name, email address, phone number, postal address, contacts, calendar,
photos, camera, microphone, files, precise or GPS location, health data,
payment information, or anything you type. The app has no chat, no user-generated
content, no social features and no in-app purchases.

---

## Permissions the app requests

| Permission | Why |
|---|---|
| `INTERNET`, `ACCESS_NETWORK_STATE` | To load ads and, if you opted in, send analytics |
| `VIBRATE` | Haptic feedback on merges and button presses |
| `AD_ID` | Required by Google AdMob to serve ads |
| `ACCESS_ADSERVICES_TOPICS`, `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION` | Added by the Google Mobile Ads SDK for Android's Privacy Sandbox |
| `READ_BASIC_PHONE_STATE`, `WAKE_LOCK`, `FOREGROUND_SERVICE`, `BIND_GET_INSTALL_REFERRER_SERVICE` | Added automatically by Google Play services and the ads SDK. The last is Play's install-referrer service, used for install attribution. |

The last two rows are declared by Google's own libraries rather than by us. We
list them because they appear in the app's manifest and you are entitled to know
why they are there.

---

## Legal basis, and your rights under GDPR

GC Apps is established in Belgium, so the EU General Data Protection
Regulation applies to this app everywhere it is distributed.

**Legal basis.** Analytics and personalised advertising are processed on the
basis of your **consent** (GDPR Art. 6(1)(a)), which you give through the
in-app consent form and the Settings screen, and which you may withdraw at any
time without affecting the lawfulness of processing before withdrawal.

**Your rights.** You have the right to request access to, correction of,
erasure of, or restriction of processing of your personal data; to object to
processing; and to data portability. Because the app holds no account and no
identifier that points to you as a person, we will usually need the advertising
ID or app instance ID from your device to act on such a request. Write to
**gcapplicationdev@gmail.com** and we will respond within one month.

**Withdrawing consent.** Open **Settings** in the app. The analytics switch
turns collection off immediately. The privacy options row reopens the ads
consent form.

**Complaints.** You may lodge a complaint with the Belgian Data Protection
Authority — *Gegevensbeschermingsautoriteit / Autorité de protection des
données*, Rue de la Presse 35, 1000 Brussels — or with the supervisory
authority of the EU country where you live.

---

## Who else processes this data

| Processor | Purpose | Their policy |
|---|---|---|
| Google Firebase Analytics | Gameplay analytics, only if you opted in | https://firebase.google.com/support/privacy |
| Google AdMob | Serving rewarded video ads | https://policies.google.com/technologies/ads |
| Google Play | App distribution | https://policies.google.com/privacy |

Data processed by these services may be transferred outside the European
Economic Area. Google relies on the EU Standard Contractual Clauses and, for the
United States, the EU–US Data Privacy Framework for such transfers.

## How long it is kept

Analytics data is retained by Firebase according to the project's configured
retention window and is then deleted automatically. Advertising data is retained
by Google under its own advertising policies. Data stored on your device is kept
until you delete it in-app or uninstall the app.

---

## Children

Drop & Evolve is intended for players aged **13 and over**. It is not directed
to children, it is not enrolled in Google Play's Families programme, and we do
not knowingly collect data from children under 13. If you believe a child has
provided us with data, contact **gcapplicationdev@gmail.com** and we will delete
it.

## Changes to this policy

If this policy changes materially we will update the "Last updated" date above
and, where the change affects what is collected, ask for your consent again
inside the app. The current version always lives at this URL.

## Contact

**gcapplicationdev@gmail.com**
