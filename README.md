# Firefox CSS

My extremely basic CSS modifications for Firefox.

### What does it change?

- No logo and wordmark on the new tab page.
- No settings button on the new tab page.
- Replaces the menu button for the settings button in the toolbar.

## Preview

![Preview](https://st0rm.is-fi.re/4jxdswo.png)

## Installation

### Initial Setup

Be sure you have the Settings toolbar button at the very right. You can put it there by right-clicking your toolbar, and going into `Customize Toolbar...`, and finally dragging Settings to the toolbar and to the right.

### Installing the CSS

1. Navigate to [about:config](about:config) and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
2. Navigate to [about:profiles](about:profiles) and locate your current profile.
3. Open the root directory by pressing `Open Folder` on the `Root Directory` section.
4. Inside your profile directory, go into or create the `chrome` directory.
5. Paste `userChrome.css` and `userContent.css` into there.
