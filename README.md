# Purusfox

**A compact and minimal Firefox UI for keyboard-centric users.**

One-line layout

![Purusfox One-Line](./previews/one-line.avif)

Two-line layout on small windows

![Purusfox Bar](./previews/just-bar.avif)

Super compactible tabs

![Purusfox Bar Compact Tabs](./previews/just-bar-compact-tabs.avif)

Blends in nicely with my YouTube CSS

![Purusfox](./previews/two-line.avif)

## Installation

### Enable User Stylesheets

1. Open Firefox.
2. Type `about:config` into the address bar and press Enter.
3. Click **Accept the Risk and Continue** if prompted.
4. In the search bar, type `toolkit.legacyUserProfileCustomizations.stylesheets`.
5. Set the preference to `true` by double-clicking it.

### Open Profile Directory

1. Type `about:support` into the address bar and press Enter.
2. In the **Application Basics** section, locate **Profile Directory**.
3. Click the **Open Directory** button next to **Profile Directory**.

### Add the Custom CSS Files

1. In your profile directory, create the `chrome` directory if it doesn't exist.
2. Place the following into the `chrome` directory:

* `userChrome.css`
* `themes`

### Change the Theme

1. Open `userChrome.css` in a text editor.
2. At the top, you'll see this import: `@import url(./themes/catppuccin-frappe.css);`
3. Edit the import URL to your desired theme.

### That's it

Close and reopen Firefox for the changes to take effect.
