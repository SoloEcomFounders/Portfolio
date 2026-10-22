# SPNutrition magnesium page: Shopify theme files

Three files to add to a theme (Online Store > Themes > ••• > Edit code):

| File | Add it under |
|---|---|
| `layout/spn-landing.liquid` | Layout > Add a new layout > liquid, name `spn-landing` |
| `sections/spn-magnesium-page.liquid` | Sections > Add a new section > liquid, name `spn-magnesium-page` |
| `templates/product.spn-magnesium.json` | Templates > Add a new template > product, JSON, name `spn-magnesium` |

Paste each file's contents over the starter code and save.

Then open the product in Shopify admin, set **Theme template** to `spn-magnesium`, and preview.

- Bundle cards come from the product's variants, highest price first. Variant titles like "Buy 3 Bags" set the supply length (3 × 30 days) and guarantee days. The highest-priced variant gets the "Best value" badge and perks.
- Add to cart posts to the store's real cart.
- The custom layout drops the theme's own header and footer so the page shows its own.
- Images load from the SPNutrition Shopify CDN. Text for the announcement bar, heading and best-value perks can be edited in the theme customizer.
