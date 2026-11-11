# icloud-gcal-sync

A personal, single-user tool that copies events from a chosen set of iCloud calendars into one Google Calendar, so a household's schedules can be seen in one place.

It runs only on its owner's own Mac. There is no server, no website and no account system. This page exists because Google's OAuth consent screen asks for a homepage link.

- Reads: calendars the owner selects in iCloud, using an Apple app-specific password stored in the owner's macOS Keychain.
- Writes: one Google Calendar that the tool itself created, using the `calendar.app.created` scope.
- Does not read the owner's other Google calendars, email, contacts or files.

See [PRIVACY.md](PRIVACY.md) for how data is handled.

Contact: mtakacs@gmail.com
