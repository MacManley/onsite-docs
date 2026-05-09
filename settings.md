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

| Setting | Description |
|---|---|
| **Auto-sort radius** | How close a photo or contact must be to a site to be auto-matched (meters or feet) |
| **Precise Location** | Shows whether iOS has granted precise GPS access to OnSite |

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

Links to **Manage Notifications** — the same screen as the Notifications tab where you control site arrival alerts and per-site muting.

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

## Support

| Action | Description |
|---|---|
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
