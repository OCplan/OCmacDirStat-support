# OCmacDirStat support

OCmacDirStat is a free, native disk-usage map for macOS 15 and later. It shows the folders you choose as a size-ranked tree, file categories and an interactive map.

## Get help

[Ask a question or report a problem](https://github.com/OCplan/OCmacDirStat-support/issues/new). Include your macOS version, app version, the action you tried and what happened. Do not post private file paths, file contents, account details or credentials. Replace personal names and paths in any screenshots before sharing them.

## Scan a folder

Choose **Open Folder** and select the folder you want to inspect. **Full system scan** asks for read-only access to the startup disk. macOS may still protect some folders; those are marked incomplete rather than counted as empty. External disks can be selected separately.

Start with **Allocated Size** for the blocks reported by the filesystem. **File Size** shows logical file lengths. Cloud-only or sparse files can have a large file size while taking little local storage. Allocation is not a measurement of unique APFS physical blocks and does not promise how much deleting a file would reclaim.

The scanner reads metadata without requesting cloud-content downloads. OneDrive, SharePoint and other macOS File Provider folders follow the same system metadata rules. Cloud-only folders and inaccessible entries are marked incomplete.

## Explore the result

Click a map area to select its folder or file in the sidebar. Double-click a folder to explore it, or use the folder tree and breadcrumbs. Categories highlight file types. **Rescan** clears the old view and builds a fresh map. A cached overview shows its scan date.

## Privacy and permissions

Scans run locally. The app has no account, advertising, analytics or network-upload feature. It does not delete files. Folder access is read-only and granted through the macOS picker.

Read the [privacy policy](PRIVACY.md) and [original MIT notice](LICENSE.upstream).

## Availability

The Mac App Store release is being prepared. A Store upload is not a public release; this page does not claim the app is currently available to download.

OCmacDirStat is OCplan’s flavor of MacDirStat, originally created by Josh Auriemma. The original MIT copyright and license are included in the app. This public repository contains support material, not the private product source.
