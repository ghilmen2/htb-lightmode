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

### 1.0.16

- Added card row container hover overrides using the full background shorthand to remove the remaining dark path row layer.

### 1.0.15

- Added direct path-progress card row overrides and restored the path-progress page background to light mode.

### 1.0.14

- Overrode the exact `hover:!bg-neutral-600` class causing dark overlays on enrolled path rows.

### 1.0.13

- Restored the path detail header to the light theme and strengthened enrolled path row hover cleanup.

### 1.0.12

- Added scoped hover cleanup for Academy enrolled path rows to avoid the dark overlay effect.

### 1.0.11

- Added scoped dashboard rank card styling for the main Academy profile card.

### 1.0.10

- Removed the light background from the Pwnbox tab/header while keeping scoped Pwnbox text contrast.

### 1.0.9

- Added scoped Pwnbox text contrast fixes using the observed Pwnbox component structure.

### 1.0.8

- Added a scoped `#questions-list` override for Academy question text based on the observed DOM structure.

### 1.0.7

- Reverted broad question-bank text overrides that leaked into normal Academy lesson content; kept terminal output cleanup.

### 1.0.6

- Strengthened text-only contrast for Academy answer/question panels without changing terminal styling or panel backgrounds.

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
