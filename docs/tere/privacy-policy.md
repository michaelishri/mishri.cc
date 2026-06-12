# Tere — Privacy Policy

Last updated: 13 June 2026 · Effective immediately

1. Summary

Tere ("we", "the app") does not collect, store, or transmit any personal
information. There are no user accounts, no sign-in, no advertisements,
no analytics SDKs, and no third-party trackers. Everything that happens
in the app happens on your device.


2. Data stored on your device

The app keeps two kinds of data locally on the device where it is
installed:

- The Wellington public-transport timetable — the full static Metlink
  GTFS (~12 MB) is downloaded once on first launch and cached in an
  on-device SQLite database for offline use. The app re-downloads a fresh
  copy in the background when the cached copy is older than seven days or
  has expired. No information from you is sent as part of this download.

- Your saved journeys — the list of routes you add to the home screen
  (stop ids, friendly names, and which route numbers you have hidden) is
  stored as a small JSON file on the device. This data never leaves your
  device.


3. Network traffic

The only network requests the app makes are to the open, public endpoints
operated by Metlink (Greater Wellington Regional Council) under the
Metlink Open Data API (https://opendata.metlink.org.nz). These requests
are made to show you live departures, delays, vehicle locations, and
service alerts. Each request contains only the stop ids that appear in
the saved journeys you chose to view; it does not contain any device
identifier, advertising id, account information, location, or
IP-attributable user data beyond the normal request metadata your network
carries.

Metlink's Open Data API is operated under Metlink's own terms and privacy
policy, which we do not control. You can review it at metlink.org.nz.


4. Permissions

Tere requests no sensitive permissions. On Android the only permission
declared is INTERNET, which allows the app to download the timetable and
query live departures. The app does not request access to location,
contacts, photos, storage, microphone, camera, calendar, phone, or any
other permission.


5. Backups

On Android, the app opts into Google's backup service for only the
saved-journeys file, so you keep your routes after a factory reset or
migration to a new phone. The timetable database is excluded from backups
(it re-downloads itself on a fresh install).

On iOS, backups follow the system default. If you prefer that Tere data
not be backed up, turn off iCloud Backup for Tere in Settings → Apple ID
→ iCloud → Manage Account Storage → Backups → Tere.


6. Children

The app does not collect personal information from anyone, including
children under the age of 13 (or the applicable age in your jurisdiction).


7. Your choices

To remove all Tere data from a device:

- Android: Settings → Apps → Tere → Storage → Clear Data, then optionally
  uninstall.
- iOS: uninstall the app; iOS removes the app's on-device storage
  automatically.


8. Data Safety (Google Play) and App Privacy (App Store)

We declare on both stores:

- Data shared with third parties: No.
- Data collected: No.
- Encrypted in transit: All network traffic uses HTTPS (TLS). Data at
  rest is protected by the operating-system sandbox.
- Data can be deleted: Yes — by uninstalling the app or clearing app data.
- Purpose: Any data that exists on your device exists only to provide the
  service you asked for (showing departures) and is not used for
  analytics, personalisation, advertising, or any other purpose.


9. Changes to this policy

If this policy changes materially, the updated version will be posted at
the same URL and the "Last updated" date above will change. Continued use
of the app after the effective date means you accept the updated policy.


10. Contact

Questions, complaints, or data-subject requests regarding this privacy
policy are handled by the app developer directly. Please contact:

- Email: michael.ishri@gmail.com
- Postal / other: see the app's support contact listed on the store page.
