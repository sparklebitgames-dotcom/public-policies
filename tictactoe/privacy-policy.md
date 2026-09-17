# Privacy Policy — Tic Tac Toe

_Last updated: 17 September 2026_

This policy covers the **Tic Tac Toe** app (package `com.sparklebit.tictactoe`, "the App"),
published by **Sparkle Bit Games** ("we", "us").

**Who is responsible for your data (data controller / data fiduciary)**
Sparkle Bit Games · contact: **sparkle.bit.games@gmail.com**
For users in India, this address is also our **grievance contact** under the Digital
Personal Data Protection Act, 2023 (see [Contact and complaints](#7-contact-and-complaints)).

**In short:** the App has no accounts, shows no ads, and has no server of ours. Your games and
stats stay on your phone. The App does send a small amount of technical data to Google so we
can find and fix crashes and tell you when an update is required. It does not send usage
analytics.

---

## 1. What we collect, why, and on what legal basis

### 1.1 Gameplay data — stays on your device
Your in-progress board, your win/loss/draw record and streaks, and your settings — theme
(light/dark/system), board skin, sound on/off, and your last-used game options. The App also
stores a small amount of internal bookkeeping: how many wins have been counted toward the
"rate this app" prompt, and how far you got through the first-run walkthrough.

Stored locally via Android DataStore. **We never receive it** — it is not sent to us, and we
operate no server it could be sent to.

One thing to be clear about: if **Android Backup** is switched on for your device (Android
**Settings → Google → Backup**), Android itself copies this into **your own Google account
backup**. That copy belongs to your Google account rather than to us, and we cannot read it.
It does mean that **uninstalling the App does not necessarily erase your record**:
reinstalling later, on the same phone or a new one, can restore it. When you set up a new
phone, Android's device-to-device transfer carries it across too.

If you want that copy gone as well, turn off Android Backup for the App, or delete the App's
backup under **Settings → Google → Backup**.

### 1.2 No advertising
The App **shows no ads** and contains no advertising code. It does not use your device's
advertising ID for anything.

For completeness: the installed App still lists the Android permission that *allows* access to
the advertising ID (`AD_ID`), and two related Android "AdServices" permissions. They are not
there for advertising — they come bundled inside a Google library the App includes (see §1.4),
and that library's data collection is switched off. No part of the App reads the advertising ID.

### 1.3 Crash diagnostics — Firebase Crashlytics
If the App crashes we receive a diagnostic report: the stack trace, the App version, your
device model and operating-system version, basic device state at the time of the crash, and a
**Firebase installation identifier** (a random ID for this installation of the App, not
linked to your name, email or Google account). It contains none of your game data.

Crashlytics also uses a companion Google library (Firebase Sessions) which may send a small
**session record** when the App starts — a random session ID, the installation identifier and
basic app and device details — so that a crash can be linked to the session it happened in.

- **Purpose:** to find and fix defects that break the App.
- **Legal basis (GDPR):** our **legitimate interest** in a functioning, secure app
  (Art. 6(1)(f)).

### 1.4 Analytics — switched off
The App includes Google's Firebase Analytics library because other Firebase features depend on
it, but **the App switches Analytics data collection off every time it starts**. We send no
analytics events, and the App does not use Analytics to measure or profile you.

### 1.5 Remote configuration — Firebase Remote Config
The App fetches a small set of configuration values from Google (for example, the minimum
supported app version, so we can tell you when an update is required). This is a **download
of settings**; it does not send your game data.

**Please note:** to perform this fetch, the Firebase SDK registers the persistent **Firebase
installation identifier** described in §1.3 with Google. This happens **when the App starts**,
because it is what allows us to deliver an urgent fix or service notice. It is not used for
advertising or profiling.

- **Purpose:** service integrity — remote kill switch and update notices.
- **Legal basis (GDPR):** **legitimate interest** in operating and securing the App
  (Art. 6(1)(f)).

### 1.6 Feedback you choose to send us
Settings has a **Send feedback** button. It is entirely optional — nothing is sent unless you
tap it, write a message, and press send in your own email app.

Tapping it opens **your** email app with a message addressed to us, pre-filled with a short
diagnostic block: the **App version**, your device's **country** and **language** settings,
and your **Android version, device manufacturer and model**. You can edit or delete any of
that before sending. Because the message comes from your own mailbox, we also receive **your
email address** and whatever you write.

- **Purpose:** replying to you, and reproducing the problem you are reporting.
- **Legal basis (GDPR):** **consent** (Art. 6(1)(a)) — you choose to write to us, and you can
  delete the diagnostic block, or simply not send the email.
- **Where it goes:** our support mailbox, hosted by **Google (Gmail)**. We do not forward it
  anywhere else, and we never use it for advertising or profiling.

### 1.7 Sharing a result
The App can export a picture of a finished board so you can share it. The image is written to
the App's own temporary storage and handed to whichever app you pick in the Android share
sheet. **We never receive it** — where it goes after that is governed by the app you chose.

### 1.8 Rating the App
After you have won a few games, the App may ask Google Play to show its standard "rate this
app" prompt. The prompt is Google Play's own screen: any rating or review you give goes to
Google Play under Google's terms, not to us directly, and Google decides whether the prompt
appears at all. The App only keeps the on-device count described in §1.1.

### 1.9 What we do NOT collect
Apart from a feedback email you choose to send us (§1.6), we collect no account, name, email
address, phone number, contacts, photos, files, precise location, or any other directly
identifying information. We run **no server of our own** — beyond that support mailbox and
the Google services named above, there is nowhere else your data goes.

---

## 2. Who receives your data, and where it goes

The only third-party recipient is **Google** (Google Ireland Limited and Google LLC), acting
through the Firebase Crashlytics and Remote Config services, through Google Play for the
rating prompt, and, if you email us, as the provider hosting our support mailbox (Gmail).

Google processes this data on servers **outside your country, including in the United
States**. For transfers out of the EEA/UK, Google relies on the European Commission's
**Standard Contractual Clauses** and the **EU–US Data Privacy Framework**. Google's handling
is governed by [Google's Privacy Policy](https://policies.google.com/privacy).

We do **not** sell your personal information, and we do not share it for advertising.

---

## 3. How long it is kept

| Data | Retention |
|---|---|
| Game data on your device | Until you clear the App's storage or uninstall it. We never receive it. If Android Backup is on, a copy stays in your own Google account backup until you delete it there — see §1.1. |
| Crash reports, session records and the installation identifier held by Google | Per Google's own retention schedules — see [Google's Privacy Policy](https://policies.google.com/privacy) and [Google's data-retention page](https://policies.google.com/technologies/retention). We hold no copy and cannot extend it. |
| A feedback email you chose to send us (§1.6) | Kept only as long as needed to deal with your message, then deleted. Ask us at any time and we will delete it sooner. |

---

## 4. Your choices and your rights

### 4.1 Controls on your device

- **Erase everything the App stores on your phone:**
  **Settings → Apps → Tic Tac Toe → Storage → Clear storage**. This also resets the
  installation identifier described in §1.3.
- **Remove the backed-up copy** (if Android Backup is on): delete the App's backup under
  **Settings → Google → Backup**.
- **Uninstalling** the App ends all further collection.

### 4.2 If you are in the EEA or the UK (GDPR)
You have the right to access, rectify, erase, restrict or object to processing, and to data
portability. Where we rely on consent (a feedback email, §1.6) you can withdraw it at any time,
and withdrawal does not affect processing already carried out. You may also complain to your
national supervisory authority.

Because we hold no account and no server-side record of you, the practical route for most of
these is the device-level controls in §4.1 — and, for data held by Google, Google's own
controls. For anything we do hold (a feedback email), write to us at §7.

### 4.3 If you are in California (CCPA/CPRA)
You have the right to know what is collected, to delete it, to correct it, and to opt out of
"sale" or "sharing" of personal information. **We do not sell your personal information, and
we do not share it for cross-context behavioural advertising** — the App shows no ads. We will
not discriminate against you for exercising any of these rights.

### 4.4 If you are in India (DPDP Act, 2023)
You have the right to access a summary of your personal data and its processing, to
correction and erasure, to nominate someone to exercise your rights, and to a grievance
mechanism. Our grievance contact is the address in §7 — please put "Privacy" in the subject
line. Where processing relies on your consent (a feedback email, §1.6), you can withdraw it at
any time by writing to us.

---

## 5. Security

Data on your device is protected by Android's app sandbox and, on modern devices, by the
device's own encryption. Traffic between the App and Google's services uses encrypted
connections (HTTPS/TLS). We hold no server and no database of our own, which removes an
entire category of risk — but no method of storage or transmission is perfectly secure, and
we cannot guarantee absolute security.

---

## 6. Children

The App is a **general-audience game**. It is not directed at children, and we do not
knowingly collect personal data from them. The App shows no ads to anyone.

Different laws set different ages: **under 13** in the United States (COPPA) and generally
**under 16** in the EEA, while **India's DPDP Act treats anyone under 18 as a child**.

If you believe a child has provided personal data through the App, contact us at the address
in §7. Because we run no server and hold no accounts, here is precisely what we can do:

- **An email a child sent us** (§1.6) is the one piece of personal data we hold ourselves. We
  will delete it on request and confirm that we have.
- **Game data** never reaches us at all. It is erased on the device itself via
  **Settings → Apps → Tic Tac Toe → Storage → Clear storage**, and — if Android Backup is
  switched on — by also deleting the App's backup under **Settings → Google → Backup**
  (§1.1, §4.1).
- **Crash reports and session records** are **pseudonymous**: they are tied to a random
  installation identifier, never to a name, an email address or an account. This means nobody
  — not us, and not Google — can look up "this particular child's" records from a name or an
  email. Clearing the App's storage or uninstalling it replaces that identifier and ends all
  further collection.

---

## 7. Contact and complaints

**sparkle.bit.games@gmail.com**

Use this address for any privacy question, to exercise any right above, or — for users in
India — to raise a **grievance** under the DPDP Act. Please put "Privacy" in the subject line
so we can route it quickly.

---

## 8. Changes to this policy

We may update this policy as the App changes — for example if we add a new service. Material
changes will be posted here with a revised "Last updated" date.
