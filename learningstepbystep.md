# sections?

cleared this concept

# snippets?

are resuable components, i.e we keep reusable part of code in snippets directory.

# templates

A template in Shopify is a starting point or blueprint for rendering a specific type of page on your storefront — like a product page, collection page, cart, or home page.

# ❓ So, what is a template really?

A template in Shopify (whether .liquid or .json) is a file that defines how a specific type of page should look and behave.

# ❓ When should I use .json and when .liquid?

Situation Use
You want to customize page with drag-and-drop sections in Shopify theme editor ✅ .json
You want custom logic using Liquid (e.g., if, for, etc.) ✅ .liquid
You want to mix both → create a .json and refer to custom sections ✅ Best practice

✅ When to create a new template?
Create a new template if:

You need a different layout for certain products/pages.

Example: /templates/product.custom.json

Then assign this to specific products in Shopify admin.

You want to control the page with drag-and-drop sections → use .json.

You want logic-heavy layout → use .liquid.

# usman here
✅ Summary: 

Folder Purpose
/templates Entry point for different page types (product, index, cart, etc.)
/sections Layout sections used in templates
/snippets Reusable UI parts (like buttons, price, etc.)
