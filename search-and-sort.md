---
layout: default
title: Search & Sort
nav_order: 9
---

# Search & Sort
{: .no_toc }

Find sites quickly and let OnSite automatically match photos or contacts to the right location.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Searching sites

1. Open the **Sites** tab.
2. Tap the search bar at the top.
3. Type any part of the site name or address — results update as you type.

If no sites match, the list shows **No Matching Sites**.

### Searching archived sites

1. Tap the archive icon in the Sites tab toolbar to open **Archived Sites**.
2. Use the **Search archived sites…** bar at the top.

---

## How sites are ordered

The site list is ordered automatically — there is no manual sort option. The order is always:

1. **Currently on site** — sites you are physically at right now (within your auto-sort radius) float to the top, highlighted.
2. **Pinned** — pinned sites appear next.
3. **Alphabetical** — everything else is sorted A–Z by name.

{: .note }
"Currently on site" detection requires location permission. If location is unavailable, sites sort by pinned then alphabetical.

---

## Filtering by job type

If your sites have jobs assigned, a row of job type chips appears at the top of the list. Tap a chip to show only sites that contain that job type. Tap it again to clear the filter.

You can select multiple job types at once — the list will show sites that have any of the selected types.

---

## Auto-Sort (Sort tab)

The **Sort** tab is a tool that uses GPS to match photos or contacts to the right site automatically.

### Auto-sorting photos

Match photos from your library to sites based on where they were taken.

1. Open the **Sort** tab.
2. In the **Photo Auto-Sort** section, tap **Select Photos**.
3. Choose photos from your library.
4. Tap **Sort Photos into Sites**.

OnSite compares the GPS coordinates in each photo against your site addresses. Photos taken within your configured **Auto-sort radius** of a site are assigned to that site automatically.

Results show:
- **Matched** — photos successfully assigned to a site.
- **Unmatched** — photos that didn't fall within range of any site (no GPS data, or too far away).

{: .note }
Photos must have GPS metadata to be matched. Photos taken without location services enabled won't match.

### Auto-sorting contacts

Match contacts from your address book to sites based on their saved address.

1. Open the **Sort** tab.
2. In the **Contact Auto-Sort** section, tap **Select Contacts**.
3. Choose contacts from your address book.
4. Tap **Sort Contacts into Sites**.

OnSite matches contacts whose address falls within the auto-sort radius of a site.

---

## Auto-sort radius

The auto-sort radius controls how close a photo, contact, or your physical location must be to a site to count as a match. It also determines whether you appear **Currently on site** in the site list.

**To adjust the radius:**

1. Tap the **Settings** tab.
2. Scroll to the **Location** section.
3. Drag the **Auto-sort radius** slider to the value you want.
   - Range: **20 – 2,000 meters** (or feet if Units is set to Imperial).
   - The current value is shown next to the label (e.g. **100 m** or **328 ft**).

See [Settings → Auto-sort radius](settings#auto-sort-radius) for tips on choosing the right value.

---

## Sorting photos within a site

Within a site, you can control photo order:

1. Open a site and go to the Photos section.
2. Tap the Sort menu.
3. Choose from:
   - **Upload date (newest)** — most recently added first
   - **Upload date (oldest)** — oldest additions first
   - **Capture date (newest)** — most recently taken first
   - **Capture date (oldest)** — oldest capture date first
