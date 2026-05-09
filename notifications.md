---
layout: default
title: Notifications
nav_order: 8
---

# Notifications
{: .no_toc }

OnSite can alert you when services are due and when you arrive at a job site.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Turning on notifications

OnSite requests notification permission during onboarding. If you skipped it, you can enable notifications manually:

1. Open your device **Settings** app.
2. Scroll down and tap **OnSite**.
3. Tap **Notifications** and turn them on.

---

## Arrival notifications

OnSite can detect when you arrive at a site and send a banner notification — even if the app is closed.

### Enabling arrival notifications

1. Open the **Notifications** tab in OnSite (found inside the Calendar tab).
2. Turn on the **Site Arrival Notifications** toggle.
3. If prompted, grant OnSite permission to use your location **Always** in device Settings.

{: .important }
Arrival notifications require **Always On** location access. If you've only granted **While Using**, go to **Settings → OnSite → Location** and change it to **Always**.

### Per-site notification control

By default, arrival alerts are enabled for all sites. You can mute individual sites:

1. Open the **Notifications** tab.
2. Find the site in the list.
3. Toggle it off to mute arrival alerts for that site.

Tap **Mute All** to silence every site at once, or **Unmute All** to re-enable them.

{: .note }
Turning off alerts for a site stops banners from appearing when you're within range. It does not affect service-due or invoice notifications.

---

## Service-due notifications

OnSite generates service-due alerts based on the **Service Interval** set on each job. These appear in the **Calendar** tab and as push notifications when a service date is reached.

No additional setup is needed — just make sure notifications are enabled for OnSite in device Settings.

---

## Troubleshooting notifications

### Arrival notification didn't fire

- Confirm **Site Arrival Notifications** is turned on in the Notifications tab.
- Check the site has a valid address with GPS coordinates.
- Go to **Settings → OnSite → Location** and confirm access is set to **Always**.
- Make sure the site is not muted in the per-site list.
- Check **Settings → OnSite → Notifications** is enabled at the system level.

### Service reminder didn't appear

- Confirm the job has a **Service Interval** greater than 0.
- Confirm OnSite notifications are enabled in device Settings.
- Check the **Calendar** tab — the reminder appears there even if a push notification is missed.

### Notifications tab shows "No sites added yet"

- Add at least one site with a valid address to begin tracking arrivals.
