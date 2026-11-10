# Desk Scout release notes

## 1.0.2 (November 2026)

- American spelling throughout (color, organize, gray, centered and so on) in the program, the manual and the video.

## 1.0.1 (November 2026)

- **New:** Help > **Watch the video**, a 2-minute narrated tour ([watch it here](desk-scout-explainer.mp4)).
- **New:** Options > **Install updates automatically**, on by default. Each update is checked against its published SHA-256 fingerprint before it is installed, and a notice by the clock tells you when it happened.
- Your fences are saved more safely. There is never a moment without a settings file, and Desk Scout falls back to the backup copy if it needs to.
- If a fence's settings are ever lost, Desk Scout rebuilds the fence from its folder automatically, so no files are left stranded.
- Removing a fence now keeps the fence if any of its files couldn't be put back on the desktop, for example a file that is open in a program.
- Items you drag or move back onto the desktop are no longer pulled straight back into a fence by a rule.
- Folders that are still being copied onto the desktop are never moved mid-copy.
- Shortcuts that belong to all users go back to the Public Desktop when you remove their fence.
- Fences show correctly when a wallpaper slideshow or wallpaper app is running.
- Every part of the source code is now commented.

## 1.0.0 (November 2026)

First release.

- **Fences:** shaded, see-through boxes for your desktop icons. You can set each fence's:
  - name and color
  - see-through level
  - icon size
  - layout (grid or list)
  - sort order
- **Moving files:** drag files in from the desktop, Explorer or another fence, and drag them out the same way. Right-click an icon to open, rename, delete (to the Recycle Bin), cut, copy or paste it, move it to another fence, or see its Properties.
- **Roll-up:** double-click a fence's title to shrink it to just the title bar. Point at it to peek inside.
- **Lock** a fence's position and size. Fences snap neatly to screen edges and to each other.
- **Folder Portals:** show any folder on the desktop and browse into its sub-folders.
- **Rules:** new desktop files are sorted into fences automatically, by kind, file ending or name pattern. **Organize my desktop** sets everything up in one click.
- **Quick-hide:** double-click empty desktop to hide all fences and desktop icons.
- **Peek:** press Ctrl+Alt+Space to bring every fence in front of your open windows.
- **Icon looks:**
  - faded until you point at it
  - grayscale
  - tinted with the fence color

  Photos and videos can show thumbnails.
- **Snapshots** of your whole layout. Positions are remembered separately for each monitor arrangement.
- **Automatic updates:** each download is checked against its published SHA-256 fingerprint before it is installed. You can turn automatic updates off on the Options tab.
