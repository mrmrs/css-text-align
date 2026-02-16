# css-text-align

Functional CSS for text-align

## Filesize

| File | Size |
|------|------|
| `dist/text-align.css` | 1773 bytes |
| `dist/text-align.min.css` | 1165 bytes (275 Gzipped) |

## Install

```sh
npm install css-text-align
```

## Usage

### Import

```css
@import "css-text-align";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-text-align/dist/text-align.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-text-align/dist/text-align.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.tl` | `text-align: left;` |
| `.tr` | `text-align: right;` |
| `.tc` | `text-align: center;` |
| `.tj` | `text-align: justify;` |
| `.ts` | `text-align: start;` |
| `.te` | `text-align: end;` |
| `.tmp` | `text-align: match-parent;` |
| `.tse` | `text-align: start end;` |
| `.tp` | `text-align: ".";` |
| `.tsp` | `text-align: start ".";` |
| `.tpe` | `text-align: "." end;` |
| `.tl-s` | `text-align: left;` |
| `.tr-s` | `text-align: right;` |
| `.tc-s` | `text-align: center;` |
| `.tj-s` | `text-align: justify;` |
| `.ts-s` | `text-align: start;` |
| `.te-s` | `text-align: end;` |
| `.tmp-s` | `text-align: match-parent;` |
| `.tse-s` | `text-align: start end;` |
| `.tp-s` | `text-align: ".";` |
| `.tsp-s` | `text-align: start ".";` |
| `.tpe-s` | `text-align: "." end;` |
| `.tl-m` | `text-align: left;` |
| `.tr-m` | `text-align: right;` |
| `.tc-m` | `text-align: center;` |
| `.tj-m` | `text-align: justify;` |
| `.ts-m` | `text-align: start;` |
| `.te-m` | `text-align: end;` |
| `.tmp-m` | `text-align: match-parent;` |
| `.tse-m` | `text-align: start end;` |
| `.tp-m` | `text-align: ".";` |
| `.tsp-m` | `text-align: start ".";` |
| `.tpe-m` | `text-align: "." end;` |
| `.tl-l` | `text-align: left;` |
| `.tr-l` | `text-align: right;` |
| `.tc-l` | `text-align: center;` |
| `.tj-l` | `text-align: justify;` |
| `.ts-l` | `text-align: start;` |
| `.te-l` | `text-align: end;` |
| `.tmp-l` | `text-align: match-parent;` |
| `.tse-l` | `text-align: start end;` |
| `.tp-l` | `text-align: ".";` |
| `.tsp-l` | `text-align: start ".";` |
| `.tpe-l` | `text-align: "." end;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.tl-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/text-align.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/text-align.css` — formatted
- `dist/text-align.min.css` — minified

## License

MIT
