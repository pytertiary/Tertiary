# Tertiary3

A custom, single-file website for Tertiary3 and **PyTertiary (PT3)**.

- [Live GitHub Pages URL](https://pytertiary.github.io/Tertiary/) (requires Pages to be enabled)
- [Edit the website](https://github.com/pytertiary/Tertiary/edit/main/index.html)
- [GitHub Pages settings](https://github.com/pytertiary/Tertiary/settings/pages)

## Publish

In **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, and save. GitHub Pages will publish `index.html` automatically.

## Design

The website is built entirely in one `index.html` file with bespoke CSS and vanilla JavaScript. Its palette uses **#d12a2a** (red), **#18181b** (gray), **#262626** (lighter gray), **#fff** and **#e0e0e0** (white and silver). The header wordmark toggles between **Tertiary3** and **T3**. Hover or keyboard-focus **Download PyTertiary** to see the About PT3 panel. The page includes a PT3 product information section, $5 and $45 options, the Cash App handle **$pytertiary**, and Discord username **pytertiary**.

## Setting up a real download

No installer or direct download URL was supplied. The "Download PyTertiary" navigation currently links to the PT3 product/purchase section, **not to an installer**.

When you have a published release or download page:

1. Open `index.html`.
2. Edit the header's `href="#pyt"` to link to your real download destination, or add a separate download button next to the pricing options.
3. Verify your links, platform compatibility, prices and purchasing instructions before publishing.
4. Keep all customer details, payment secrets and credentials **out of this public repository**.

GitHub Pages serves static files only; payments and license delivery must be handled through a separate trusted process.

## Contacts

- Cash App: **$pytertiary**
- Discord: **pytertiary**

The page has accessible focus behavior and reduced-motion support, and does not load third-party JavaScript libraries.
