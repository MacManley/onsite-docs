---
layout: default
title: Settings
nav_order: 10
---

# Settings
{: .no_toc }

Configure OnSite to match how you work — company details, units, storage, invoices, and more.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Opening Settings

Tap the **Settings** tab (rightmost tab in the tab bar).

---

## Company

Store your business details so they appear on any reports or exports you generate.

| Field | Description |
|---|---|
| **Company Logo** | Tap **Add Company Logo** to upload an image, or **Remove** to delete it |
| **Company Name** | Your business or trading name |
| **Phone Number** | Must be a valid phone number |
| **Email** | Must be a valid email address |
| **Website** | Your business website URL |

Changes save automatically.

---

## Units

Choose how distances are displayed throughout the app.

| Option | Description |
|---|---|
| **Metric** | Distances shown in meters and kilometers |
| **Imperial** | Distances shown in feet and miles |

This affects the auto-sort radius display and any distance-based features.

---

## Location

### Auto-sort radius

The auto-sort radius controls how close a photo, contact, or your physical location must be to a site to count as a match. It affects:

- **Photo auto-sort** — photos taken within this distance are assigned to the site.
- **Contact auto-sort** — contacts whose address falls within this distance are matched.
- **Currently on site** — sites you are physically within this distance of float to the top of the site list, highlighted.

**To adjust the radius:**

1. Tap the **Settings** tab.
2. Scroll to the **Location** section.
3. Drag the **Auto-sort radius** slider left (smaller) or right (larger).
   - Range: **20 – 2,000 meters** (or the equivalent in feet if Units is set to Imperial).
   - The current value is shown to the right of the label (e.g. **100 m** or **328 ft**).

The radius is displayed in meters or feet based on your **Units** setting.

{: .note }
A smaller radius (e.g. 50 m) gives more precise matching but may miss photos or contacts that are slightly off. A larger radius (e.g. 500 m) is more forgiving but can produce false matches in dense areas.

### Precise Location

| Status | Meaning |
|---|---|
| **Available** | iOS has granted precise GPS access — all location features work normally |
| **Unavailable** | Precise location is off or temporarily unavailable |

If **Precise Location** shows **Unavailable**, go to **Settings → OnSite → Location** on your device and enable precise location. Site detection and nearby sorting may be affected without it.

---

## Calendar

Control which days and holidays appear on your schedule calendar.

| Setting | Description |
|---|---|
| **Allow Holidays** | Toggle on to show public holidays on the calendar |
| **Include Regional Holidays** | Adds regional/local holidays when toggled on |
| **Working days** | Tap the day initials (M T W T F S S) to include or exclude days |

---

## Invoices

Set how long after a job completion before an invoice reminder appears.

- **Invoice Delay** — adjust using the stepper.
- **0** days = reminder appears the same day (shown as **Same day**).
- Maximum is **30 days**.

---

## Notifications

| Setting | Description |
|---|---|
| **Notification Time** | The time of day OnSite sends scheduled job reminders. Tap the time to open the picker and choose any hour and minute. |
| **Manage Notifications** | Opens the full notifications screen where you control site arrival alerts and per-site muting — the same screen as the Notifications tab. |

---

## Storage

Choose where OnSite saves your data.

### Storage options

| Option | Description |
|---|---|
| **On Device** | All data stays on this device. No iCloud needed. Not accessible from other devices. |
| **iCloud Drive** | Sites, photos, notes, and files sync across all devices on the same Apple ID. Requires iCloud. |

### Changing storage location

1. Go to **Settings → Storage Location**.
2. Tap the storage option you want.
3. OnSite migrates your data automatically. Do not close the app during migration.

{: .warning }
If the app is closed before migration finishes, OnSite shows a **Migration Interrupted** warning on next launch. Tap **Retry** to complete the migration safely — your data is not lost.

### iCloud status indicators

| Status | Meaning |
|---|---|
| **iCloud Available** | iCloud is connected and syncing |
| **iCloud Not Available** | No iCloud account. Sign in via **Settings → [Your Name] → iCloud** |
| **Waiting for iCloud data to download…** | Initial sync in progress |
| **iCloud storage is full** | Free space in **Settings → [Your Name] → iCloud → Manage Account Storage** |

### Settings sync

When using iCloud, app settings (invoice delay, units, calendar preferences) are synced via iCloud Key-Value Store.

- **Push Settings to iCloud Now** — manually push local settings to iCloud.
- **Pull Settings from iCloud** — overwrite local settings with what's stored in iCloud.

---

## What's New

Tap **What's New** to view a summary of recent updates and feature additions. This is the same content shown on first launch after an update.

---

## Support

| Action | Description |
|---|---|
| **Contact Support** | Opens a contact form on the OnSite website to send a message to the developer |
| **Documentation** | Opens this documentation site in your browser |
| **Rate the App** | Opens the App Store review prompt |
| **Share** | Share a link to OnSite with someone |

---

## About

| Item | Description |
|---|---|
| **Version** | The current installed version of OnSite |
| **Replay Onboarding** | Walk through the onboarding screens again |
| **Reset All Data** | Permanently deletes all sites, photos, files, and company data and resets all settings |

{: .warning }
**Reset All Data** is irreversible. All sites, photos, notes, files, and company settings are permanently deleted and cannot be recovered. Onboarding restarts immediately after reset.
