# ProductCard

The front face of a product flip box: product imagery, growth-stage label, product name, tagline and an outline "Learn More" pill.

**Consumer provides:** `div.vt-product` with two custom properties, `--product-accent` (one of the `product-*` colour tokens, used behind the imagery) and `--product-label` (the label colour); a `vt-product__media` element holding the product photo; and a `vt-product__body` with label, `h3.vt-product__name`, `p.vt-product__tag` and a `vt-btn--outline` link.

- `radius-8`, `shadow-float`, white ground. The live flip box is 675px tall (775px on mobile) and flips right over 1000ms to a back face listing three benefits.
- Product names are always written in full and title case: Root Ignite Bio, Soil Vitality Max, Hydro Balance Pro, Canopy Care Elite, Vigor Spray Max, Crop Aid Myco Spora 10x.
- The label is the growth stage the product serves ("Seed Germination & Early Root Development").
- Product accents mark a product, not a state. Don't use `product-root-ignite-bio` or `product-hydro-balance-pro` as text on white.

Use the product's bottle shot on white (`vt-product__media--photo`, as in the Vigor Spray Max card); the coloured band (Soil Vitality Max card) is the fallback until a product has a photo.
