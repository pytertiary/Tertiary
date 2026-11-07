# Tertiary3 — website

A custom single-file website for Tertiary3 and **PyTertiary (PT3)**, built with HTML, bespoke CSS, and vanilla JavaScript.

- **Website:** https://pytertiary.github.io/Tertiary/ (GitHub Pages must be enabled)
- **Edit page:** https://github.com/pytertiary/Tertiary/edit/main/index.html
- **Pages settings:** https://github.com/pytertiary/Tertiary/settings/pages

## Publish

Go to **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/(root)**, then save.

## Appearance & interactions

- Full-height landing screen with **Tertiary3** and the headings **Bypass. Exploit. Abuse.**
- Click or keyboard-activate each heading to toggle an inline definition.
- Top-right wordmark toggles between **Tertiary3** and **T3**.
- Hover or keyboard-focus **Download PyTertiary** to open the About PT3 menu.
- Responsive breakpoints and reduced-motion behavior.
- Animations include entrance reveals, interactive heading underlines, subtle logo glow and scroll reveals.
- Colors: red **#d12a2a**, dark gray **#18181b**, lighter gray **#262626**, white **#fff**, silver **#e0e0e0**.
- Software details, PT3 logo and pricing appear below the landing screen.

## Logo

The PT3 logo is loaded from **`PT3LogoBig.png`** at the repository root, next to **`index.html`**. If the logo is unavailable, the page displays a fallback PT3 text mark.

## Download and purchasing

The **Download PyTertiary** navigation item currently scrolls to product information because no direct installer URL has been provided. The two listed prices are **$5** and **$45**. The page directs visitors to Cash App **$pytertiary** and Discord username **pytertiary**. Confirm purchase and delivery terms before making payments.

To add a real installer/release link, edit `index.html` and update the header anchor to a verified download URL, or add a separate download link. Avoid storing secrets, private customer details or sensitive payment information in this public repository.

GitHub Pages serves static content; it does not process payments or manage licenses on its own.
