# OtterWiki "Mint & Charcoal" Theme

A custom CSS theme for [OtterWiki](https://otterwiki.com/) featuring a polished "Mint & Charcoal" dark mode. 

## Features
* **Color Palette:** Soft charcoal backgrounds (`#1a1d23`) with vibrant orange accents (`#ff9a56`).
* **Typography:** Optimized spacing and font sizes using Inter and Fira Code.
* **Enhanced UI:**
    * Custom-styled callout boxes (Notes, Tips, Warnings) with glass-morphism tints.
    * Cleaned up tables and code blocks.
    * **Fixed Editor:** Solves CodeMirror conflicts to ensure the editing interface remains clean and usable without visual glitches.

## Installation

1.  Locate your OtterWiki `app-data` volume or directory.
2.  Navigate to the `custom/` folder (e.g., `app-data/custom/`).
3.  Place the `custom.css` file into this directory.
4.  Restart the OtterWiki container (if changes don't appear immediately, though they usually just require a page refresh).

## Customization

You can adjust the primary accent colors at the top of the `custom.css` file under `:root`:

```css
:root {
    --primary: #ff9a56; 
    --primary-light: #ffb077;
    --primary-dark: #ff8338;
}
