# CH03 DEMO for Mac

A little retro TV casino that sits on your desktop. Fictional coins only: no real money, ever.

## 1. Download

- [CH03-DEMO-0.9.2-mac.dmg](https://github.com/ibarrett50cal/ch03-demo/releases/download/v0.9.2/CH03-DEMO-0.9.2-mac.dmg) (about 230 MB)

One app for Apple Silicon (M1 and later) and Intel Macs.

## 2. Install

1. Double-click **CH03-DEMO-0.9.2-mac.dmg** in your Downloads.
2. A window opens. Drag **CH03 DEMO** onto the **Applications** folder in it.
3. Open your **Applications** folder and double-click **CH03 DEMO**.

## 3. The first time, your Mac will block it. This is normal.

The game isn't registered with Apple yet, so the first time you open it, your Mac shows a warning that it can't open
it or can't check it. **Nothing is wrong with the game.** You only have to allow it once:

1. On the warning, click **Done** (or **OK**). **Don't** click "Move to Trash".
2. Click the **Apple menu** (top left) → **System Settings**.
3. Click **Privacy & Security** in the list on the left.
4. Scroll **all the way down** on the right, to the **Security** section. You'll see a line about **CH03 DEMO** being
   blocked, with a button: click **Open Anyway**.
5. Type your Mac's password (or use Touch ID) and click **OK**.
6. If a warning shows one more time, click **Open Anyway** (or **Open**).

That's it: from now on it opens like any other app.

**Don't see Open Anyway?** The button only shows for about an hour after you try to open the game. Double-click
**CH03 DEMO** in Applications again, click **Done**, and go straight back to step 2.

**On macOS 14 (Sonoma) or older** there's a quicker way: in Applications, **right-click** (or Control-click)
**CH03 DEMO** → **Open** → **Open**. *(Not sure which macOS you have? Apple menu → About This Mac.)*

**If the Mac says the app "is damaged and can't be opened":** it isn't. Open **Terminal** (Applications → Utilities →
Terminal), paste this line, press Return, then open the game again:

```
xattr -dr com.apple.quarantine "/Applications/CH03 DEMO.app"
```

## 4. Playing

- Click the screen to start. Drag the handle on top to move the TV; drag its top-left corner to resize it.
- The little TV in the **menu bar** (top right of the screen) has Show / Hide and Quit, and **Cmd+Q** quits.
- The book on the stack is the instruction manual.

**Keep it in your Dock:** click the little TV in the menu bar → **Show in Dock**. CH03 DEMO's icon appears in the Dock.
Then **right-click** that icon → **Options** → **Keep in Dock**, and it stays there, ready to click, even when the game
is closed. (Show in Dock again takes the icon away while it's running.)

**Your progress comes with you:** when you get the full game on the same Mac, it offers to carry your demo save over.

**Remove it:** drag **CH03 DEMO** from Applications to the Trash.
