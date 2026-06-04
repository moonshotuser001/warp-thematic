# warp-thematic

![status](https://img.shields.io/badge/status-active-success)
![themes](https://img.shields.io/badge/themes-12-blue)
![svg](https://img.shields.io/badge/assets-svg%20gallery-orange)


---

## Overview

A curated collection of Warp themes organized by geography. 

---

## Gallery

### Europe
<details>
<summary>Expand</summary>

<img src="assets/images/central_european_warp_themes.svg" width="48%" />
<img src="assets/images/nordic_warp_themes.svg" width="48%" />
<img src="assets/images/mediterranean_warp_themes.svg" width="48%" />

</details>

### Americas
<details>
<summary>Expand</summary>

<img src="assets/images/north_america_us_themes.svg" width="48%" />
<img src="assets/images/latin_america_themes.svg" width="48%" />
<img src="assets/images/canada_mexico_themes.svg" width="48%" />

</details>

### Swiss / Extended Systems
<details>
<summary>Expand</summary>

<img src="assets/images/warp_swiss_theme_previews.svg" width="48%" />
<img src="assets/images/warp_swiss_extended_previews.svg" width="48%" />

</details>


## Installation

### Method 1 — Clone Repository

bash git clone https://github.com/moonshotuser001/warp-thematic.git cd warp-thematic 

Create the Warp themes directory if it does not already exist:

bash mkdir -p ~/.warp/themes 

Copy all theme files:

bash find themes -name "*.yaml" -exec cp {} ~/.warp/themes/ \; 

Restart Warp, then navigate to:

Settings → Appearance → Theme

Select any installed theme from the list.

---

### Method 2 — Manual Installation

1. Download the desired .yaml theme file.
2. Place it in:

text ~/.warp/themes/ 

3. Restart Warp.
4. Open Settings → Appearance → Theme.
5. Select the installed theme.

---

### Verify Installation

List installed custom themes:

bash ls ~/.warp/themes 

If installation was successful, the selected theme will appear in Warp's theme picker.

---

### Included Collections

- Central European Themes
- Nordic Themes
- Mediterranean Themes
- North American Themes
- Latin American Themes
- Canada & Mexico Themes
- Swiss Themes
- Swiss Extended Themes

All themes are provided as standard Warp-compatible YAML theme files.
---

## Structure
