# What's new in LGA FileManager S3

## v0.917 (2026-10-04)

- **New:** Right-click a sequence in the Wasabi panel and choose Download first, middle & last frames to check it without downloading the whole thing.
- **New:** An arrow between the two path bars opens the Local folder on the Wasabi side; hold Shift and it flips to open the Wasabi folder on the Local side.
- **New:** The update window now shows what's new before you install, the app shows it once after an update you didn't see, and Help has a What's New button with the full history.
- **Improved:** The app now checks for updates every few hours while it stays open, not only at startup. Remind me later waits one day instead of a week, and closing the update window won't ask again until you restart the app.
- **Improved:** The right-click menu now has Upload on the Local panel and Download on the Wasabi panel.
- **Improved:** Shot and task folders and the shot info card now show the Review Netflix and SL Approved statuses with their own label and color. (Client only)
- **Improved:** Calculate size shows the name of the folder it is measuring, lists the loose files and sequences in your selection, and stacks several results instead of piling them on top of each other.
- **Improved:** A failed auto-update now leaves an update log, and the error message tells you where to find it.
- **Improved:** In the update window, Update now is highlighted as the main action instead of looking disabled.

## v0.916

- **Improved:** The "Transfer services unavailable" notice is now a single window with an expandable Details, and a repeating error shows a counter instead of stacking windows.
- **Improved:** Error messages no longer send you to support or to the log files: they point to Details instead.
- **Improved:** The download overwrite warning now shows only the number of files (or the file name), and folders that simply merge no longer trigger it.
- **Improved:** The title of the selected tab is now pure white when the tab has a background color.
- **Fixed:** If the transfer services stop while the app is open, they now restart on their own instead of leaving uploads and downloads dead until you restart the app.
- **Fixed:** Permanent delete and Paste's Replace no longer follow junctions and delete the files on the other side. (Windows only)
- **Fixed:** Downloaded update installers are now deleted after use instead of piling up on disk.
- **Fixed:** Uninstalling now removes the leftover cache, logs and the app folder itself. (Windows only)
