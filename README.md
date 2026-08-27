# Ethnikka Login

A single static HTML page implementing a sign-in form UI for "Ethnikka," an Indian ethnic-wear/fashion-style brand (see the floral logo). It's a small front-end practice/prototype page, not a working application — the form has no JavaScript or backend, so submitting it doesn't actually authenticate anything.

## Tech stack

- HTML5
- CSS (inline `<style>` block in the HTML, no external stylesheet or framework)
- No JavaScript, no backend, no build tooling

## Running it locally

There's no build step. Just open the file directly in a browser:

```
open login.html
```

(or double-click `login.html` in a file browser)

## File structure

```
.
├── login.html         # The login page (markup + styling)
├── finalloginbg.jpg    # Background image used by login.html
└── logo.png            # Ethnikka logo image (not referenced by login.html)
```

Note: `logo.png` isn't actually linked from `login.html` — the page only uses `finalloginbg.jpg` as its background. `logo.png` appears to be an unused/leftover asset.
