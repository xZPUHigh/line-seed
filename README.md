# line-seed

LINE Seed Sans TH as woff2, mirrored here so my sites do not depend on somebody else's repository staying where it is.

Five weights, 156KB for the whole family.

## Use

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/xZPUHigh/line-seed@1.0.0/line-seed-sans-th.css"
/>
```

```css
body {
  font-family: "LINE Seed Sans TH", system-ui, sans-serif;
}
```

Pin the tag. `@main` moves under you, and jsDelivr caches it for twelve hours, which is the worst of both.

For a site where Thai is most of the page, copy the woff2 files into the project instead and serve them from the same origin: one less DNS lookup and TLS handshake before any text can paint.

## Weights

| Weight | File | CSS |
|---|---|---|
| Thin | LINESeedSansTH-Thin.woff2 | 100 |
| Regular | LINESeedSansTH-Regular.woff2 | 400 |
| Bold | LINESeedSansTH-Bold.woff2 | 500 to 700 |
| ExtraBold | LINESeedSansTH-ExtraBold.woff2 | 800 |
| Black | LINESeedSansTH-Black.woff2 | 900 |

Bold covers 500 and 600 as well, so `font-weight: 600` gets a real face instead of a synthesised one.

## Licence

LINE Seed is (c) 2020-2022 LINE Corporation, licensed under the SIL Open Font License 1.1. The original notice is in `LICENSE.txt` and has to travel with the files.

Sources: [seed.line.me](https://seed.line.me), woff2 conversions from [lazywasabi/thai-web-fonts](https://github.com/lazywasabi/thai-web-fonts).
