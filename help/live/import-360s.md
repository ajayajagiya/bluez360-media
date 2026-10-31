---
id: import-360s
title: Import 360s from your phone
section: Projects and areas
summary: Bringing 360s from another camera or app into an area, and why one is skipped
app_version: 2.8.2
---

# Import 360s from your phone

Have 360 photos from another camera or app, like a Ricoh Theta, Insta360 or GoPro? Bring them into an area and use them like your own, in Tour Builder too.

1. On a project, long-press an area and tap **Import 360°s**.
2. Android may ask **Allow Bluez360 to access photos and videos on this device?** Say **Allow** so each 360 keeps where it was taken. See [Where it was taken](#where-it-was-taken).
3. Android's Files picker opens. Pick one or several photos.
4. Bluez360 checks each one and adds it to the area. **Cancel** stops it: the photo it's on isn't added, and the ones already in stay in.

When it's done, the status line says how many were added. If any were skipped, a list shows each one with the reason. Tap **OK** to close it.

Your photos on the phone are never changed or removed. Importing is free.

## Why one is skipped

Google Maps only takes full 360s, so each photo is checked first:

- **Not a JPEG** – Google takes JPEG only.
- **Too big** – over 75 MB.
- **Not a 360°** – it isn't exactly twice as wide as it's tall, or it's a cylindrical panorama.
- **Too small** – it needs to be at least 3840×1920.
- **Not a full 360°** – it's only part of a sphere.
- **Saved turned or flipped** – save it upright from the camera's app first.
- **A camera's raw file** – two round fisheye pictures side by side. Export it as a 360 from the camera's app first.
- **Already in** – the same 360 is already in one of your areas. The message says which.
- **Couldn't be opened** – for example a cloud file while you're offline.
- **Not enough space on the phone**, or **the file is damaged**.

## Where it was taken

A 360 that has GPS in it arrives already placed in Tour Builder. One without GPS, or imported after you said **Don't allow**, arrives unplaced: place it yourself in Tour Builder's **Place** tab. If you said no twice, Android won't ask again: turn it on for Bluez360 in your phone's settings.

## What you get

- Each one is a new, stitched 360 in the area, named after its file. It's never locked.
- Its date is the one the camera saved, or the file's date.
- One wider than 8192 is made 8192×4096, the size of Bluez360's 4K stitches.
- It can't be stitched again, because there are no original shots.
- In Tour Builder it's like any other 360: you can blur it, and publishing it costs tokens as usual. Once published, it's listed in Bluez360's Explore.
- A project with no location gets one from the 360s that have GPS.

See also: [How your 360s are organised](projects-and-areas.md) · [Tour Builder](tour-builder.md) · [Add 360s from Google Maps](tour-import.md)
