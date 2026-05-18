# css-breaks

Functional CSS for breaks

## Filesize

| File | Size |
|------|------|
| `dist/breaks.css` | 1010 bytes |
| `dist/breaks.min.css` | 777 bytes (221 Gzipped) |

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
| `.ba-aut` | `break-after: auto;` |
| `.ba-al` | `break-after: always;` |
| `.ba-l` | `break-after: left;` |
| `.ba-r` | `break-after: right;` |
| `.ba-rect` | `break-after: recto;` |
| `.ba-vers` | `break-after: verso;` |
| `.ba-page` | `break-after: page;` |
| `.ba-col` | `break-after: column;` |
| `.ba-reg` | `break-after: region;` |
| `.ba-avoid` | `break-after: avoid;` |
| `.ba-avoid-page` | `break-after: avoid-page;` |
| `.ba-avoid-column` | `break-after: avoid-column;` |
| `.ba-avoid-region` | `break-after: avoid-region;` |
| `.bb-aut` | `break-before: auto;` |
| `.bb-al` | `break-before: always;` |
| `.bb-l` | `break-before: left;` |
| `.bb-r` | `break-before: right;` |
| `.bb-rect` | `break-before: recto;` |
| `.bb-vers` | `break-before: verso;` |
| `.bb-page` | `break-before: page;` |
| `.bb-col` | `break-before: column;` |
| `.bb-reg` | `break-before: region;` |
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

Example: `.ba-aut-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/breaks.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/breaks.css` — formatted
- `dist/breaks.min.css` — minified

## License

MIT
