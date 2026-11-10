# DeskGrid release notes

## 1.2.0 (November 2026)

- **New: an installer, `DeskGrid-Setup.exe`.** It needs no administrator password, adds DeskGrid to the Start menu, starts it with Windows, and adds an uninstaller under Settings → Apps. The single-file `DeskGrid.exe` still works for anyone who prefers not to install.
- Uninstalling never deletes your files. The folder that holds your grids' files becomes a normal, visible folder on the desktop.
- Installing over a running copy closes it cleanly first and starts the new one. Your grids are kept.
- IT staff can install silently with `DeskGrid-Setup.exe /S`.
- Help → User manual and the About links now open the DeskGrid page on GitHub.

## 1.1.0 (November 2026)

- **New name: DeskGrid.** The boxes on your desktop are now called **grids**.
- If you used the earlier version, everything carries over by itself the first time 1.1.0 starts: your grids, their files, rules, snapshots and settings.
- The "Icons in a grid" layout is now called **Large icons**, so it isn't confused with grids.

## 1.0.2 (November 2026)

- American spelling throughout (color, organize, gray, centered and so on) in the program, the manual and the video.

## 1.0.1 (November 2026)

- **New:** Help > **Watch the video**, a 2-minute narrated tour ([watch it here](deskgrid-explainer.mp4)).
- **New:** Options > **Install updates automatically**, on by default. Each update is checked against its published SHA-256 fingerprint before it is installed, and a notice by the clock tells you when it happened.
- Your grids are saved more safely. There is never a moment without a settings file, and DeskGrid falls back to the backup copy if it needs to.
- If a grid's settings are ever lost, DeskGrid rebuilds the grid from its folder automatically, so no files are left stranded.
- Removing a grid now keeps the grid if any of its files couldn't be put back on the desktop, for example a file that is open in a program.
- Items you drag or move back onto the desktop are no longer pulled straight back into a grid by a rule.
- Folders that are still being copied onto the desktop are never moved mid-copy.
- Shortcuts that belong to all users go back to the Public Desktop when you remove their grid.
- Grids show correctly when a wallpaper slideshow or wallpaper app is running.
- Every part of the source code is now commented.

## 1.0.0 (November 2026)

First release.

- **Grids:** shaded, see-through boxes for your desktop icons. You can set each grid's:
  - name and color
  - see-through level
  - icon size
  - layout (large icons or list)
  - sort order
- **Moving files:** drag files in from the desktop, Explorer or another grid, and drag them out the same way. Right-click an icon to open, rename, delete (to the Recycle Bin), cut, copy or paste it, move it to another grid, or see its Properties.
- **Roll-up:** double-click a grid's title to shrink it to just the title bar. Point at it to peek inside.
- **Lock** a grid's position and size. Grids snap neatly to screen edges and to each other.
- **Folder Portals:** show any folder on the desktop and browse into its sub-folders.
- **Rules:** new desktop files are sorted into grids automatically, by kind, file ending or name pattern. **Organize my desktop** sets everything up in one click.
- **Quick-hide:** double-click empty desktop to hide all grids and desktop icons.
- **Peek:** press Ctrl+Alt+Space to bring every grid in front of your open windows.
- **Icon looks:**
  - faded until you point at it
  - grayscale
  - tinted with the grid color

  Photos and videos can show thumbnails.
- **Snapshots** of your whole layout. Positions are remembered separately for each monitor arrangement.
- **Automatic updates:** each download is checked against its published SHA-256 fingerprint before it is installed. You can turn automatic updates off on the Options tab.
