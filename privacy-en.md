# Privacy Policy — AutoPot

**Last updated:** 8 October 2026
**Version:** 1.1

This Privacy Policy explains which personal data the **AutoPot** app processes, why, on
what legal basis, with whom it is shared, how long it is kept, and what rights you have.
AutoPot is an app that lets a fixed group of people fairly split the costs of one or
more shared cars (trips, refuelling and expenses).

We process as little data as possible, use **no** tracking, **no** advertising and **no**
analytics, and we **never** sell your data.

---

## 1. Who is responsible?

The data controller for your data is:

- **Ditmar Zuiderwijk** (private individual), the Netherlands
- **Email:** ditmar.hhs@gmail.com

You can use this email address for any question about this policy or about your data.

---

## 2. What data we process

We only process the data needed to make the app work. We do **not** ask for a phone
number, date of birth, payment details, photos or contacts.

### a. Account data
- **Email address** — to sign in and identify your account.
- **Password** — stored encrypted/hashed by our backend provider; we cannot read your
  password.
- **User ID** — a random unique code (UUID) that identifies your account internally.

### b. Profile and group data
- **Display name** — the name other members of your car group see.
- **Role** — whether you are an admin or a member in a group.
- **Car/group name** and group settings (such as the default per-kilometre surcharge).
- **Membership periods** — when you were active or temporarily absent in a group, and
  join/leave requests.

### c. Content you enter
- **Trips** — date, odometer readings (start/end), an optional description and who drove.
- **Refuelling / trip lists** — date, amount, litres filled and who paid.
- **Expenses** — date, description, amount, who paid and who shares in it.
- **Calendar claims** — when you reserve the car (date/part of day and an optional title).

### d. Location data (optional, only with your choice)
- When logging a trip you can choose yourself to add your **current location** as the
  car's location. If you do, we store the **coordinates (latitude/longitude)** and a
  **human-readable address** with that trip, so the group knows where the car is.
- This only happens if you choose it at that moment; you can also skip location and enter
  it manually. There is **no** background location tracking.
- See section 4 for details.

### e. Data on your device (not on our servers)
- Your **login session (token)** is stored securely on your device (iOS Keychain).
- Your **preferences** for notifications and for automatic location capture are stored
  locally on your device.

### What we do NOT collect
- No advertising identifiers (IDFA), no cross-app or cross-site tracking.
- No analytics SDKs, no third-party crash reporting.
- No camera, microphone, contacts, phone calendar, health or photos.

---

## 3. Purposes and legal bases (GDPR)

| Data | Purpose | Legal basis (GDPR art. 6) |
|---|---|---|
| Account (email, password, user ID) | Create, secure and sign you into your account | Performance of a contract (art. 6(1)(b)) |
| Profile, group, membership | Deliver the core service: splitting costs fairly within your group | Performance of a contract (b) |
| Trips, refuelling, expenses, calendar | Keep the bookkeeping and cost split of the shared car | Performance of a contract (b) |
| Location on a trip | Share the car's last known location with your group | **Consent** (a) — per use, withdrawable |
| Security and abuse prevention | Protect the app and accounts | Legitimate interest (f) |
| Push notifications (once available) | Keep you informed of activity in your group | **Consent** (a) |

You are not obliged to provide data, but without an email address and display name you
cannot use the app. Location and notifications are entirely optional.

---

## 4. Location data in detail

- AutoPot uses your location **only while you are using the app** and only after you
  have given permission (iOS asks this with the standard "While Using the App" prompt).
- Location is fetched **once** when you tap "use my location" on a trip — there is **no**
  continuous or background tracking.
- We store the coordinates and the derived address only with the relevant trip, so your
  group can see where the car was last parked.
- You can withdraw your permission at any time via **iOS Settings → Privacy → Location
  Services → AutoPot**. Locations already saved are not removed automatically; you can
  delete them by editing or deleting the relevant trip, or by contacting us.

---

## 5. Who we share data with (processors)

We never sell or rent your data and do not use it for advertising. We use one external
party to operate the app (a "processor" acting solely on our instructions):

- **Supabase** — our backend and database provider. This is where your account and app
  data are securely stored. The data is hosted in the **European Union**. Supabase
  processes the data only to provide the app's storage and sign-in functionality.

In addition, distribution and billing of the app run through **Apple** (App Store /
StoreKit). Apple processes any purchase and subscription data under its own privacy
policy; we do not receive full payment details.

We may disclose data where required by law (for example, in response to a lawful request
by an authority).

---

## 6. Transfers outside the European Economic Area (EEA)

Your app data is stored on servers **within the EU**. For the core of the app there is
**no** transfer outside the EEA.

If in the future a service is used that processes data outside the EEA (for example a push
notification service), we will put appropriate safeguards in place, such as the European
Commission's **Standard Contractual Clauses**, and update this policy.

---

## 7. How long we keep data

- We keep **account data and content** for as long as your account exists and you are a
  member of a group.
- **If you delete your account**, we delete or anonymise your personal data. Because a
  shared ledger must remain correct for the other members too, already-processed
  transactions (trips/expenses) may be retained in **anonymised** form — detached from
  your name and email — for the accuracy of the group's bookkeeping.
- **Backups** that still contain data are overwritten in the normal backup cycle within
  at most **30 days**.
- **Local preferences** on your device are removed when you delete the app.

---

## 8. Security

We take appropriate technical and organisational measures to protect your data:

- Encrypted connections (HTTPS/TLS) between the app and the server.
- Encrypted storage on the server side and hashed passwords.
- **Row Level Security:** the database enforces that you can only see data from your own
  group(s) — not from other groups.
- Your login session is kept on your device in the secure iOS Keychain.

No system is 100% secure; in the event of a data breach posing a high risk, we will
inform you and the supervisory authority as required by law.

---

## 9. Your rights

Under the GDPR you have the right to:

- **Access** the data we hold about you;
- request **rectification** (correction) of inaccurate data;
- request **erasure** ("right to be forgotten");
- **restrict** processing;
- **object** to processing based on legitimate interest;
- receive your data in a portable format (**data portability**);
- **withdraw consent** you have given (for example for location or notifications), without
  affecting prior processing.

You exercise these rights by managing your account in the app or by emailing
**ditmar.hhs@gmail.com**. We respond within the statutory period (in principle within one
month).

You also have the right to lodge a complaint with the Dutch supervisory authority, the
**Autoriteit Persoonsgegevens** (autoriteitpersoonsgegevens.nl).

---

## 10. Deleting your account and data

You can delete your account and associated personal data:

- **In the app**, via Settings → (delete account), or
- by sending a request to **ditmar.hhs@gmail.com**.

What happens to shared transactions on deletion is described in section 7.

---

## 11. Children

AutoPot is intended for adults who share a car and is not directed at children. We do
not knowingly collect data from persons under 16. If you believe a child has provided us
data, please contact us so we can delete it.

---

## 12. Automated decision-making

We do **not** carry out automated decision-making or profiling with legal effects. The
cost calculations in the app are simple, transparent rules and not profiling.

---

## 13. Changes to this policy

We may update this Privacy Policy, for example when new features are added. The date at
the top indicates the most recent change. For significant changes we will inform you in or
through the app.

---

## 14. Contact

Questions or requests? Email **ditmar.hhs@gmail.com**.
