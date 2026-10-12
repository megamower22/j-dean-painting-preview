# J Dean Painting – preview website

This is a free preview website for **J Dean Painting** (La Crosse, WI), built by Hudson | Lacrosse Lawn & Landscape.
It is plain HTML and CSS: no build step, no monthly fees for hosting.

Live preview: https://megamower22.github.io/j-dean-painting-preview/

## How to change text on the site (on github.com)

1. Go to this repo on github.com and sign in.
2. Click **index.html**.
3. Click the **pencil icon** (Edit this file) at the top right of the file.
4. Find the words you want to change and type the new text. Only change the words between the tags, not the `<` `>` parts.
5. Scroll down (or click the green **Commit changes...** button), add a short note like "Update hours", and click **Commit changes**.
6. Wait about a minute, then refresh the website. Your change will be live.

## Good to know

- **Colors** are at the top of `style.css`: `--ink` and `--paper` are the base, and `--tomato`, `--sun`, `--sky` and `--mint` are the paint-swatch accents.
- **Fonts** come from Google Fonts: **Chango** for headings, **Albert Sans** for body text and buttons (`--font-display` and `--font-body` in `style.css`).
- Anything in yellow highlight that says **[Owner to confirm]** still needs real info from the owner. Once it's confirmed, delete the whole `<span class="placeholder">...</span>` part.
- **Services** are the `<li>` items inside the two `class="chips"` lists (Interior and Exterior).
- **Reviews** are real Google reviews, shown as `<blockquote class="note">` blocks. When the review count changes, search for `23 Google` and update it (it appears twice).
- The phone number appears in several places. Search for `780-8501` (and `+16087808501` in the call links) to update all of them.
- The email appears in several places. Search for `jonrdean@gmail.com` to update it.
- To remove the "Preview site" banner once the owner approves, delete the line with `class="preview-banner"` in `index.html`.
