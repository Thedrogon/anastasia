# Anastasia Theme 🌲

[![Version](https://vsmarketplacebadge.apphb.com/version/publisher.name.anastasia)](https://marketplace.visualstudio.com/items?itemName=publisher.name.anastasia)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/publisher.name.anastasia)](https://marketplace.visualstudio.com/items?itemName=publisher.name.anastasia)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/publisher.name.anastasia)](https://marketplace.visualstudio.com/items?itemName=publisher.name.anastasia)

> **A deep, matte pine aesthetic with electric neon accents.**
>
> *Modern. Sleek. Immersion-first.*

---

## 🎨 The Philosophy

**Anastasia** was engineered to solve the "OLED Black" problem. Pure black backgrounds often cause harsh eye strain and "text ghosting" during long coding sessions.

This theme utilizes a **Deep Matte Green (`#041F1A`)** foundation—a chalkboard-like surface that absorbs light rather than reflecting it. This is paired with high-energy **Neon Spring (`#00FF9D`)** indicators and **Pale Mint** text to create a high-contrast environment that remains soft on the eyes.

It is not just a theme; it is a specialized environment for focused development.

## ✨ Features

* **Matte Surface Technology:** The background is a specific deep pine shade designed to reduce halation and eye fatigue.
* **Semantic Neon:** High-priority indicators (cursors, errors, active tabs) glow with a neon spring green (`#00FF9D`).
* **Logic Separation:**
    * **Data** (Strings/Numbers) is colored in warm Emeralds and Ambers.
    * **Logic** (Keywords/Control Flow) is colored in cool Purples and Cyans.
* **"Waterfall" UI:** The sidebar and file explorer use a seamless gradient of greens, removing harsh gray borders found in default themes.
* **Readability First:** Comments use a specialized **Sage Green** contrast ratio (3:1) to ensure they are visible but unobtrusive.

---

## 📸 Screenshots

### The Editor Experience
*A balance of deep matte backgrounds and vibrant syntax highlighting.*

![Main Editor Screenshot](./images/preview.png)
*(Note: Please ensure you have an 'images' folder in your repository with a file named 'preview.png')*

---

## 🔧 Recommended Settings

For the full **Anastasia** experience, we recommend adding these settings to your `settings.json` to enhance the visual immersion:

```json
{
  "editor.renderLineHighlight": "gutter",
  "editor.fontFamily": "'JetBrains Mono', 'Fira Code', monospace",
  "workbench.iconTheme": "material-icon-theme",
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on"
}