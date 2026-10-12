# CDSEO for CS-Cart

**🛑 PREMIUM ADD-ON: This repository does not contain the open-source code. It serves as the official listing and documentation page for the WebGraphiq premium add-on.**

**CDSEO** (Custom Dynamic Search Engine Optimization) is an SEO and JSON-LD schema suite for CS-Cart and Multi-Vendor. It extends the built-in SEO add-on with custom canonical paths, 301 redirects for disabled items, Open Graph and Twitter cards, BreadcrumbList markup, and Google-oriented structured data for Organization, Product, WebSite, Article, NewsArticle, and BlogPosting.

## [🛒 Buy & View Live Demo](https://www.webgraphiq.com/cs-cart-seo-optimization-canonical-url-cdseo-v4.html)

One-time license. The current price and the live demo are on the product page.

## Why store owners use it

- Keep discontinued products, categories, and pages from landing on a dead URL: set a 301 target when you disable the item.
- Override the default CS-Cart SEO path with a canonical you choose, per language.
- Emit JSON-LD that Google’s rich-results tools can read: company profile, product offers, sitelinks search box, and blog articles.
- Fill Open Graph and Twitter Card tags so product and article shares show a title, description, and image.
- Append the page number to category meta title, description, and keywords on paginated lists.
- Turn storefront 404s into a redirect to search, sitemap, promotions, or any CS-Cart dispatch you set.

## Canonical links and 301 redirects

On each product, category, and page you pick one mode:

- **Canonical link** — a path without the domain (for example `apparel/men/seo-link`). CDSEO uses it as the storefront canonical URL.
- **Redirect link** — a full URL. When that item is disabled, visitors get a 301 to the URL you entered.

The same fields exist for products, categories, and CMS pages, including blog pages.

## Store-wide 404 handling

- Set a destination for 404 traffic (default points at product search).
- Optionally send a **301** instead of a raw 404.

## JSON-LD structured data

- **Organization** on the storefront: name, logo, postal address, customer-service contact, phone, and `sameAs` for Facebook, X, and YouTube when those URLs are filled.
- **WebSite** + **SearchAction** on the homepage (Google’s sitelinks search-box pattern).
- **Article** on the homepage and category pages.
- **Product** extras on top of CS-Cart’s SEO markup: category name, brand, SKU/MPN from the product code, validated GTIN when the code is a real GTIN-8/12/13/14, and `priceValidUntil` on the offer (your date, or one year ahead if empty).
- **NewsArticle** for the built-in CS-Cart blog page type.
- **BlogPosting** when CS-Press blog posts are present.
- **BreadcrumbList** microdata on the Responsive breadcrumb template.

## Social sharing meta

- Open Graph: `og:type` (website / product / article), title, description, URL, site name, image, dimensions, MIME type, and `article:published_time` for articles.
- Twitter Card: `summary_large_image` when an image is available.
- If the share image is WebP, CDSEO prefers a matching JPG or PNG when one exists, so crawlers that mishandle WebP still get a raster image.

## Requirements

- CS-Cart or Multi-Vendor **4.12.1** or newer, including **4.21**
- PHP **8.3** or a current 8.x release used by that shop
- The built-in **SEO** add-on must stay enabled

## This repository

<p align="center">
  <a href="https://www.webgraphiq.com/cs-cart-seo-optimization-canonical-url-cdseo-v4.html">
    <img alt="Buy and view the live demo" src="https://img.shields.io/badge/CS--Cart-Buy%20%26%20View%20Live%20Demo-28a745?style=for-the-badge&labelColor=1A365D">
  </a>
</p>

<p align="center"><strong>One-time license · canonical links, JSON-LD, and social meta</strong></p>

This is the public product listing. The add-on package, license checks, and source files are not published here. After purchase, the package is readable PHP under the WebGraphiq commercial license, installed from your WebGraphiq account.

Support: [webgraphiq.com](https://www.webgraphiq.com) · webgraphiq@gmail.com

© WebGraphiq. All rights reserved. [License](https://www.webgraphiq.com/license.html)

## Other Premium CS-Cart Add-ons by WebGraphiq

More CS-Cart and Multi-Vendor add-ons are listed on the [WebGraphiq GitHub profile](https://github.com/webgraphiq).
