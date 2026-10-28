# Japanese Verbs 動詞

A study app for 134 common Japanese verbs. It is the companion to the N5 Kanji app.

- **Verbs:** browse by topic or verb group, or search for a verb, its meaning, or any conjugated form (for example `食べた` or `tabemasen`). Tap a verb to see all 29 forms in kanji, hiragana and rōmaji with English, the formation rule for each, an example sentence and notes on exceptions.
- **Drill:** multiple-choice practice. *Make the form* asks for a given form of a verb; *Name the form* shows a conjugated word and asks which form it is. Filter by form category, verb group, topic or a single verb. Mistakes are listed for review.

Once loaded, it works offline.

## Publish with GitHub Pages

1. Upload every file in this folder to a GitHub repository (all files sit at the top level).
2. In the repository, open **Settings › Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Install on iPhone or iPad

1. Open the site's URL in **Safari**.
2. Tap **Share › Add to Home Screen**, then **Add**.
3. Launch **Verbs** from the home screen. It opens full screen.
4. Open it once while online. After that it works without a connection.

On Android or desktop Chrome, use the install icon in the address bar, or **⋮ › Install app**.

## Updating

After changing `index.html`, also change `VERSION` in `sw.js` (for example `jp-verbs-v2`). Installed copies pick up the new version the next time they are opened online.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app: page, styles, script, verb data and conjugation engine |
| `manifest.webmanifest` | App name, colours and icons for installing |
| `sw.js` | Service worker that caches the app for offline use |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | Home-screen and browser icons |

## Notes

Rōmaji uses modified Hepburn with long vowels written out (ou, uu). JLPT levels are approximate, because the JLPT has published no official vocabulary list since 2010. Fonts: Shippori Mincho and Zen Kaku Gothic New from Google Fonts.
