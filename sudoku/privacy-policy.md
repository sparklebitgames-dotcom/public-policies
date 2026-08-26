# Privacy Policy — Sudoku

_Last updated: 27 August 2026_

This policy covers the **Sudoku** app (package `com.sparklebit.sudoku`, "the App"),
published by **Sparkle Bit Games** ("we", "us").

**Who is responsible for your data (data controller / data fiduciary)**
Sparkle Bit Games · contact: **sparkle.bit.games@gmail.com**
For users in India, this address is also our **grievance contact** under the Digital
Personal Data Protection Act, 2023 (see [Contact and complaints](#contact-and-complaints)).

**In short:** the App has no accounts and no server of ours. Your puzzles stay on your
phone. The App does send some technical and advertising data to Google so it can show
ads, report crashes, and check for a required update — and where the law requires
consent, that collection is off until you allow it.

---

## 1. What we collect, why, and on what legal basis

### 1.1 Gameplay data — stays on your device
Puzzle progress, notes/pencil marks, best times, daily-challenge streak, coin balance,
and settings (including your theme choice).

Stored locally via Android DataStore/SharedPreferences. **We never receive it** — it is not
sent to us, and we operate no server it could be sent to.

One thing to be clear about: if **Android Backup** is switched on for your device (Android
**Settings → Google → Backup**), Android itself copies some of this into **your own Google
account backup** — your records, meaning the daily-challenge streak, last-completed date,
best times, and your in-app settings. That copy belongs to your Google account rather than
to us, and we cannot read it. It does mean that **uninstalling the App does not necessarily
erase those records**: reinstalling later, on the same phone or a new one, can restore them.
When you set up a new phone, Android's device-to-device transfer additionally carries your
in-progress puzzle and coin balance across.

If you want that copy gone too, turn off Android Backup for the App, or delete the App's
backup under **Settings → Google → Backup**.

- **Purpose:** to let you resume a puzzle and keep your records.
- **Legal basis (GDPR):** performance of the service you requested (Art. 6(1)(b)).

### 1.2 Advertising — Google AdMob
The App shows ads via Google AdMob. AdMob and its partners may collect your **device
advertising ID**, **IP address** (from which approximate, city-level location may be
inferred), and **ad-interaction data** in order to serve, cap, and measure ads — and,
**only where you have consented**, to personalise them.

- **Purpose:** to fund the App, which is free to play.
- **Legal basis (GDPR):** your **consent** for personalised ads and for storing/reading
  identifiers on your device (Art. 6(1)(a)). Where you do not consent, ads are still
  shown but are **non-personalised**.

### 1.3 Crash diagnostics — Firebase Crashlytics
If the App crashes we receive a diagnostic report: the stack trace, device model,
operating-system version, and a Firebase installation identifier. It contains no
puzzle content and does not identify you by name.

- **Purpose:** to find and fix defects that break the App.
- **Legal basis (GDPR):** our **legitimate interest** in a functioning, secure app
  (Art. 6(1)(f)).

### 1.4 Analytics — Firebase Analytics
**We send no custom analytics events of our own.** The Firebase Analytics SDK
automatically collects a standard set of app-lifecycle events — such as first open,
session start, app updates and removals, and screen views — together with an
**app-instance identifier** and the advertising ID.

- **Purpose:** to understand basic usage volumes and stability.
- **Legal basis (GDPR):** your **consent** (Art. 6(1)(a)). Analytics collection is
  **disabled by default in the App's manifest** and is switched on only when the consent
  signals allow it.

### 1.5 Remote configuration — Firebase Remote Config
The App fetches a small set of configuration values from Google (for example, the
minimum supported app version, so we can tell you when an update is required). This is
a **download of settings**; it does not send your gameplay data.

**Please note:** to perform this fetch, the Firebase SDK registers a persistent
**Firebase installation ID** with Google. This happens **when the App starts, before any
consent choice is made**, because it is what allows us to deliver an urgent fix or
service notice. It is not used for advertising or profiling.

- **Purpose:** service integrity — remote kill switch and update notices.
- **Legal basis (GDPR):** **legitimate interest** in operating and securing the App
  (Art. 6(1)(f)).

### 1.6 Feedback you choose to send us
Settings has a **Send feedback** button. It is entirely optional — nothing is sent unless
you tap it, write a message, and press send in your own email app.

Tapping it opens **your** email app with a message addressed to us, pre-filled with a short
diagnostic block: the **App version**, your device's **country** and **language** settings,
and your **Android version and device model**. You can edit or delete any of that before
sending. Because the message comes from your own mailbox, we also receive **your email
address** and whatever you write.

- **Purpose:** replying to you, and reproducing the problem you are reporting.
- **Legal basis (GDPR):** **consent** (Art. 6(1)(a)) — you choose to write to us, and you
  can delete the diagnostic block, or simply not send the email.
- **Where it goes:** our support mailbox, hosted by **Google (Gmail)**. We do not forward it
  anywhere else, and we never use it for advertising or profiling.

### 1.7 What we do NOT collect
Apart from a feedback email you choose to send us (§1.6), we collect no account, name,
email address, phone number, contacts, photos, files, precise location, or any other
directly identifying information. We run **no server of our own** — beyond that support
mailbox and the Google services named above, there is nowhere else your data goes.

---

## 2. Who receives your data, and where it goes

The only third-party recipient is **Google** (Google Ireland Limited and Google LLC),
acting through the AdMob, Firebase Analytics, Crashlytics and Remote Config services,
— for advertising — Google's advertising partners, and, if you email us, as the provider
hosting our support mailbox (Gmail).

Google processes this data on servers **outside your country, including in the United
States**. For transfers out of the EEA/UK, Google relies on the European Commission's
**Standard Contractual Clauses** and the **EU–US Data Privacy Framework**. Google's
handling is governed by [Google's Privacy Policy](https://policies.google.com/privacy).

We do **not** sell your personal information for money.

---

## 3. How long it is kept

| Data | Retention |
|---|---|
| Gameplay data on your device | Until you clear the App's storage or uninstall it. We never receive it. If Android Backup is on, a copy of your records stays in your own Google account backup until you delete it there — see §1.1. |
| Advertising / analytics / crash data held by Google | Per Google's own retention schedules — see [Google's Privacy Policy](https://policies.google.com/privacy) and [Google's data-retention page](https://policies.google.com/technologies/retention). We hold no copy and cannot extend it. |
| A feedback email you chose to send us (§1.6) | Kept only as long as needed to deal with your message, then deleted. Ask us at any time and we will delete it sooner. |

---

## 4. Your choices and your rights

### 4.1 Controls inside the App and on your device
- **Change or withdraw your advertising consent.** Where the consent framework applies
  to you (for example in the EEA, the UK, and certain US states), **Settings → Privacy
  options** in the App re-opens the consent form. Withdrawing is as easy as giving
  consent. Outside those regions this entry point may not be shown, because no consent
  form is served to you.
- **Reset or delete everything the App has stored** at any time: Android
  **Settings → Apps → Sudoku → Storage → Clear storage**, or simply uninstall. If Android
  Backup is switched on, delete the App's backup under **Settings → Google → Backup** as
  well — otherwise your records can come back the next time you install (§1.1).
- **Reset or delete your advertising ID** at any time: Android
  **Settings → Google → Ads**, where you can also turn off ad personalisation
  device-wide.

### 4.2 If you are in the EEA or the UK (GDPR)
You have the right to **access** your data, to **rectify** it, to **erase** it, to
**restrict** or **object to** processing, to **data portability**, and to **withdraw
consent** at any time (withdrawal does not affect processing already carried out).

Because we operate no server and hold no account, the only personal data we ever hold is a
**feedback email you chose to send us** (§1.6) — write to us and we will retrieve, correct,
export or delete it. Apart from that, **we hold no personal data about you**: requests about
the advertising, analytics and crash data described above are directed to **Google**, which
acts as controller or processor for it, and we will point you to the right Google mechanism.

You also have the right to **lodge a complaint with your national data protection
supervisory authority**.

### 4.3 If you are in California (CCPA/CPRA)
In the past 12 months the App has enabled the collection of **identifiers** (advertising
ID, app-instance/installation ID), **internet or network activity** (app and ad
interactions), **coarse location inferred from IP address**, and **device diagnostics**,
for the purposes described in section 1.

We do not sell personal information for money. However, allowing personalised
advertising may qualify as **"sharing" for cross-context behavioural advertising** under
the CPRA. You may **opt out** by declining or withdrawing consent in **Settings →
Privacy options**, and/or by turning off ad personalisation in **Settings → Google →
Ads**. You also have the rights to **know**, to **delete**, to **correct**, and to
**non-discrimination** — we do not degrade the App for exercising any of them.

### 4.4 If you are in India (DPDP Act, 2023)
You may **withdraw consent**, **request erasure** of your personal data, and **raise a
grievance** with us using the contact below. We will respond within the period required
by law. Withdrawal is available in-app via **Settings → Privacy options** and, for
device-level identifiers, via **Settings → Google → Ads**.

The same practical limits described in §4.2 apply to an erasure request: the only
personal data we hold, and can therefore erase ourselves, is a **feedback email you chose
to send us** (§1.6). Gameplay data never reaches us and is erased on your own device
(§4.1). The advertising, analytics and crash data is **pseudonymous** — tied to
resettable device identifiers rather than to you — so it cannot be looked up from your
name or email address by us or by Google; the effective control there is resetting or
deleting the advertising ID under **Settings → Google → Ads** (§6).

---

## 5. Security

Data in transit to Google is protected with **HTTPS/TLS**. Gameplay data is held in the
App's **private, sandboxed storage**, which other apps cannot read. Release builds are
code-shrunk and obfuscated. We hold no server-side database of user data, which
materially limits what a breach could expose.

If a breach affecting personal data occurs, we will notify the relevant supervisory
authority and affected users where the applicable law requires it.

---

## 6. Children

The App is a general-audience puzzle game. It is **not directed at children**, we do not
knowingly collect personal data from children, and we do not target ads at them.

Different laws set different ages: **under 13** in the United States (COPPA) and
generally **under 16** in the EEA, while **India's DPDP Act treats anyone under 18 as a
child** and restricts tracking and targeted advertising to them.

If you believe a child has provided personal data through the App, contact us at the
address in §7. Because we run no server and hold no accounts, here is precisely what we
can do:

- **An email a child sent us** (§1.6) is the one piece of personal data we hold
  ourselves. We will delete it on request and confirm that we have.
- **Gameplay data** never reaches us at all. It is erased on the device itself via
  **Settings → Apps → Sudoku → Storage → Clear storage**, and — if Android Backup is
  switched on — by also deleting the App's backup under **Settings → Google → Backup**
  (§1.1, §4.1).
- **Advertising, analytics and crash data** is **pseudonymous**: it is tied to resettable
  device identifiers, never to a name, an email address or an account. This means nobody —
  not us, and not Google — can look up "this particular child's" records from a name or an
  email, and there is no request form that would change that. Google says the same of its
  own systems. What *does* work, immediately and entirely under your control, is
  **resetting or deleting the device's advertising ID** and **turning off ad
  personalisation**, both under **Settings → Google → Ads**. Uninstalling the App ends all
  further collection.

---

## 7. Contact and complaints

**sparkle.bit.games@gmail.com**

Use this address for any privacy question, to exercise any right above, or — for users
in India — to raise a **grievance** under the DPDP Act. Please put "Privacy" in the
subject line so we can route it quickly.

---

## 8. Changes to this policy

We may update this policy as the App changes — for example if we add an ad format or a
new service. Material changes will be posted here with a revised "Last updated" date.
