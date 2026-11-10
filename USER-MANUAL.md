# Desk Scout — User Manual

*Version 1.0.2 · Dialsoft LLC · Windows 10 and 11*

Desk Scout tidies your Windows desktop into shaded, labeled boxes called **fences**. Each fence holds the icons you put in it and can be named, colored, made more or less see-through, rolled up out of the way, locked in place, or hidden with a double-click. A **Folder Portal** is a fence that shows a folder you already have, like Documents or a network share.

---

## 1. Getting started

1. Put `DeskScout.exe` somewhere permanent, such as your **Documents** folder, and double-click it. There is nothing to install.
2. The Desk Scout window opens on **Start here**. Click **Organize my desktop for me** for a one-click tidy-up, or **Make one empty fence** to start by hand.
3. Desk Scout now lives in the **notification area** (by the clock). Closing its window keeps it running. Double-click the icon there to open the window again.

Desk Scout starts with Windows by default. Fences only show while it is running, so leave that on (**Options → Start Desk Scout when I sign in**).

## 2. Using fences

| To… | Do this |
|---|---|
| Put something in a fence | Drag it from the desktop or any Explorer window and drop it on the fence. If you drop it on a folder icon inside the fence, it goes into that folder. |
| Take something out | Drag it onto the desktop, into another fence, or into a folder. |
| Copy instead of move | Hold **Ctrl** while you drop. |
| Open an item | Double-click it, or select it and press **Enter**. |
| Move a fence | Drag its title bar. |
| Resize a fence | Drag any edge or corner. Fences snap to screen edges and to each other. |
| Roll up / unroll | Double-click the title bar. A rolled-up fence opens while you point at it. |
| Lock a fence | Right-click the title → **Lock position and size**. A padlock shows in its title. |
| Change anything else | Right-click the title, or an empty spot inside the fence. |

**Keyboard** (click a fence first): **Delete** sends to the Recycle Bin, **F2** renames, **Ctrl+A** selects all, **Ctrl+C / Ctrl+X / Ctrl+V** copy, cut and paste, **F5** refreshes, and **Backspace** goes back in a portal.

**Right-click an icon** to open it, choose **Open with**, **Open file location**, cut, copy, rename or delete it, **Move to** the desktop or another fence, or open **Properties**.

### How a fence looks

These are all on the fence's right-click menu and on the **Fence settings** tab:

- **Color.** Thirteen ready-made colors, or any color you like.
- **See-through.** Choose anything from *invisible* (icons only) to *solid*. Icons and names stay sharp either way.
- **Icon size.** Small, Medium, Large or Extra large. You can also choose a **grid** or a **list** (one item per line, which fits many more).
- **Sort by.** Name, type, date changed or size, with an option to reverse the order. Folders always come first.
- **Icon look.**
  - *Normal*
  - *Faded until I point at it*: the fence melts into the wallpaper until the mouse is over it.
  - *Grayscale*
  - *Tinted with the fence color*
- **Thumbnails.** Photos and videos show a small preview instead of a plain icon.
- **Title position.** Centered or on the left.

## 3. Folder Portals

Click **Folder portal** on the ribbon (or right-click a fence → **New Folder Portal**) and pick any folder. The portal shows that folder live, and nothing gets moved into it. Double-click a sub-folder to browse into it; the **←** arrow in the title takes you back. To show a different folder, right-click the title → **Change folder…**.

## 4. Rules: automatic sorting

A rule says "files like this go into that fence". Rules are checked from the top of the list down, and the first one that matches wins. Open the **Rules** tab and click **Add rule…**. A rule can match on one of three things:

- **Kind:** Programs & shortcuts, Folders, Documents, Pictures, Videos, Music, Archives, Installers or Other.
- **File ending:** for example `.png; .jpg`.
- **Name pattern:** for example `Screenshot*`. Here `*` means "anything" and `?` means "any one character".

When **Automatic sorting** is on, a new file that lands on the desktop is moved into its fence about 3 seconds after it arrives. Desk Scout waits until downloads and copies have finished first. **Sort desktop now** applies the rules to everything that is already on the desktop.

**Organize my desktop** sets all of this up in one go. It shows you its plan first, then makes a fence for each kind of thing on your desktop, moves the items in, and adds the rules. Some shortcuts belong to every user of the PC (they live in the Public Desktop folder). Moving those needs administrator permission, so Windows asks you once.

## 5. Quick-hide and Peek

- **Quick-hide.** Double-click any empty spot on the desktop. Every fence disappears, and so do the desktop icons unless you turn that off in Options. Double-click again to bring them back. You can also use **Hide all** on the ribbon or in the tray menu.
- **Peek.** Press **Ctrl+Alt+Space**. The screen dims and every fence comes forward in front of your open windows. Press the keys again, press **Esc**, or click the dark area to go back. You can change the key under **Options → Peek hot key**.

## 6. Snapshots and multiple monitors

**Take snapshot** saves where every fence is, how it looks, and your rules. **Restore snapshot** puts it all back. Your files are not moved by a restore.

Desk Scout also remembers fence positions **separately for each screen arrangement**. Docking or undocking a laptop, or changing resolution, therefore puts each fence back where it was for that setup.

## 7. Where your files are, and safety

- A fence's files live in **Desktop\Desk Scout Fences\\<fence name>**. That folder is hidden so it doesn't clutter the desktop, but it is a normal folder inside your Desktop, so OneDrive and backups still include it. **File → Open the fences folder** shows it.
- Desk Scout **never deletes** anything on its own.
  - The **Delete** command sends items to the Recycle Bin.
  - **Remove fence** puts the fence's files back on the desktop.
  - **File → Put everything back on the desktop** empties every fence at once. Use it before you stop using Desk Scout.
- When Desk Scout is closed, fenced files are not on the desktop. They are still safe in the folder above.
- Settings are kept in `%AppData%\Dialsoft\Desk Scout\`: `fences.txt`, `settings.txt` and the `Snapshots` folder.

## 8. Updates

Desk Scout keeps itself up to date. It checks when it starts and every 6 hours after that. When a new version is out, it waits until you aren't busy, downloads it, and checks it against its published SHA-256 fingerprint. A damaged or tampered download is never installed. It then swaps itself in and restarts in a few seconds, without touching your fences or files. A notice by the clock tells you it happened, and **Help → What's new** lists the changes.

To decide for yourself, turn off **Options → Install updates automatically**. You then get a notice and a green "Update available" link in the status bar instead, and nothing installs until you click it or **Help → Check for updates**.

**Help → Watch the video** plays a 2-minute narrated tour of Desk Scout.

---

© 2026 Dialsoft LLC, Wharton, New Jersey. Created by Marc Frega. Built with Claude by Anthropic.
