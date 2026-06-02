---
title: Privacy Policy
---

# Privacy Policy — Goldly

_Last updated: June 2, 2026_

This Privacy Policy explains how the **Goldly** mobile app
("the app", "we") handles your information.

The app is a Vietnamese gold price tracker. It is designed to work on
your device and to fetch public gold price quotes from vang.today so
the prices you see are current. We do not run our own user-data server,
we do not have user accounts, and we do not sell your personal data.

## 1. Who we are

- App name: **Goldly**
- Developer: Hau Nguyen ([@haunguyenphuc1110](https://github.com/haunguyenphuc1110))
- Contact: ngphuchau1110@gmail.com

## 2. Information stored on your device

Goldly stores the following information locally on your device. This
information is not sent to Goldly servers.

| Data | Why the app uses it |
|---|---|
| Language preference (Vietnamese / English) | Render UI text in your chosen language |
| Cached gold price quotes and last-fetched timestamp | Show prices when offline, show freshness, and feed widgets |
| Portfolio / holdings entries | Let you track local gold quantity, source, cost basis, current value, and profit/loss |
| Price alert rules | Let you create local alerts for buy/sell prices crossing a threshold |
| Alert state, such as enabled, armed, and last-triggered status | Avoid repeated notifications for the same price crossing |
| Widget cache and widget language | Let the Android and iOS home-screen widgets display the latest known prices |

This information is stored using local app storage, such as
AsyncStorage. On iOS, widget-related data may also be stored in an App
Group container so the Goldly widget can read the latest cached prices.
Uninstalling the app removes app-local data.

## 3. Network requests

To show current gold prices, the app makes HTTPS requests to:

- **vang.today** — a public Vietnamese gold-price aggregator
  ([https://www.vang.today](https://www.vang.today))

These requests are read-only price queries. Goldly does not add your
name, email address, account identifier, portfolio entries, or alert
rules to these requests. Like any network request, the receiving
service may receive standard technical information such as IP address,
User-Agent, preferred language, and request time.

The Android and iOS home-screen widgets may make the same public price
requests or repaint from the cached snapshot. Widget refresh timing is
controlled by the operating system and may vary.

## 4. Widgets

Goldly includes home-screen widgets. Widgets display cached public gold
prices and freshness information. They do not display your portfolio or
alert thresholds.

On iOS, the widget reads cached data from the Goldly App Group. On
Android, the widget reads cached data from local app storage. A widget
may request a fresh public price snapshot from vang.today when the
operating system allows it or when you use a manual refresh control.

## 5. Notifications and permissions

Goldly intentionally requests as few permissions as possible:

| Permission | Why |
|---|---|
| Internet | Fetch gold price quotes from vang.today |
| Notifications | Send local price alerts when a threshold you created is crossed |
| Background processing / fetch | Best-effort local checks for enabled price alerts while the app is closed |
| Vibrate / haptics | Subtle haptic feedback for app interactions where supported |

You can revoke any of these permissions at any time from your device
Settings. The app will continue to work; the affected feature simply
stops being available.

Notification permission is requested only when you use alert features
that need notifications. Price alerts are local and best-effort.
Background delivery is controlled by the operating system and is not
guaranteed.

## 6. Information we do not collect

We want this to be explicit:

- We do not collect personal data.
- We do not collect analytics or usage statistics.
- We do not use advertising SDKs.
- We do not use tracking SDKs.
- We do not have user accounts or sign-in.
- We do not store your portfolio or alert rules on a Goldly server.
- We do not back up your data to any cloud service we control.

## 7. Retention and deletion

Goldly keeps local app data until you delete it in the app or uninstall
the app.

- Portfolio entries can be deleted from the Portfolio screen.
- Price alerts can be deleted from the Alerts screen.
- Language preference and cached prices are removed when the app is
  uninstalled.

Because Goldly does not maintain user accounts or store this data on a
Goldly server, there is no server-side account deletion request to make.

Your device or iCloud settings may affect system-level device backups.
Goldly does not control or receive those backups.

## 8. App updates

Goldly may use Expo services and Apple distribution systems to deliver
app updates or bug fixes. Update checks can include standard technical
information such as app version, runtime version, platform, and device
environment. They do not include your portfolio entries or alert rules.

Expo's privacy practices are described at
[https://expo.dev/privacy-explained](https://expo.dev/privacy-explained).

## 9. Financial information disclaimer

Goldly is for informational and reference purposes only. It does not
provide financial, investment, tax, or trading advice. Prices are
aggregated from public sources and may be delayed, unavailable, or
different from final retail transaction prices. Please verify prices
with the retailer before any transaction.

Goldly is not affiliated with SJC, DOJI, PNJ, Bảo Tín, or any listed
gold retailer.

## 10. Children's privacy

Goldly is intended for general audiences. We do not knowingly collect
information from anyone, including children.

## 11. Security

Because data is kept on your device, the security of your data is tied
to the security of your device (passcode, biometrics, full-disk
encryption). We recommend keeping your operating system up to date.

## 12. Changes to this policy

If we change this policy, we will update this page and update the "Last
updated" date at the top. Material changes will also be called out in
the app's release notes.

## 13. Contact

Questions about this policy or about how the app handles your data?

- Email: ngphuchau1110@gmail.com
- GitHub: [https://github.com/haunguyenphuc1110/goldly](https://github.com/haunguyenphuc1110/goldly)
