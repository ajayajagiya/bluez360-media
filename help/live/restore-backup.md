---
id: restore-backup
title: Restore a backup
section: Sharing and backup
summary: Opening a .bz360 file, and what gets skipped
app_version: 1.9.3
---

# Restore a backup

There is no import button. You open the **.bz360** file itself.

**Moving to a new phone?** Copy your .bz360 files to it, install Bluez360, then open each file there and sign in with the same Google account.

1. Tap the file in your Files app (look in **Download/Bluez360**), or share it to Bluez360.
2. Sign in with the account that made the backup.
3. If some of its 360°s are already on this phone, you'll see **Already on this phone**. Choose **Skip all** or **Replace all**.
4. The restore runs in the background, with progress in your notifications and a **Cancel** button. Cancelling keeps what is already restored.
5. When done, you'll see "… restored" with counts like "8 added · 4 replaced". Tap **Open project**.

Everything goes back where it came from. Missing projects and areas are created; existing ones keep their name and details.

## What gets skipped

- With **Skip all**, 360°s already on the phone.
- A 360° being stitched right now.
- A locked copy never replaces a 360° you already unlocked.
- A damaged 360° shows as "couldn't be read". The rest still restore.

Locked 360°s come back locked.

## If it won't open

- "This backup can't be opened. The file may be damaged." It is damaged, or made by a different account. Backups from a deleted account never open again.
- "That file isn't a Bluez360 backup." Only .bz360 files work.
- "Connect to the internet once to set up backups."
- "Needs … This phone has … free." Free up some space.

See also: [Back up to your phone](local-backup.md) · [Delete your account](delete-account.md)
