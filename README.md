# HTB Light Mode

A light theme for Hack The Box, the HTB app, and HTB Academy.

This is a Stylus userstyle, so it runs entirely in your browser. It does not change your HTB account, progress, labs, machines, or Academy content.

## Supported Sites

- `hackthebox.com`
- `app.hackthebox.com`
- `academy.hackthebox.com`

## Install

1. Install [Stylus](https://add0n.com/stylus.html).
2. Open [`htb-lightmode.user.css`](./htb-lightmode.user.css).
3. Choose **Install Style** when Stylus opens.
4. Refresh any open HTB tabs.

If the install prompt does not open, create a new style in Stylus and paste in the contents of `htb-lightmode.user.css`.

## Notes

- The theme focuses on making the main HTB surfaces light while keeping terminal-like areas readable.
- Some HTB Academy panels are intentionally left dark when the original component works better that way.
- HTB changes its markup from time to time, so a page may need a small selector fix after a site update.

## Changelog

### 1.0.16

- Cleaned up the last dark hover layer on enrolled Academy path rows.

### Earlier 1.0.x releases

- Improved Academy path rows, path headers, profile rank cards, Pwnbox text, question panels, terminal output, hover states, and general contrast across HTB pages.
