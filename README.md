# bluez360-media

Demo panoramas for [bluez360.web.app](https://bluez360.web.app), served over
jsDelivr so Firebase Hosting does not pay the bandwidth for them.

    https://cdn.jsdelivr.net/gh/ajayajagiya/bluez360-media@v1/demos/<file>

## Why a tag and not a branch

jsDelivr caches a tagged path forever and a branch path for twelve hours. The
site pins the tag, so the images come back from the edge every time.

The cost is that a tag cannot move. **Replacing an image means a new tag** --
`v2`, `v3` -- and the `@v1` in every page that points at it has to change in
the same commit. Overwriting a file and re-pushing `v1` will not reach anyone
who has already loaded the old one.

## What belongs here

Only images the public site shows. Nothing private, nothing unreleased: this
repository is public and jsDelivr will serve anything in it to anyone.

The originals stay in the main repository under `web_app/DEMOS/masters/`.
These are the downscaled 2048 and 4096 versions.
