# Satoshi

Satoshi is Antler's recommended typeface for AI-built landing pages and prototypes. It is published by [Indian Type Foundry](https://www.indiantypefoundry.com/) and distributed via [Fontshare](https://www.fontshare.com/fonts/satoshi).

This repo does **not** host the font files — link to Fontshare's CDN instead.

## Embed via Fontshare CDN

### HTML `<link>` (recommended)

```html
<link
  href="https://api.fontshare.com/v2/css?f[]=satoshi@300,301,400,401,500,501,700,701,900,901&display=swap"
  rel="stylesheet"
/>
```

### CSS `@import`

```css
@import url('https://api.fontshare.com/v2/css?f[]=satoshi@300,301,400,401,500,501,700,701,900,901&display=swap');
```

The trailing digit in each weight token toggles italic: `400` = regular, `401` = regular italic. Drop any weights you don't need to reduce payload.

## Available styles

| Weight | Name | Italic |
|---:|---|:---:|
| 300 | Light | ✓ |
| 400 | Regular | ✓ |
| 500 | Medium | ✓ |
| 700 | Bold | ✓ |
| 900 | Black | ✓ |

## Usage

### CSS

```css
body {
  font-family: 'Satoshi', system-ui, sans-serif;
}
```

### Tailwind

```js
// tailwind.config.js
module.exports = {
  theme: {
    extend: {
      fontFamily: {
        sans: ['Satoshi', 'system-ui', 'sans-serif'],
      },
    },
  },
};
```

## License

Free for personal and commercial use under the Fontshare license. Do not redistribute the font binaries — link to the Fontshare CDN. See [Fontshare's license terms](https://www.fontshare.com/licenses/itf-ffl) for the authoritative wording.
