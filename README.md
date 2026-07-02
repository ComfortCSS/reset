# ComfortCSS Reset

A modern CSS reset for web projects.

## Installation

```bash
npm install comfort-css-reset
```

Alternatively, download the files manually from the repository.

## Usage

At the very beginning of the CSS file:
```css
@import 'comfort-css-reset/dist/reset.min.css';
```
For example, just the basic reset and forms:
```css
@import 'comfort-css-reset/src/core/base.css';
@import 'comfort-css-reset/src/core/forms.css';
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
