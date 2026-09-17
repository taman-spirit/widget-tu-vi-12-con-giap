# 12 zodiac animals today

A grid of the twelve animals, each showing its computed relation to today's branch.

*[Đọc bản tiếng Việt](README.md)*

**See it running:** https://nhatnguyet.org/widget/tu-vi-12-con-giap

## Paste these two lines

```html
<div data-widget="tu-vi-12-con-giap"></div>
<script async src="https://nhatnguyet.org/embed/w.js"></script>
```

No account, no API key, nothing to pay.

## What it gives your page

All twelve zodiac animals in one frame, each cell showing how today's Earthly Branch stands in relation to that animal's branch under the Three Harmonies, Four Clashes and Six Harms tables. Tap an animal to read what that relation means.

## Worth knowing before you embed

- Each cell states how that animal stands to today: Three Harmonies, Four Clashes or Six Harms.
- These are fixed groupings from the classical tables, so they can simply be looked up. They are not predictions.
- The widget writes no daily fortune for any sign. Tap an animal and you get an explanation of what that relation means.

## The steps

1. Paste the snippet. The default is a three-column grid, suited to a wide sidebar.
2. For a narrow sidebar, switch to the single-column layout.
3. Tap an animal to open its explanation, tap again to close.

## Where to paste it

**WordPress.** Add a *Custom HTML* block to the post, or a *Text* widget in
the sidebar, and paste both lines there. Do not paste into the ordinary
editor: it will show the code as text instead of running it.

**Wix, Squarespace, Shopify.** Use the *Embed HTML* / *Custom HTML* block.

**Hand-written sites.** Paste it straight where you want the widget. If you
embed several widgets, the `<script>` line only needs to appear once on the
page.

**A note on width.** The widget fits the width of wherever you put it. If that is narrower than 280px, add
`data-size="compact"`; if it is a wide horizontal strip, use
`data-size="wide"`.

## Make it match your page

| Attribute | Values | Meaning |
|---|---|---|
| `data-widget` | `tu-vi-12-con-giap` | Required |
| `data-theme` | light or dark | Defaults to light |
| `data-accent` | #b3341f | Accent colour as a 6-digit hex value, to match your own branding |
| `data-lang` | vi or en | Defaults to vi |
| `data-layout` | grid or list | Applies to the 12 zodiac animals widget only |
| `data-size` | compact, standard or wide | Level of detail for the width you have: compact drops secondary detail, wide lays out horizontally. Defaults to standard |

With every attribute this widget accepts, it looks like this:

```html
<div data-widget="tu-vi-12-con-giap" data-theme="dark" data-accent="#1f6f5c" data-lang="en" data-layout="list" data-size="compact"></div>
<script async src="https://nhatnguyet.org/embed/w.js"></script>
```

Want to see it for yourself before it goes near your real page? Open
[`vi-du/index.html`](vi-du/index.html) in a browser, nothing to install.

## A few things we ask

- Free for personal and business websites, with no display limit.
- Keep the attribution line at the foot of the widget. That is what you give
  in return for free use.
- Do not embed on gambling, adult, fraudulent sites or anything unlawful
  under Vietnamese law.
- The content is folk knowledge and cultural convention, offered as
  reference, not as health, financial or legal advice.

Full text: [`TERMS.md`](TERMS.md) · [https://nhatnguyet.org/widget/dieu-khoan](https://nhatnguyet.org/widget/dieu-khoan)

## Who we are

Nhat Nguyet (https://nhatnguyet.org) is a Vietnamese reference site for calendrical and
cultural knowledge: the lunar calendar computed for Vietnam's own time zone,
the sexagenary cycle, solar terms, auspicious hours, astrology, feng shui,
and a glossary of terms.

There is one thing we try hard to keep clear, even inside a 300px frame:
which parts are computed, and which are folk convention.

Lunar dates, sexagenary names and solar terms are **computed**. Run the same
calculation and you get the same answer, and we publish the underlying
datasets under CC BY 4.0 so you can check for yourself.

Auspicious hours, Bat Trach directions and Lo Ban rule bands are **cultural
convention**. There are real lookup tables behind them, but they are not
measurements. The widget tells you what the table says; how much weight to
give it is yours to decide.

Where the schools disagree, we say so, rather than quietly picking a side and
presenting it as the only reading.

Open data: [GitHub](https://github.com/taman-spirit/du-lieu-am-lich) ·
[Hugging Face](https://huggingface.co/datasets/nhatnguyet)

## Something not right?

Open an issue in this repository. We do read them.

The whole widget library: [https://nhatnguyet.org/widget](https://nhatnguyet.org/widget)
