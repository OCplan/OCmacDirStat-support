# OCmacDirStat privacy policy

Effective date: 9 October 2026. Applies to the OCmacDirStat 0.1.7 candidate. The App Store release remains pending.

## Data stays on your Mac

OCmacDirStat does not collect or transmit your file names, file paths, file contents, scan results, identifiers or usage analytics to OCplan. It has no advertising SDK, tracking SDK, account system or network-upload feature.

The app reads filesystem metadata for folders you select, including names, sizes, types and modification dates. It uses this information locally to display the folder tree, categories and storage map. It does not open file contents to perform a scan and avoids requesting downloads of cloud-only content.

## Local storage and access

A dated scan overview may be cached on your Mac to show the last result while a new scan starts. The app may save a macOS security-scoped bookmark for the folder or startup disk you authorise. These are local app data. Cached results are not uploaded. Scans use read-only bookmarks. Version 0.1.7 adds native Quick Look and Open
actions that read file contents only when you choose them. Previewing or opening
a cloud-only file asks before its contents can be downloaded.

The Store sandbox permits read/write access to folders selected through the macOS
picker. Move to Trash is an explicit, confirmed action and requests the containing
folder. The app does not save writable bookmarks or automatically delete files.
There is no permanent-delete fallback. Local items can be restored using Finder’s
Trash → Put Back. Trashing an item in a synced folder may also sync deletion to
the cloud and other devices; it is not local-copy eviction.

To remove local cached scans or saved folder permissions, remove the app’s local data through macOS or contact support for guidance. Removing app data does not remove your scanned files.

## Apple and cloud providers

Apple manages App Store downloads and may process purchase, installation or diagnostic information under its own privacy settings and policies. Your cloud provider remains responsible for its own sync and storage service. OCmacDirStat does not add an account connection to those providers.

## Support

Support is available through [OCmacDirStat support](https://github.com/OCplan/OCmacDirStat-support/issues). If you choose to post an issue, GitHub processes your account and issue content under its own policies, and public issues are visible to others. Only include information you want to share publicly. Do not include private paths, files, credentials or personal information. Support submissions are separate from the app’s local scans.

## Changes

We will update this policy if the app’s data practices change. Any future advertising or paid feature would require a new review of the app’s disclosures; neither is present in this version.
