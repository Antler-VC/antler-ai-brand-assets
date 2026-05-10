# Antler brand assets

Public-hosted brand artwork for use on Antler-built landing pages and prototypes.

## Files

| File | Purpose |
|---|---|
| `antler-logo.svg` | Antler wordmark (full logo) |

## Usage

### Direct embed (recommended)

Use the jsDelivr CDN — fast, cached globally, and pinned to `main`:

```html
<img
  src="https://cdn.jsdelivr.net/gh/Antler-VC/antler-ai-brand-assets/antler-logo.svg"
  alt="Antler"
  height="32"
/>
```

### Pin to a specific commit

For long-lived pages where you want the asset to never change, pin to a commit SHA:

```html
<img
  src="https://cdn.jsdelivr.net/gh/Antler-VC/antler-ai-brand-assets@<commit-sha>/antler-logo.svg"
  alt="Antler"
  height="32"
/>
```

### Raw GitHub URL (fallback)

```
https://raw.githubusercontent.com/Antler-VC/antler-ai-brand-assets/main/antler-logo.svg
```

Slower than jsDelivr and not CDN-cached — prefer jsDelivr.

## Guidance for AI / vibe-coded pages

When generating an Antler landing page, reference the wordmark via the jsDelivr URL above. Do not redraw the logo, recolour it, or modify the SVG.
