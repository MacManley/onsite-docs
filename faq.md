---
layout: default
title: FAQ & Troubleshooting
nav_order: 12
---

# FAQ & Troubleshooting
{: .no_toc }

Answers to common questions and fixes for typical issues.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## My photo date is wrong

**Symptom:** A photo shows the wrong date in OnSite, or sorting by capture date gives unexpected results.

**Cause:** The capture date comes from the photo's embedded EXIF metadata, not the date you imported it. If your camera's clock was wrong, or if the photo was edited or converted in a way that stripped or changed the EXIF data, the date may be incorrect.

**Fix:**
- Sort by **Upload date** instead of **Capture date** for a reliable order based on when you added the photo to OnSite.
- To fix the EXIF date, use a third-party photo editing app to correct the metadata before importing.

---

## Notifications didn't fire

**Symptom:** You expected an arrival or service notification but it didn't appear.

**Checklist:**
1. Confirm **Notifications** are enabled for OnSite in **Settings → OnSite → Notifications** on your device.
2. For arrival notifications, confirm **Site Arrival Notifications** is toggled on in the OnSite **Notifications** tab.
3. Check the site is not muted in the per-site notification list.
4. For arrival notifications, go to **Settings → OnSite → Location** and confirm access is set to **Always** (not "While Using").
5. Make sure the site has a valid address — sites without a location cannot trigger arrival alerts.
6. If your device was in **Focus** or **Do Not Disturb** mode, notifications may have been silenced at the system level.

---

## I can't find a site

**Symptom:** A site is missing from your list.

**Possible causes and fixes:**

| Cause | Fix |
|---|---|
| Site is archived | Open **Archived Sites** from the filter menu and restore it |
| Search filter is active | Clear the search bar |
| Different storage location on this device | Check **Settings → Storage Location** — if you use iCloud, make sure this device is signed into the same Apple ID |
| iCloud not finished syncing | Wait for the **Waiting for iCloud data to download…** status to clear |

---

## Storage is full

**Symptom:** OnSite shows a warning about iCloud storage being full, or your device is running low on space.

### iCloud storage full

OnSite shows: *"iCloud storage is full. Your latest changes are not being saved to iCloud."*

**Fix:** Free up iCloud space:
1. On your device, go to **Settings → [Your Name] → iCloud → Manage Account Storage**.
2. Delete backups, large app data, or upgrade your iCloud plan.

### Device storage full

If your device itself is running low:
1. Go to **Settings → General → iPhone Storage**.
2. Review which apps and media are using the most space.
3. Offload unused apps or delete large media files.

{: .note }
If you're using **On Device** storage, photos and files in OnSite count toward your device storage. Switching to **iCloud Drive** in **Settings → Storage Location** moves them to iCloud and frees local space.

---

## The app says "Migration Interrupted"

**Symptom:** After switching storage locations, the app shows a **Migration Interrupted** warning on launch.

**Cause:** The app was closed before it could finish moving data to the new storage location.

**Fix:** Tap **Retry** on the warning banner. Keep the app open until the migration completes. Your data is safe and has not been lost.

---

## Auto-Sort matched a photo to the wrong site

**Symptom:** A photo ended up assigned to the wrong site after running Auto-Sort.

**Cause:** Two sites may be close together and the photo's GPS coordinates fell within range of the wrong one.

**Fix:**
- Increase site separation or reduce the **Auto-sort radius** in **Settings → Location** to reduce overlap.
- Move the incorrectly matched photo manually by viewing it in the wrong site and deleting it, then re-adding it to the correct site.

---

## "Precise Location" shows Unavailable

**Symptom:** Settings shows **Precise Location: Unavailable**, and nearby sorting or arrival notifications aren't working properly.

**Fix:**
1. Go to **Settings → OnSite → Location** on your device.
2. Set location access to **Always**.
3. Make sure **Precise Location** is toggled on (iOS 14+).

If precise location is temporarily unavailable due to system restrictions, it will recover automatically when conditions improve.
