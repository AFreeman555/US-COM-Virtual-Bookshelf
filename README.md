# Virtual Bookshelf

A clean, responsive virtual bookshelf. Click any cover to open the purchase page in a new tab. Includes placeholder covers you can replace with your own.

## 🚀 Quick Start
1. Open `index.html` in your browser.
2. Click a cover to open its purchase link.
3. Use the search bar and category filter to find titles quickly.

## ✏️ Customize Books
Each book is a small HTML block in `index.html` inside the `<div class="bookshelf">`:

```html
<div class="book" data-category="fiction" data-title="The Aurora Secret" data-author="J. M. Kade">
  <a href="https://books.example.com/aurora-secret" target="_blank" rel="noopener noreferrer">
    <img src="assets/covers/the-aurora-secret.jpg" alt="The Aurora Secret — J. M. Kade"/>
  </a>
  <div class="book-title">The Aurora Secret</div>
  <div class="book-author">J. M. Kade</div>
</div>
```

- **Change the image**: Replace the file in `assets/covers/` and update the `src` path.
- **Change the purchase link**: Update the `<a href="…">` value.
- **Change the category**: Update `data-category` (e.g., `fiction`, `non-fiction`, `science`, `business`, `biography`).
- **Add a book**: Copy one block and paste it as a new sibling, then adjust values.

## 🌐 Host Online
### GitHub Pages
1. Create a repo and upload the contents of this folder.
2. In **Settings → Pages**, set **Source** to `main` (or your default) and the root folder.
3. Wait a minute, then visit `https://<your-username>.github.io/<repo-name>/`.

### Netlify (drag‑and‑drop)
1. Go to https://www.netlify.com/ and sign in.
2. Click **Add new site → Deploy manually**.
3. Drag the entire folder and drop it into the upload box.

## 🛠️ Optional Tweaks
- Replace placeholder covers with real ones (recommended size: ~600×900 JPG/PNG).
- Update colors or spacing inside the `<style>` block in `index.html`.
- Add new categories by adding an `<option>` in the `<select>` and using the same value in `data-category`.

Enjoy!
