<h1 align="center">joey</h1>
<p align="center">
  <img alt="icon" width="20%" src="https://raw.githubusercontent.com/xshapira/joey/main/icon.png">
</p>

A minimal theme that helps you code with joy and focus.

* [x] Eye-friendly highlighting
* [x] Optimized for focus
* [x] Support for Python syntax

<p align="center">
  <img alt="joey-theme-snap" width="80%" src="https://raw.githubusercontent.com/xshapira/joey/main/screenshots/joey-theme-snap.png">
</p>

<p align="center">
  <img alt="joey-theme-snap-2" width="80%" src="https://raw.githubusercontent.com/xshapira/joey/main/screenshots/joey-theme-snap-2.png">
</p>

<p align="center">
  <img alt="joey-theme-snap-2" width="80%" src="https://raw.githubusercontent.com/xshapira/joey/main/screenshots/joey-theme-snap-3.png">
</p>

## Font Styles

This theme doesn't automatically apply italic and bold styling, giving users the freedom to personalize their look.

If you wish to use the italic/bold stylings this theme suggests for improved readability, add the following to your `settings.json` :

```json
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "name": "italics & bold",
        "scope": [
          //following will be in italic bold
          "keyword", //import, export, return…
          "keyword.control.flow",
          "storage.modifier", //static keyword
          "storage.type",
          "support.function.builtin"
        ],
        "settings": {
          "fontStyle": "italic bold"
        }
      },
      {
        "name": "No italics",
        "scope": ["comment", "keyword.operator", "keyword.key"],
        "settings": {
          "fontStyle": ""
        }
      }
    ]
  }
```

## In preview

The font in preview is [MonoLisa](https://www.monolisa.dev/).

## Other

This theme is a next-level version of [shaodahong](https://github.com/shaodahong/)'s fantastic [bear theme](https://github.com/shaodahong/theme-bear), now improved and updated to offer even more to your productivity.
