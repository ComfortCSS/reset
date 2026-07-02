# ComfortCSS Reset

A modern CSS reset for web projects.

## Installation

```bash
npm install comfortcss/reset:1.X.X
```

Alternatively, download the files manually from the repository.

## Usage

At the very beginning of the CSS file:
```css
@import '@comfortcss/reset/dist/reset.min.css';
```
For example, just the basic reset and forms:
```css
@import "@comfortcss/reset";
@import "@comfortcss/reset/reset";
@import "@comfortcss/reset/modules/core/base.css";
```

## Modules

| Module | Description |
|--------|-------------|
|base|Box model, html, body, system colors|
|typography|Headings, paragraphs, lists, quotes, code, hr|
|forms|All input fields, buttons, select elements, and textareas|
|tables|Tables, cells, captions|
|media|Images, videos, iframes, SVG, audio|
|interactive|Links, focus, hidden, disabled, contenteditable|
|accessibility|prefers-reduced-motion, system @property|

## License

[MIT](LICENSE)
