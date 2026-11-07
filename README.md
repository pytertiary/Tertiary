# Tertiary — Business Website

A lightweight, mobile-friendly storefront for **Tertiary**, hosted with GitHub Pages. No build tools, dependencies, server or paid hosting required.

## Publish on GitHub Pages

1. Open [this repository's Pages settings](https://github.com/pytertiary/Tertiary/settings/pages).
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Choose **main** and **/(root)**, then select **Save**.
4. Your site should be available at **https://pytertiary.github.io/Tertiary/** after GitHub finishes publishing.

> The repository contains the site files, but GitHub Pages still needs to be enabled in Settings.

## Customize your storefront

Open [index.html](https://github.com/pytertiary/Tertiary/blob/main/index.html), click the pencil icon to edit, then scroll to the `STORE` object near the bottom. Replace the empty values with your actual business details.

```js
const STORE = {
  contactEmail: "you@example.com",             // replace with your real business email
  instagramUrl: "https://instagram.com/YOURNAME", // optional
  products: [
    {
      name: "Your product name",
      price: "$15",
      category: "Accessories",
      description: "Describe the product here.",
      image: "images/your-photo.jpg",            // optional
      buyUrl: "https://your-real-checkout-link", // optional
      tag: "New"                                 // optional
    }
  ]
};
```

**The example values above are placeholders.** Only publish genuine product descriptions, prices and checkout links.

Each product is automatically shown in the catalog, and customers can search by name or description and filter by category. If you omit a product's image, a graphic placeholder appears. If you omit `buyUrl`, a customer can ask about the product by email if you've added `contactEmail`. Products with neither a checkout link nor a contact email will show no ordering link.

### Adding product images

Inside the repository, create a folder named `images` and upload your photos. Refer to them from your product entries as `images/filename.jpg`. Photos work best when they're clear, square or landscape-oriented, and compressed for the web.

### Editing the text, colors and layout

The HTML, CSS and JavaScript all live in `index.html`. Edit the heading and text directly. The main color palette is defined near the top inside the `:root` CSS rule. This site works without any external framework.

## A note about payments

GitHub Pages only hosts **static websites**. It cannot securely process payments or store private customer/order data on its own. To take payments, point each `buyUrl` to a trusted external checkout service you set up. **Never put passwords, API secrets or private customer data in this public repository.**

## What's included

- Responsive home, product catalog, about and contact sections
- Search and category filters when products are available
- Image placeholders, optional product photos and external checkout links
- Contact-by-email and optional Instagram link
- Accessible navigation, reduced-motion support, no third-party tracking scripts

---

Made for Tertiary ✳
