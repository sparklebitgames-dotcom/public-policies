# Privacy Policy — Sudoku

_Last updated: 28 July 2026_

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

Stored locally via Android DataStore/SharedPreferences. **It is never transmitted to us
or to anyone else.** Uninstalling the App deletes it.

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

### 1.6 What we do NOT collect
No account, name, email address, phone number, contacts, photos, files, precise
location, or any other directly identifying information. We run **no server of our own**
— beyond the Google services named above, there is nowhere else your data goes.

---

## 2. Who receives your data, and where it goes

The only third-party recipient is **Google** (Google Ireland Limited and Google LLC),
acting through the AdMob, Firebase Analytics, Crashlytics and Remote Config services,
and — for advertising — Google's advertising partners.

Google processes this data on servers **outside your country, including in the United
States**. For transfers out of the EEA/UK, Google relies on the European Commission's
**Standard Contractual Clauses** and the **EU–US Data Privacy Framework**. Google's
handling is governed by [Google's Privacy Policy](https://policies.google.com/privacy).

We do **not** sell your personal information for money.

---

## 3. How long it is kept

| Data | Retention |
|---|---|
| Gameplay data on your device | Until you clear the App's storage or uninstall it. We never receive it. |
| Advertising / analytics / crash data held by Google | Per Google's own retention schedules — see [Google's Privacy Policy](https://policies.google.com/privacy) and [Google's data-retention page](https://policies.google.com/technologies/retention). We hold no copy and cannot extend it. |

---

## 4. Your choices and your rights

### 4.1 Controls inside the App and on your device
- **Change or withdraw your advertising consent.** Where the consent framework applies
  to you (for example in the EEA, the UK, and certain US states), **Settings → Privacy
  options** in the App re-opens the consent form. Withdrawing is as easy as giving
  consent. Outside those regions this entry point may not be shown, because no consent
  form is served to you.
- **Reset or delete everything the App has stored** at any time: Android
  **Settings → Apps → Sudoku → Storage → Clear storage**, or simply uninstall.
- **Reset or delete your advertising ID** at any time: Android
  **Settings → Google → Ads**, where you can also turn off ad personalisation
  device-wide.

### 4.2 If you are in the EEA or the UK (GDPR)
You have the right to **access** your data, to **rectify** it, to **erase** it, to
**restrict** or **object to** processing, to **data portability**, and to **withdraw
consent** at any time (withdrawal does not affect processing already carried out).

Because we operate no server and hold no account, **we hold no personal data about you
to retrieve, correct, export or delete** — requests about the advertising, analytics and
crash data described above are directed to **Google**, which acts as controller or
processor for it. Write to us and we will point you to the right Google mechanism.

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
child** and restricts tracking and targeted advertising to them. If you believe a child
has provided personal data through the App, contact us and we will delete it.

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
