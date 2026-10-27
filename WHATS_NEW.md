# What's new in LGA FileManager S3

## v1.000 (2026-10-27)

- **Improved:** Download first, middle & last frames también aparece con Compare activo, y cada frame baja a su carpeta del shot sin tener que entrar a ella.
- **Improved:** el botón Download del Media Manager de Nuke pregunta si saltear o pisar los archivos que ya tenés en disco, en vez de pisarlos.
- **Improved:** el tab ACTIVITY ahora se llama QUEUE: es el mismo de siempre, con las subidas y descargas a Wasabi.
- **Fixed:** Con Compare activo, mover, renombrar, cortar y pegar o copiar en el panel de Wasabi ya muestra el resultado al terminar, y Refresh ya no vuelve a mostrar las carpetas como estaban antes.
- **Fixed:** Mover o renombrar una carpeta en Wasabi ya no aparece como fallido en QUEUE cuando en realidad se movió completa.
- **Fixed:** El texto de Download first, middle & last frames en el click derecho ya no se ve cortado como «middle _last».
- **Fixed:** Download clip de Nuke Studio ya no vuelve a bajar los clips que ya tenés en disco: los saltea sin preguntar, y ya no falla con los que están abiertos en Nuke Studio.

## v0.919 (2026-10-18)

- **New:** Nuke Studio can upload the project you just saved straight to Wasabi, asking first only if that file is already there.
- **New:** Ctrl+Alt+click a folder (Cmd+Option+click on Mac), or right-click it and choose Expand all subfolders, to open it together with all its subfolders.
- **New:** In the Wasabi panel you can copy files and folders and paste them into another Wasabi folder without downloading them: right-click Copy (Ctrl+C), then Paste in each destination. Files that already exist there are never overwritten.
- **Improved:** Renaming or moving many individual files in Wasabi, like the frames of a sequence, is now many times faster.
- **Fixed:** Quitting no longer leaves the app frozen when a Wasabi listing is still arriving.
- **Fixed:** Opening the app no longer sometimes shows "The listing failed" on the Wasabi tabs. (Windows only)
- **Fixed:** Renaming individual files in Wasabi no longer waits up to fifteen minutes on a stalled connection before continuing with the remaining files.
- **Fixed:** A Wasabi move or rename that can't be done, for example because the destination already has an item with that name, now shows as failed in Activity instead of done.
- **Fixed:** Cutting items in Wasabi, opening another folder and pasting now moves the items you cut, not other items with the same name.

## v0.918

- **New:** Task information distinguishes the responsible artists from Viewers who retain access. Role changes refresh task information even when the assigned names stay the same.
- **New:** Tabs take the color of their project, toned down to fit the tab bar, and favorites without a color of their own show it too. (Studio only)
- **New:** Right-click a tab to jump to any active project straight from the menu, without saving it as a favorite first. (Studio only)
- **New:** Right-click a tab and choose Reset tab color to remove a color you set by hand.
- **Improved:** The installer is much smaller (about 51 MB instead of 188 MB), so updates download faster, and FileManager S3 takes about 700 MB less disk space. (Windows only)
- **Improved:** Renaming or moving a folder in the Wasabi panel retries by itself when the connection drops halfway, instead of leaving part of the files behind.
- **Fixed:** Downloads started from the command line appear in Activity immediately and finish correctly there even if a transfer notification is missed.

## v0.917

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
