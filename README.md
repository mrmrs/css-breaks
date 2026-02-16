# css-breaks

Functional CSS for breaks

## Filesize

| File | Size |
|------|------|
| `dist/breaks.css` | 1051 bytes |
| `dist/breaks.min.css` | 818 bytes (224 Gzipped) |

## Install

```sh
npm install css-breaks
```

## Usage

### Import

```css
@import "css-breaks";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-breaks/dist/breaks.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-breaks/dist/breaks.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.ba-auto` | `break-after: auto;` |
| `.ba-always` | `break-after: always;` |
| `.ba-lleft` | `break-after: left;` |
| `.ba-right` | `break-after: right;` |
| `.ba-recto` | `break-after: recto;` |
| `.ba-verso` | `break-after: verso;` |
| `.ba-page` | `break-after: page;` |
| `.ba-column` | `break-after: column;` |
| `.ba-region` | `break-after: region;` |
| `.ba-avoid` | `break-after: avoid;` |
| `.ba-avoid-page` | `break-after: avoid-page;` |
| `.ba-avoid-column` | `break-after: avoid-column;` |
| `.ba-avoid-region` | `break-after: avoid-region;` |
| `.bb-auto` | `break-before: auto;` |
| `.bb-always` | `break-before: always;` |
| `.bb-left` | `break-before: left;` |
| `.bb-right` | `break-before: right;` |
| `.bb-recto` | `break-before: recto;` |
| `.bb-verso` | `break-before: verso;` |
| `.bb-page` | `break-before: page;` |
| `.bb-column` | `break-before: column;` |
| `.bb-region` | `break-before: region;` |
| `.bb-avoid` | `break-before: avoid;` |
| `.bb-avoid-page` | `break-before: avoid-page;` |
| `.bb-avoid-column` | `break-before: avoid-column;` |
| `.bb-avoid-region` | `break-before: avoid-region;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ba-auto-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/breaks.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/breaks.css` — formatted
- `dist/breaks.min.css` — minified

## License

MIT
