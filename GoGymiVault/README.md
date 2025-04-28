# How to start using the vault

This guide walks you through:

* Enabling and using custom CSS snippets in Obsidian
* Installing and activating the **Hover Editor** community plugin

---

## 1. Enable CSS Snippets

1. **Create (if needed) a `snippets` folder**
   * In your vault’s `.obsidian` folder, create a subfolder named `snippets`:
     ```
     .obsidian/snippets/
     ```
2. **Add your `.css` files**
   * Place any custom CSS files you want into `.obsidian/snippets/`. For example:
     ```
     .obsidian/snippets/my-theme-overrides.css
     ```
3. **Load snippets in Obsidian**
   1. Open **Settings** (⚙️) →  **Appearance** .
   2. Scroll down to the **CSS snippets** section.
   3. You should see your `.css` files listed. Flip the toggle to **On** for each snippet you want to activate.
4. **Enjoy your custom styles!**

> **Tip:** Edit your snippet file and then click the refresh icon next to the snippet name in Settings to see changes immediately.

---

## 2. Install the Hover Editor Community Plugin

The Hover Editor plugin lets you preview and edit notes by hovering over internal links.

1. **Disable Restricted Mode** (if it's on)
   1. Go to **Settings** →  **Community plugins** .
   2. If **Restricted mode** is enabled, click the toggle to turn it off.
2. **Browse and install**
   1. In the **Community plugins** pane, click  **Browse** .
   2. In the search bar, type  **Hover Editor** .
   3. Click **Install** on the **Hover Editor** entry.
   4. After installation completes, click  **Enable** .
3. **Configure (optional)**
   * Once enabled, you can tweak Hover Editor options under **Settings** → **Plugin options** →  **Hover Editor** .
   * For example, adjust the hover delay, maximum width, or disable for certain filetypes.
   * It is recommended to set **Auto Pin** to always, as most keyboard shortcut combinations are already taken.

---

## 3. Example CSS Snippet

Here's what is already contained in

 `.obsidian/snippets/Canvas-Snippets.css`:

```css
.canvas-node-content:not(.is-loaded) {
text-align: center;
}
```

This allows all the text nodes that have not been imported from external files to be centered.
