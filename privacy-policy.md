# Privacy Policy — Drop & Evolve

**Effective date:** 2026-09-06
**Last updated:** 2026-10-12

Drop & Evolve ("the app", "the game") is developed by **GC Apps** ("we", "us").

Contact for any privacy question or request: **gcapplicationdev@gmail.com**

This policy explains what the app collects, why, and what you can do about it.
It is written to be read, not to be survived.

---

## The short version

- The app has **no accounts of its own and no real-money purchases.** We never
  ask for your name, email address, phone number, contacts, photos or precise
  location.
- **Your progress is backed up to your own Google account, never to us.** If
  you use Google Play Games, your collection, coins and levels are saved there,
  so a new phone or a reinstall picks them up. Android's own backup may keep a
  copy of the save file in your Google account too. We never receive either.
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
section is collected. The app asks you once, after you first complete a level,
with two equal choices; if you decline, it does not ask again.

If you opt in, the app uses **Google Firebase Analytics** to record these eleven
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
| `day_active` | That the game was opened on a given day, at most once a day, how many days have passed since it was first opened on this device, and how many days in a row farm orders have been delivered |

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

### 3. Your game progress — on your phone and in your Google account

The following is written to a save file inside the app's private storage on your
phone:

- Which creatures you have discovered, and their variants
- Your level progress, star ratings and best scores
- Coins, purchased cosmetics and boosters
- Your settings: language, haptics, sound, music, and your analytics choice

**It is never sent to us.** Two Google services can keep a copy **in your own
Google account**, so your progress survives a new phone or a reinstall:

- **Google Play Games.** If you are signed in to Play Games — most Android
  phones sign you in automatically, and you can also sign in from the game's
  Settings — the game saves your discoveries, levels, best score, coins,
  cosmetics and boosters there (never your settings). To sign you in, Play Games
  shares your Play Games profile with the game: your player ID, gamer name and
  avatar. Google also collects its own diagnostics to keep the service working.
  If you do not sign in, nothing is saved to Play Games and the game works
  exactly the same.
- **Android backup.** If backup is turned on for your phone, Android copies the
  save file (and only the save file) to your Google account and restores it when
  you reinstall. This follows your phone's backup setting, not ours.

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
time without affecting the lawfulness of processing before withdrawal. Saving
your progress to Google Play Games is processed to provide the cloud save you
use by signing in (Art. 6(1)(b)); you can stop it by signing out of Play Games.

**Your rights.** You have the right to request access to, correction of,
erasure of, or restriction of processing of your personal data; to object to
processing; and to data portability. Because the app holds no account of its
own and we receive no identifier that points to you as a person, we will usually need the advertising
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

## Deleting your data

Drop & Evolve has no account of its own, so there is nothing to close. To have
your data deleted:

1. **Delete what is on your phone.** Uninstall the app, or open Android
   **Settings → Apps → Drop & Evolve → Storage → Clear storage**. This erases
   your progress, collection, coins and settings on the phone; we never had a
   copy.
2. **Delete the copies in your Google account.** Your Play Games save is
   deleted from **Google Play Games → Settings → Delete Play Games account &
   data**, where each game's data can be deleted on its own. Android backups
   are managed, and can be deleted, in your Google account's backup settings.
   Delete both before reinstalling, or the game will restore your progress.
3. **Stop anything new being collected.** In the app, open **Settings**, turn
   the analytics switch off, and use the privacy options row to withdraw ads
   consent.
4. **Delete your advertising ID.** On Android, open **Settings → Google → Ads**
   (on some phones **Settings → Privacy → Ads**) and choose **Delete
   advertising ID**. Advertising data Google already holds is then no longer
   linked to your phone.
5. **Ask us to erase analytics data.** Email **gcapplicationdev@gmail.com** with
   the subject "Delete my data — Drop & Evolve". If you never switched
   analytics on, there is none. We reply within one month.

**What is deleted, and what is kept.** Your save file is deleted in step 1,
and its copies in your Google account in step 2.
Analytics data is deleted on request where we can link it to your device, and
in every case automatically at the end of Firebase's retention window.
Advertising data is held by Google, not by us, and is kept under Google's own
retention policy (https://policies.google.com/technologies/retention). We keep
nothing else.

---

## Who else processes this data

| Processor | Purpose | Their policy |
|---|---|---|
| Google Firebase Analytics | Gameplay analytics, only if you opted in | https://firebase.google.com/support/privacy |
| Google AdMob | Serving rewarded video and banner ads | https://policies.google.com/technologies/ads |
| Google Play | App distribution | https://policies.google.com/privacy |
| Google Play Games services | Sign-in and saving your progress, only if you use Play Games | https://policies.google.com/privacy |
| Android backup (Google) | Backing up the save file, only if backup is on for your phone | https://policies.google.com/privacy |

Data processed by these services may be transferred outside the European
Economic Area. Google relies on the EU Standard Contractual Clauses and, for the
United States, the EU–US Data Privacy Framework for such transfers.

## How long it is kept

Analytics data is retained by Firebase according to the project's configured
retention window and is then deleted automatically. Advertising data is retained
by Google under its own advertising policies. Data stored on your device is kept
until you delete it in-app or uninstall the app. Copies of your progress in
your Google account are kept until you delete them (see *Deleting your data*).

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
