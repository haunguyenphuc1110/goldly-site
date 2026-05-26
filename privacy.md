---
title: Privacy Policy
---

# Privacy Policy — Goldly

_Last updated: May 26, 2026_

This Privacy Policy explains how the **Goldly** mobile app
("the app", "we") handles your information.

The app is a Vietnamese gold price tracker. It is designed to work
entirely on your device, with one exception: it fetches public gold
price quotes from vang.today so the prices you see are current. We do
not run our own server, we do not have user accounts, and we do not
collect, transmit, or sell your personal data.

## 1. Who we are

- App name: **Goldly**
- Developer: Hau Nguyen ([@haunguyenphuc1110](https://github.com/haunguyenphuc1110))
- Contact: ngphuchau1110@gmail.com

## 2. Information the app handles

All of the following stays on your device. None of it is sent to us or
to any third party (other than the public price-quote provider noted
in section 3).

| Data | Why the app uses it |
|---|---|
| Language preference (Vietnamese / English) | Render UI text in your chosen language |
| Cached gold price quotes | Show prices when offline and feed the home-screen widget |
| Last-fetched timestamp | Display how fresh the prices are (the "Cập nhật N phút trước" line) |

This information is stored locally using your device's secure storage
(AsyncStorage on Android). Uninstalling the app removes this data.

## 3. Network requests

To show current gold prices, the app makes HTTPS requests to:

- **vang.today** — a public Vietnamese gold-price aggregator
  ([https://www.vang.today](https://www.vang.today))

These requests are read-only price queries. They do not include
personal information, account identifiers, or device identifiers
beyond the standard headers a mobile network client sends (User-Agent,
preferred language, etc.).

The Android home-screen widget makes the same requests on an hourly
cadence, only during Vietnamese business hours (08:00–18:00 ICT,
Mon–Sat). Outside that window the widget repaints from the cached
snapshot without hitting the network.

## 4. Permissions the app requests

Goldly intentionally requests as few permissions as possible:

| Permission | Why |
|---|---|
| Internet | Fetch gold price quotes from vang.today |
| Vibrate | Subtle haptic feedback on the chart crosshair and the refresh button |

You can revoke any of these permissions at any time from your device
Settings. The app will continue to work; the affected feature simply
stops being available.

## 5. Information we do not collect

We want this to be explicit:

- We do not collect personal data.
- We do not collect analytics or usage statistics.
- We do not use advertising SDKs.
- We do not use tracking SDKs.
- We do not have user accounts or sign-in.
- We do not share data with third parties.
- We do not back up your data to any cloud service we control.

## 6. Over-the-air app updates

The app uses Expo's update service to deliver bug fixes and improvements
to the app code. When the app starts, it asks Expo whether a newer build
is available. This request includes standard technical information
(app version, runtime version, platform) and does not include any
personal information from inside the app.

Expo's privacy practices are described at
[https://expo.dev/privacy-explained](https://expo.dev/privacy-explained).

## 7. Children's privacy

Goldly is intended for general audiences. We do not knowingly collect
information from anyone, including children. Because no personal
information leaves the device, the app does not transmit children's
data.

## 8. Security

Because data is kept on your device, the security of your data is tied
to the security of your device (passcode, biometrics, full-disk
encryption). We recommend keeping your operating system up to date.

## 9. Changes to this policy

If we ever change this policy — for example, if a future feature
introduces price alerts, cloud backup, or portfolio tracking — we will
update this page and update the "Last updated" date at the top.
Material changes will also be called out in the app's release notes.

## 10. Contact

Questions about this policy or about how the app handles your data?

- Email: ngphuchau1110@gmail.com
- GitHub: [https://github.com/haunguyenphuc1110/goldly](https://github.com/haunguyenphuc1110/goldly)
