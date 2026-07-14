# ExifShield Privacy & Support

**Effective July 15, 2026 · Developer: Dev Jang**

ExifShield inspects JPEG metadata and creates privacy-clean copies locally on your Android device. The app has no account, advertising, analytics, developer backend, or Internet permission.

## Privacy summary

- No photo uploads
- Originals stay untouched
- No Internet permission
- No broad photo-library or storage permission
- No advertising, analytics, or tracking

## What ExifShield does

ExifShield lets you choose up to 12 JPEG files, view metadata such as GPS coordinates, capture time, device make and model, software, camera settings, and creator fields, then create cleaned copies in `Pictures/ExifShield`.

The original files are not edited. ExifShield removes privacy-bearing EXIF, XMP, IPTC, and JPEG comment containers from each copy without decoding or recompressing the compressed image scan. A minimal orientation value may be retained so the cleaned photo displays correctly.

Version 1 supports JPEG files only, up to 60 MB each. It does not claim to clean PNG, HEIC, RAW, video, or another format.

## Personal information collected by us: none

Dev Jang does not receive, store, sell, or share your photos, metadata, file names, app activity, device identifiers, location, contact information, or diagnostics through ExifShield.

The app has no developer-operated server, user account, advertising service, analytics service, crash-reporting service, or cloud synchronization. The Android release does not request the Internet permission. Photo inspection and cleanup happen on the device.

### Metadata shown in the app

A selected photo may already contain personal information, including precise GPS coordinates, capture time, device details, or creator information. ExifShield reads these fields only to show them to you and verify the cleaned copy. They are not transmitted to the developer.

### Temporary processing

ExifShield decodes a small preview for the inspection card and reads the selected JPEG while creating a clean copy. Temporary data is held by the app process as needed and is not retained on a developer server.

### Third-party services

ExifShield v1 does not integrate ads, analytics, social login, payments, or another third-party data service. Distribution and updates through Google Play are governed by Google Play's own terms and privacy practices.

## Your files and choices

- **Selection:** Android's system document picker grants access only to the JPEG files you select.
- **Originals:** selected source files are opened for reading and are not modified or deleted.
- **Clean copies:** outputs are saved in `Pictures/ExifShield` until you move or delete them.
- **Sharing:** Android's chooser opens only after you tap Share. You decide the destination, whose privacy policy then applies.
- **Uninstall:** removing ExifShield does not automatically delete clean copies already saved in Pictures.

### Permissions

ExifShield does not request broad photo-library, storage, location, camera, microphone, contacts, nearby-device, notification, or advertising permission. Android may add a package-scoped internal receiver permission used by the Flutter framework; it does not grant access to another app's data.

### Security, retention, and children

There is no developer-server retention period because ExifShield does not transmit files or metadata to a developer server. ExifShield is a general-audience utility and does not knowingly collect personal information from children or adults.

## Support

### Where are cleaned copies saved?

Open your gallery or file manager and look in `Pictures/ExifShield`. Output names include `_private_` and a timestamp.

### Why is a photo shown as already clean?

Some JPEGs contain no sensitive fields that ExifShield recognizes. You may still create a copy.

### Why does the app keep orientation?

When needed, ExifShield keeps only the minimal orientation tag so a rotated photo displays correctly. Location, device, capture time, creator, XMP, IPTC, and comment data are still removed.

### Contact

Email [jjw33063@gmail.com](mailto:jjw33063@gmail.com) with “ExifShield Support” or “ExifShield Privacy” in the subject. Include only what is needed; do not attach a private photo unless necessary and intentional.

## Policy updates

If ExifShield's data practices or features change, this page will show a new effective date before the corresponding release when required.
