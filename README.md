# Dracula Sharp for Vivaldi

This is a fork from https://github.com/neonvoidx/vivaldi-dracula-theme

I'll be adding modifications for myself. The theme is for a **square UI**. Avoid if you love rounded corners.

### Installation

1. Download `settings.json`, ZIP it and go to `Settings > Themes > Import Theme...` (***This will install the theme only, not the CSS (next step will do that)***)
2. Download the `vivaldi-dracula.css` file and place it somewhere that you want to store this
3. To enable custom CSS:
    - Go to `vivaldi://experiments`
    - Check `Allow for using CSS modifications`
    - Go to `vivaldi://settings/appearance/`
    - Under `CUSTOM UI MODIFICATION`
      - `Select Folder...` and select the folder where you placed the `vivaldi-dracula.css` file
      - NOTE: This will load all CSS files in that directory
4. Restart Vivaldi
5. Install the Stylus extension, create new styles for "Everywhere" and paste the contents of `dracula-checkboxes-stylus.css` and `dracula-scrollbars-stylus.css` in each one (so you can toggle them separately whenever you wish).
