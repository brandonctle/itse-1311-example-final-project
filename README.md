# ISTE 1311 Example Final Project: Johnny Appleseed

A sample personal portfolio site for the ISTE 1311 (Beginning Web Programming) final project at Lone Star College. **Johnny Appleseed** is a made-up persona who is passionate about apples. All names, numbers, and contact details are fictional.

Use this as a reference for structure, not as a template to copy. Your site should reflect your own topics and design.

## Pages

| Page | File | Shows off |
| --- | --- | --- |
| Home | `index.html` | Hero section, flexbox cards |
| About Me | `about.html` | Two-column layout, figure + figcaption, unordered and description lists |
| Special Topic 1: Varieties | `varieties.html` | Accessible data table (caption, th, scope), responsive table, external link |
| Special Topic 2: Recipes | `recipes.html` | Ordered lists, same-page jump links, aside |
| Special Topic 3: Orchards | `orchards.html` | Flexbox photo gallery with figures, external links |
| Contact | `contact.html` | Form with fieldsets, labels, HTML5 input types, required and pattern validation |

## Folder structure

```
index.html
about.html
varieties.html
recipes.html
orchards.html
contact.html
styles/
    main.css
images/
    logo.svg  johnny.svg  orchard.svg  apple-pie.svg  basket.svg
```

## Where to find each rubric item

- **Page structure and semantics (Ch 2, 3):** every page has a doctype, `lang`, a meta charset, a viewport, a description, a unique title, and `header` / `nav` / `main` / `footer`
- **External CSS (Ch 4):** `styles/main.css` is shared by every page and uses custom properties (variables)
- **Box model (Ch 5):** reset selector, padding, borders, border-radius, box-shadow, gradient background
- **Flexbox (Ch 6, 7):** header, nav menu, cards, two-column layouts, gallery
- **Navigation (Ch 7, 9):** same menu on every page; `aria-current="page"` highlights the current page
- **Responsive (Ch 8):** media queries at 900px and 600px; the table stacks into cards on phones
- **Images, fonts, color (Ch 10):** SVG images with alt text, a favicon, and Merriweather from Google Fonts with a serif fallback
- **Table (Ch 11):** `varieties.html`
- **Form (Ch 12):** `contact.html`
- **Go further (Ch 15, 17):** hover transitions and transforms; hosted on GitHub Pages

## Credits

- All illustrations were drawn in SVG for this sample.
- Font: [Merriweather](https://fonts.google.com/specimen/Merriweather) via Google Fonts (SIL Open Font License).
