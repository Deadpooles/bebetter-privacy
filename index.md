# Be Better — Privacy Policy

> I might not always know what I'm doing. But I know one thing for sure: I don't
> want your data. I never receive it, I never see it — I wouldn't even know how to
> reach it if I tried. That was never the point.
>
> The point is you. I just want you to **be better** — or, on the hard days, at
> least not worse.
>
> Free. No ads. No foul play. Forever.

**Effective date:** June 20, 2026
**Last updated:** June 20, 2026

Be Better is an offline-first fitness, wellness and cognitive-habit app. It runs
on your device. We — the developer — operate **no servers, no user accounts of
our own, and no advertising**. We do not collect, sell, or share your personal
data. This page explains exactly what data the app touches, where it stays, and
the few cases where data leaves your device — always under your control.

**Contact:** deadpooles201@gmail.com

---

## 1. Data stored on your device

Everything you create in the app — quests, workouts, habit and dependency logs,
XP and streaks, body metrics (weight, body-fat %), and your preferences — is
stored **only in local storage on your phone**. It is never sent to us.
Uninstalling the app deletes this data (make a backup first if you want to keep
it).

## 2. Health Connect data (read-only)

With your explicit permission, Be Better reads health and fitness data from
**Android Health Connect** to personalize your experience — for example, to
adapt workouts and to show recovery, sleep and activity insights. The app
**only reads** from Health Connect; it never writes to it.

Data types the app may read:

- **Activity:** steps, distance, floors climbed, active calories, total
  calories, basal metabolic rate, activity intensity, exercise / workouts
- **Heart & vitals:** heart rate, resting heart rate, heart-rate variability,
  respiratory rate, oxygen saturation, blood pressure, blood glucose, body
  temperature, skin temperature
- **Sleep:** sleep sessions and stages
- **Body:** weight, height, body-fat percentage, lean body mass
- **Intake:** hydration, nutrition
- **Reproductive health:** menstruation

How this data is handled:

- It is **processed entirely on your device.**
- It is **never transmitted to us or to any third party.**
- It is **not included in any backup file.** If you move to a new phone, the app
  re-reads it from Health Connect on that device; we never copy it off-device.
- You can **revoke access at any time** in Health Connect settings; the app
  stops reading immediately.

> Note: the current development version requests the full set of permissions
> above so each feature can be evaluated on a real device. You grant only what
> you choose, and any permission you do not grant reads nothing.

## 3. Optional Google Drive backup

If you choose to sign in with Google and turn on backup, the app writes a single
backup file (`be_better_backup.json`) into the hidden, app-private
`appDataFolder` of **your own Google Drive**.

- It happens **only when you explicitly trigger a backup.**
- The file contains your app data (quests, logs, XP, body metrics, settings).
  It does **not** contain Health Connect data.
- It goes to **your** Google account — **not to us.** We run no server and can
  never receive or access this file.
- Your Google sign-in is used **solely as the key to your own Drive.** We do not
  create a "Be Better account" for you.
- You can **delete the backup** from inside the app or from your Google Drive at
  any time.
- Transport is encrypted (HTTPS / TLS). Google's handling of files in your Drive
  is governed by [Google's Privacy Policy](https://policies.google.com/privacy).

## 4. City search (Open-Meteo)

When you search for a city — to set your location for sleep and daylight
calculations — the **city name you type** is sent to the
[Open-Meteo](https://open-meteo.com/) geocoding API to look up coordinates. This
happens **only while you actively search.** No identity, account, or other data
is sent — just the text query. The resulting coordinates are stored on your
device, and all further calculations run offline. See
[Open-Meteo's terms](https://open-meteo.com/en/terms).

## 5. Crash reports and usage statistics

The app currently collects **neither.** If crash reporting or anonymous usage
statistics are added in the future, they will be **off by default** and require
your **explicit opt-in.** They would never include your name, your entries, or
anything identifying you — only anonymous, aggregate signals (for example, how
many people use a particular screen) used to fix bugs and improve the app.

## 6. No ads, no tracking, no sale

The app contains no advertising SDKs, no third-party analytics, and no tracking
identifiers. We do not sell or share your data — because we never receive it.

## 7. Children

Be Better is not directed at children under 13 and collects no data from anyone.

## 8. Your control

- All your data is local and yours.
- You can export or back up at any time — the backup is a plain, documented JSON
  file you can open without the app.
- You can revoke Health Connect or Google permissions at any time in system
  settings.
- Uninstalling the app removes all local data.

## 9. Changes to this policy

If this policy changes, the updated version will be posted at this URL with a new
"Last updated" date.

## 10. Contact

Questions about privacy: **deadpooles201@gmail.com**
