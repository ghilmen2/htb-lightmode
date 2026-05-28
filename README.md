# HTB Light Mode

A clean light theme for Hack The Box, HTB App, and HTB Academy.

## Supported Sites

- `hackthebox.com`
- `app.hackthebox.com`
- `academy.hackthebox.com`

## Installation

1. Install the [Stylus browser extension](https://add0n.com/stylus.html) for your browser.
2. Open `htb-lightmode.user.css` in your browser or from your local filesystem.
3. Click **Install Style** in Stylus.
4. Visit Hack The Box, HTB App, or HTB Academy.

## Manual Installation

1. Open Stylus.
2. Create a new style.
3. Copy the contents of `htb-lightmode.user.css` into the editor.
4. Save the style.

## Development

The userstyle is organized into commented CSS sections:

- Design Tokens
- Base
- Layout Surfaces
- Typography
- Navigation
- Buttons and Controls
- Tables and Lists
- Badges, Alerts, and Progress
- HTB-Specific Content
- Overlays and Scrollbars

Most colors and reusable values are defined as CSS variables under `:root`, making the theme easier to tune over time.

## Changelog

### 1.0.5

- Removed inline highlight backgrounds inside terminal output and added text-only contrast fixes for dark Academy question panels.

### 1.0.4

- Removed question-bank and Pwnbox overrides so Academy interactive panels stay on HTB's default dark styling.

### 1.0.3

- Added structural Academy overrides for answer panels and Pwnbox controls that were not covered by class-name selectors.

### 1.0.2

- Improved shell/code/Pwnbox contrast with a dark terminal palette and reinforced readable question panel text.

### 1.0.1

- Added Fix pass 1 for safer hover states, readable question panels, dark terminal/Pwnbox contrast, and readable module/path hero text.
