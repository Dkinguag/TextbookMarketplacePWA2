<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<h1 align="center">
  <img alt="Gatsby" src="resources/shopify+gatsby.png" height="60px" />
  <br/>
  The Larry U. Textbook Marketplace
</h1>

[![Netlify Status](https://api.netlify.com/api/v1/badges/d374a159-9ee3-4b02-91a3-ee3053990fcb/deploy-status)](https://app.netlify.com/sites/gatsby-shopify-starter/deploys)

Kick off your next eCommerce experience with this Gatsby starter. It is based on the default Gatsby starter to be easily modifiable. [Demo](https://gatsby-shopify-starter.netlify.com)

## Directory Structure

```shell
PROJECT/                        # → Root Directory
├── wp-content/                 #
│   ├── themes/                 #
│   │   └── wpnyc-genesis       # → Project Theme
│   └── plugins/                #
│       └── wpnyc-functions/# → Project Functionality
├── .gitignore                  # → WPE CLI Gitignore
└── composer.json               # → Installs 3rd Party Plugins
```

## 💎 Features

- Cart
- Product grid
- Product page
- Dynamic Inventory Checking
- Image optimization with Gatsby Image
- Styled Components with Emotion
- Google Analytics
- SEO

### 📦 Dynamic Inventory Checking

The Shopify product inventory is being checked in realtime, therefore no rebuilding and redeploy is needed when a product goes out of stock. This avoids problems where products could still be available even though they're out of stock due to redeploy delay.

### 🖌 Styling

I'm using [Emotion](https://emotion.sh/docs/introduction) as styled components library, but the starter is purposely only sparsely styled so you don't have to remove unecessary code but can instead add your own styling immediately.

## ⚠️ Common problems

- You need to use the Shopify Storefront API credentials not the regular Shopify API.
- You need to have at least one published product on Shopify.

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation for Gatsby lives [on the website](https://www.gatsbyjs.org/). Here are some places to start:

- **For most developers, we recommend starting with our [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.org/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to our documentation](https://www.gatsbyjs.org/docs/).** In particular, check out the _Guides_, _API Reference_, and _Advanced Tutorials_ sections in the sidebar.

## Deploy

Checkout my other open-source project [JAMStackBox](https://github.com/AlexanderProd/jam-stack-box) to continuously deploy your Gatsby site on your own server.

## 📌 ToDo

I'll happily merge any pull request to improve the starter. 🙂

- [x] Convert Layout to function component.
- [x] Add dynamic inventory checking to avoid re-building after every purchase.
- [x] Add better styling.
- [x] Add image optimization using Gatsby sharp plugin.
- [x] Convert ProductForm to function component.
  <!-- AUTO-GENERATED-CONTENT:END -->
