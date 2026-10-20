# New Icons
New icons for the toolbar, popups, site data panel, and better locale button

> **Fork note (v1.5):** this is a maintained fork of [qumeqa/zen-icons](https://github.com/qumeqa/zen-icons), which is archived.
>
> **What was fixed:** on Zen 1.23 (Firefox 158) every icon from this mod showed up blank.
>
> **Why:** the icons were inline `data:` SVGs colored with `context-fill`, so they would match the toolbar's color. Firefox no longer passes that color into `data:` SVGs, so the strokes painted with no color. Zen's own icons still work because they load from `chrome://` URLs.
>
> **How:** each SVG now lives in `icons/`. The mod ships a `chrome.manifest` that Sine registers, so the CSS loads the icons from `chrome://newicons/content/…`, where `context-fill` still works. The icons themselves are unchanged.
>
> Install in Sine from `https://github.com/LoopRook/zen-icons`. If you have the original installed, remove it first.

<img src="https://raw.githubusercontent.com/LoopRook/zen-icons/refs/heads/main/photo/icons.jpg" width="100%">

<img src="https://raw.githubusercontent.com/LoopRook/zen-icons/refs/heads/main/photo/main.jpg" width="100%">
