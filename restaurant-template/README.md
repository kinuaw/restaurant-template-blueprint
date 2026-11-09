# Ember & Oak: Modern Restaurant Website Template

Thank you for your purchase! This is a fast, mobile-friendly, one-page restaurant website built with plain HTML, CSS and a tiny bit of JavaScript. No frameworks, no build tools, no installs.

## What's inside

```
restaurant-template/
├── index.html   ← all your content (text, menu, hours)
├── style.css    ← colors, fonts, layout
├── script.js    ← mobile menu and menu tabs
├── images/      ← put your photos here
└── README.md    ← this guide
```

## Quick start (5 minutes)

1. Unzip the folder.
2. Double-click `index.html`. It opens in your browser.
3. Open `index.html` in any text editor (VS Code, Notepad, TextEdit) and start replacing the sample text.

## 1. Change the restaurant name

Search `index.html` for **Ember** and replace it with your name. It appears in the page title, the logo at the top, and the footer.

## 2. Change the colors (10 seconds)

Open `style.css`. The first block, `:root`, controls every color:

```css
--accent: #c8793a;   /* buttons and highlights */
--bg: #14100d;       /* page background */
--text: #f3ebe2;     /* text color */
```

Ideas to try:
- **Fresh green:** `--accent: #5fa36a;`
- **Tomato red:** `--accent: #d6452f;`
- **Light theme:** `--bg: #fbf7f2; --bg-soft: #f3ece3; --card: #ffffff; --text: #231a14; --muted: #6d5f54;`

## 3. Change the fonts

In `style.css`, edit `--font-head` and `--font-body`. To use a Google Font, add its `<link>` tag inside `<head>` in `index.html`, then use the font name in `style.css`.

## 4. Edit the menu

In `index.html`, find the `MENU` section. Each dish looks like this:

```html
<li class="dish"><div><h3>Dish name</h3><p>Short description</p></div><span class="price">$12</span></li>
```

- **Add a dish:** copy one line and paste it inside the same list.
- **Remove a dish:** delete its line.
- **Change currency:** replace `$` with your currency symbol or code.

## 5. Add your photos

Photo spots are currently colored placeholders.

1. Put your photos inside the `images/` folder (JPG or WebP, ideally under 300 KB each).
2. For **gallery** and **about** placeholders, replace the inside of each `<div class="ph ...">` with:
   ```html
   <img src="images/photo1.jpg" alt="Describe the photo">
   ```
3. For the **hero** image, replace the whole `<svg>...</svg>` block with:
   ```html
   <img src="images/hero.jpg" alt="Your signature dish">
   ```

## 6. Update address, phone, hours

Find the `VISIT` section in `index.html` and edit the text. For a clickable phone number, change both parts of `tel:+10000000000`.

## 7. Make the booking form work (free)

1. Create a free account at [formspree.io](https://formspree.io).
2. Create a new form and copy its ID.
3. In `index.html`, replace `YOUR_FORM_ID` in the form `action` with your ID.

Booking requests will now arrive in your email. If you prefer, you can remove the form and replace it with a "Call to book" button.

## 8. Put it online

Easy and free options:
- **Netlify Drop:** drag the whole folder onto netlify.com/drop
- **GitHub Pages**
- **Cloudflare Pages**
- Any normal web hosting: upload the files to the `public_html` folder.

## Tips

- Keep descriptions short. Visitors skim on their phones.
- Compress photos with a free tool like squoosh.app before uploading.
- Add your Google Maps link to the address for easy directions.

## License

You may use this template for your own restaurant or for client projects. Please don't resell or redistribute the template files themselves.

Need help? Message the seller through the Gumroad receipt page.
