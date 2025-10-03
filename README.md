# Firefox Chrome-Style Tabs (userChrome.css)

Make Firefox's tab bar feel closer to Chrome:
- Tabs **shrink** as more are opened (no horizontal scrolling).
- **Firefox View** button removed.
- Divider line before the first tab removed.
- Cleaned borders/shadows.
- **Close (×) button appears on hover** for any tab.

> This is a small `userChrome.css` you can drop into your profile. Built and tested on:
> - MacOS 14.6.1
> - Firefox Version 143.0.3
> - Build ID 20250929153833

---
## Demo
### Before
![Before GIF](./Before.gif)

### After
![After GIF](./After.gif)
---

## Install Guide

1. **Enable userChrome support**
   - Visit `about:config`
   - Search for: `toolkit.legacyUserProfileCustomizations.stylesheets`
   - Set it to **true**

2. **Open your profile folder**
   - Go to `about:profiles`
   - In your active profile row, click **Open Folder** / **Show in Finder** / 

3. **Create the `chrome` folder (if it doesn’t exist)**

   Your profile should look like this:

   ```
   <your-profile>/
   └── chrome/
       └── userChrome.css
   ```

4. **Add the CSS**
   - Put `userChrome.css` from this respository into the `chrome/` folder.
   - Paste the CSS from the **CSS** section below.
   - Save and **restart Firefox**.

That’s it.
