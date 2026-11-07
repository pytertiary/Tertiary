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


## Refund policy

The standalone [refund policy](refunds.html) is linked from the pricing section and footer.

- **Basic key:** $5, 30 days. Unused keys: full refund within 14 days of purchase. Used keys: full refund within 3 days of purchase, provided usage was **less than 45 minutes**.
- **Ultra key:** $45, 300 days. Unused keys: full refund within 30 days of purchase. Used keys: full refund within **72 hours of purchase**, provided usage was **less than 30 minutes**.
- If a payment was sent without the app-generated **12-character alphanumeric key** (from **I don't have a key**), contact official support immediately. Provide the amount sent, payment time and relevant account/transaction details.
- Official Discord: https://discord.gg/wS7GHzEj3N
- Official Discord support username: **pytertiary**

You can edit the refund policy by editing [refunds.html](refunds.html). Keep `index.html` pricing and policy text consistent whenever the terms change.

## Download and purchasing

The **Download PyTertiary** navigation item currently scrolls to product information because no direct installer URL has been provided. The two listed prices are **$5** and **$45**. The page directs visitors to Cash App **$pytertiary** and Discord username **pytertiary**. Confirm purchase and delivery terms before making payments.

To add a real installer/release link, edit `index.html` and update the header anchor to a verified download URL, or add a separate download link. Avoid storing secrets, private customer details or sensitive payment information in this public repository.

GitHub Pages serves static content; it does not process payments or manage licenses on its own.
