# LGA FileManager S3

A two-sided file browser for teams that keep their projects on S3. Your local
disk on one side, your Wasabi bucket on the other, side by side in the same
window.

Instead of a web console in one tab and a file explorer in another, you see both
at once and move files between them the way you already move files.

**Windows and macOS.** Portable: nothing to install, and it updates itself.

---

## What it does

**Browse both sides at the same time.** Every tab is a Local/Wasabi pair. `Ctrl+T`
opens another one, so you can work on several shots without losing your place.

**Compare.** When both sides are standing on a folder with the same name, Compare
tells you what is on one side and not on the other. Turn it off and each side
navigates on its own again.

**Move files.** Upload, download and delete, with a transfer queue that keeps
going while you keep working. The Activity tab shows what is running, what
finished and what failed.

**Open a path straight from the command line**, which is how it plugs into Hiero
and Nuke Studio:

```bash
FileManagerS3.exe --path "T:\VFX-MOR\102\MOR_2012_010"
```

That opens a tab on that folder and works out its Wasabi counterpart on its own.
If one of the two sides does not exist yet, it offers to create it; if you say
no, each side opens as deep as it can and Compare stays off.

There are also `--download`, `--download-latest`, `--upload` and
`--notify-completion` for scripting.

---

## What you need

Your own **Wasabi S3** credentials and a bucket. The application stores them
encrypted on your machine.

Comparing works on any pair of folders, VFX-related or not: it only needs both
sides to be standing on a folder with the same name.

---

## Downloads

The [releases](../../releases) of this repository, for Windows and macOS. The
application checks them on its own and offers to update.

## About this repository

This one is public so that the downloads and the auto-updater work. The source
code lives in a private repository.
