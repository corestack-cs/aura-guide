# Guide Images

Place screenshots here using these exact filenames so the guide
HTML picks them up automatically (the `<img src="...">` tags in
`docs/guide.html` reference these paths).

## Screenshots to take

Capture all on **Windows** with **stealth OFF** so the windows
show normally. PNG preferred (sharp text), 16:9 or 4:3 aspect.
1200–1600 px wide is plenty — the guide caps display width at
~880 px.

| File                            | What to capture                                                                                          |
|---------------------------------|----------------------------------------------------------------------------------------------------------|
| `01-license-dialog.png`         | The License activation dialog on first launch. Show both Step 1 (Device Key) and Step 2 (License Key).   |
| `02-main-window.png`            | Aura's main window — titlebar + caption pane + action bar + AI tab (ChatGPT signed in is ideal).         |
| `04-manage-modes.png`           | Manage Modes dialog with at least 2 resumes uploaded, one marked Active. Sidebar shows multiple modes.   |
| `14-hotkeys-settings.png`       | Settings dialog scrolled to the HOTKEYS section — every row visible with their Alt+letter bindings.       |
| `15-tray-menu.png`              | Right-click tray menu expanded with the Profile sub-menu hovered and at least one mode showing resumes. |

## Optional extras

These will land in future versions of the guide:

| File                                  | What to capture                                            |
|---------------------------------------|------------------------------------------------------------|
| `09-snap-selection.png`               | The Snap selection overlay mid-drag (a rectangle visible).  |
| `10-project-panel.png`                | Project panel with a folder loaded — file tree + editor.    |
| `13-opacity-slider.png`               | Titlebar zoomed in on the opacity slider + color swatch.    |

## Tips

- **Light background behind Aura**: the dark-on-dark window is hard
  to see; open a white-ish page underneath (Bing, blank Notepad)
  so Aura's chrome reads clearly in the screenshot.
- **Hide your real fingerprint / license key** before publishing.
  Either blur them in the screenshot or use a test PC.
- **2x DPI**: take screenshots on a 4K monitor at 100 % scale, or
  use the Windows + Shift + S snip in high-DPI mode for crisp text.

## Diagrams already inline

Two illustrations are baked into `guide.html` as inline SVG and
need no separate file:

- **Pin cursor concept** (section 12) — viewer vs. local view.
- **Stealth before / after** (section 11) — what you see vs. what
  the interviewer sees.

If you want to tweak them, search for `<svg viewBox=` in
`guide.html`.
