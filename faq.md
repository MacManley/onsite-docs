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

## Why do my OnSite notifications not work?

This is usually a device-level permissions issue rather than anything wrong with the app itself.

**Step-by-step checklist:**
1. Go to your device **Settings → OnSite → Notifications** and confirm they are turned **on**.
2. Check **Notification Style** is not set to **Off**, set it to **Banners** or **Alerts**.
3. Make sure **Do Not Disturb** or a **Focus** mode isn't blocking OnSite. Go to **Settings → Focus** and check that OnSite is allowed.
4. For **arrival notifications** specifically, go to **Settings → OnSite → Location** and set it to **Always** — "While Using" is not enough.
5. Inside OnSite, open the **Notifications** tab and confirm **Site Arrival Notifications** is toggled on and the site is not muted.
6. Make sure the site has a valid address — OnSite cannot detect arrival at a site with no location set.
7. Restart the app and, if the issue persists, restart your device.

{: .note }
If notifications work sometimes but not always, check that Low Power Mode isn't restricting background activity. Go to **Settings → Battery** and turn off **Low Power Mode**.

---

## My photo date is wrong

**Symptom:** A photo shows the wrong date in OnSite, or sorting by capture date gives unexpected results.

**Cause:** The capture date comes from the photo's embedded EXIF metadata, not the date you imported it. If your camera's clock was wrong, or if the photo was edited or converted in a way that stripped or changed the EXIF data, the date may be incorrect.

**Fix:**
- Sort by **Upload date** instead of **Capture date** for a reliable order based on when you added the photo to OnSite.
- To fix the EXIF date, use a third-party photo editing app to correct the metadata before importing.

---

## The Schedule tab is empty

**Symptom:** Nothing appears in the Calendar tab even though you have jobs set up.

**Cause:** Jobs only appear in the schedule list when they have a **Service Interval** set. Due-date-only jobs appear on the calendar grid, not in the SERVICE list.

**Fix:**
1. Open the site and tap the job.
2. Tap **Edit** and set a **Service Interval** (in months) — the job will appear in the SERVICE list when it's due or overdue.

{: .note }
If you used a **Due Date** instead of a service interval, open the **Calendar** tab and navigate to the due date. The job appears there as a flag marker, turning red when overdue. Due date jobs do not appear in the SERVICE list.

---

## I can't find a site

**Symptom:** A site is missing from your list.

| Cause | Fix |
|---|---|
| Site is archived | Tap the archive icon in the toolbar and restore it |
| Search or job type filter is active | Clear the search bar and deselect any job type chips |
| Different storage on this device | Check **Settings → Storage Location** — iCloud requires the same Apple ID on all devices |
| iCloud not finished syncing | Wait for **Waiting for iCloud data to download…** to clear |

---

## My data isn't syncing to my other device

**Symptom:** Sites, photos, or jobs added on one device don't appear on another.

**Checklist:**
1. Confirm both devices are using **iCloud Drive** storage. Go to **Settings → Storage Location** on each device.
2. Make sure both devices are signed into the **same Apple ID**.
3. Check that iCloud Drive is enabled on both devices: **Settings → [Your Name] → iCloud → iCloud Drive**.
4. Give it a few minutes — large amounts of data (especially photos) can take time to sync over iCloud.
5. If OnSite shows **Waiting for iCloud data to download…**, the sync is still in progress.

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
- Reduce the **Auto-sort radius** in **Settings → Location** to minimise overlap between nearby sites.
- Move the incorrectly matched photo manually — delete it from the wrong site and re-add it to the correct one.

---

## Auto-Sort isn't matching any of my photos

**Symptom:** All photos come back as **Unmatched** after running Auto-Sort.

**Cause:** Photos must have GPS coordinates embedded in them to be matched. Photos taken with location services disabled, or imported from sources that strip metadata, won't have coordinates.

**Fix:**
- On your iPhone, go to **Settings → Privacy & Security → Location Services → Camera** and set it to **While Using**.
- Take new photos with location enabled — they will contain GPS data and can be matched.
- Photos already taken without GPS cannot be auto-matched and must be added to sites manually.

---

## "Precise Location" shows Unavailable

**Symptom:** Settings shows **Precise Location: Unavailable**, and nearby sorting or arrival notifications aren't working properly.

**Fix:**
1. Go to **Settings → OnSite → Location** on your device.
2. Set location access to **Always**.
3. Make sure **Precise Location** is toggled on.

If precise location is temporarily unavailable due to system restrictions, it will recover automatically when conditions improve.

---

## How do I remove a contact from a site?

1. Open the site and tap **Edit**.
2. Find the contact in the Contacts section.
3. Tap the remove button next to their name.
4. Tap **Done**.

---

## How do I delete a photo?

1. Open the site and tap the photo to open it in full view.
2. Tap the **Delete** or trash icon.
3. Confirm the deletion.

{: .warning }
Deleted photos cannot be recovered from within OnSite. Make sure you have a copy elsewhere if needed.
