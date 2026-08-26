# SafeSweep safety information

## Cleanup rules

SafeSweep only cleans categories and locations that are explicitly supported by the application. A scan does not delete anything. Cleanup begins after the user selects categories and confirms the action.

Personal folders are not automatic cleanup targets. The large-file page is a review tool, not an automatic deletion feature. The old-application page does not uninstall software by itself.

Files that are changed after a scan are rechecked before cleanup. Locked or inaccessible files can be skipped and recorded in the local log.

## System changes and restoration

The optional PC optimization feature saves the previous supported Windows settings before making changes. The restore information is protected for the current Windows user. SafeSweep keeps the restore option available even when a Premium subscription has expired.

## Updates

SafeSweep checks signed release information and verifies the SHA-256 hash and the contents of an update package before applying it. The updater only replaces SafeSweep files in the existing installation folder and rolls back completed replacements if the update fails.

## Licensing

Premium licensing is validated through Keygen. SafeSweep does not contain a management token, private signing key, or key-generation secret. Administrative credentials used by the owner are not included in public builds.

## Local data

Settings, logs, update staging data, and optimization restore information are stored under the current Windows user's local application-data folder. SafeSweep does not need access to personal documents to perform its normal cleanup scan.

## Installer signature

The current installer is not yet Authenticode-signed. This can cause an unknown-publisher or SmartScreen warning even when the file has not been classified as malware. Download only from the official SafeSweep website or this repository, compare the SHA-256 checksum, and keep Windows Security enabled.

## Reporting a problem

If SafeSweep identifies something it should not clean, stop before confirming cleanup and open a GitHub issue. Include the SafeSweep version, Windows version, category, path with personal names removed, and relevant log lines.

Never post activation keys, management tokens, private account information, or complete unredacted logs in a public issue.

