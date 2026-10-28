# GitHub delivery folder

The user requested on 27 October 2026 that `release-assets/` contain only the three app downloads:

- `Scriptorium Setup.exe`
- `Scriptorium Mac.zip`
- `Scriptorium Linux.tar.gz`

Do not copy audit reports, JSON metadata, readmes, release notes, checksums, source/import archives, private archives or backups into `release-assets/`. Keep those in the master project's `commentary_sources/` or `Preserved history/` (the former `Delivery/` folder has been retired) outside this GitHub upload tree. Do not add documentation inside `release-assets/` itself.

Preserve the current app package formats unless the user asks to convert them. Updating this local folder does not authorize remote publication.

Each app download must be strictly smaller than 2,000,000,000 bytes. Keep temporary build files in the master project build folder.
