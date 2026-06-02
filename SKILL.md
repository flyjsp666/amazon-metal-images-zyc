---
name: amazon-metal-images-zyc
description: Create a seven-image Amazon US listing image set for custom iron art and metal decor products. Use for Amazon main images, lifestyle images, infographics, dimension images, drilling or hole images, color option images, customization images, and mounting option images. Requires three product reference images and a product title before use.
metadata:
  short-description: Amazon iron-art listing images
---

# amazon-metal-images-zyc

## Overview

Use this skill to produce a complete seven-image Amazon US image set or generation prompts for custom iron art and metal-cut decor products. Default every image to square 1600 x 1600 px JPG-style output, with one compliant white-background main image and six secondary images based on the user's deep prompt structure.

Do not proceed until the user has provided all required inputs:

1. One clear base product image.
2. One real product image showing the drilled-hole version.
3. One real product image showing the top-hanging-ring version.
4. The product title.

If the user invokes this skill without all three required images and the product title, stop and ask them to provide the missing image(s) and/or title first. Do not create concept drafts, storyboards, prompts, or final images until all four inputs are present.

When the required product reference photos are available, default to generating the actual seven image files with the available image-generation workflow/tool. Only return a planning table or prompts without generating images when the user explicitly asks for a plan, storyboard, copy, or prompts only.

For a Chinese-language version of this workflow, read [references/amazon-listing-image-pack.zh-CN.md](references/amazon-listing-image-pack.zh-CN.md).

For iron-art-specific deep prompt rules extracted from the user's workbook, read [references/iron-art-deep-prompts.zh-CN.md](references/iron-art-deep-prompts.zh-CN.md).

## Required Output Set

Create exactly seven images unless the user asks otherwise:

1. Main image: product only, pure white background, front view, no holes unless holes are present in the uploaded product design.
2. Drilling/hardware image: show pre-drilled mounting holes and included hardware kit in English. For round signs, show the full product large in the center with two enlarged magnifier close-ups of the left and right side holes on the outer circular rim. Use clear callouts such as "Easy to Hang", "Pre-Drilled Mounting Holes", and "Included Mounting Hardware Kit (Screws & Wall Anchors)". Include a bottom feature band for "Weather-Resistant Powder-Coated Finish", "14 Gauge Steel", and "201 Stainless Steel [Outdoor]" when those claims match the product. Do not place holes at the top, bottom, center, or inside the decorative artwork unless the uploaded product or user marks require it.
3. Color options image: 2 x 3 grid for Black, White, Gold, Silver, Blue, and Red powder-coating options unless the user provides different colors. If the user uploads a color swatch/photo, use it as the visual reference for powder-coated color tone, surface grain, sheen, and finish texture. The final color options image should still show the actual product repeated in six colors, not only color swatches, unless the user explicitly asks for a swatch-only chart. Use a clean title such as "Colors Available - Powder Coating" and color labels under each product: BLACK, WHITE, GOLD, SILVER, BLUE, RED. Add a bottom line such as "Powder Coated - Water and Moisture Resistant" when accurate.
4. Custom text/info image: show where custom text can be placed; label each marked area as "Custom Text 1", "Custom Text 2", etc.
5. Dimension image: split layout with the full product on the left and size/material table on the right. For round products, the size table must show these exact diameter options with inch and centimeter values: 12 in / 30.5 cm, 15 in / 38.1 cm, 20 in / 50.8 cm, 24 in / 61.0 cm, 28 in / 71.1 cm, 32 in / 81.3 cm, and 36 in / 91.4 cm.
6. Lifestyle with person: realistic US middle-class home scene with the product displayed on a wall, product about one fifth of the full image, a person naturally smiling at or admiring it. When the product appears on a wall in any lifestyle scene, the product itself must be clean and must not show screws, screw heads, drilled holes, hanging rings, chains, hooks, tabs, or visible mounting hardware.
7. Two mounting options image: left side wall-mounted, right side top-hanging with black metal chains; include concise English mounting and durability callouts. For round signs, wall-mounted screw holes must be drilled inside the product's own outer circular metal ring on the left and right sides, around the 9 o'clock and 3 o'clock positions; the holes must stay within the width of the existing outer ring and must not protrude outside the product outline. Top-hanging versions must add exactly two small round hanging rings outside the product body, positioned symmetrically at the upper left and upper right edge of the circular outer frame, around the 10 o'clock and 2 o'clock positions. Each ring is a simple circular metal loop attached externally to the outside edge of the product frame, and black metal chains must pass through these two rings only. Do not use a single top center ring, flat tabs, ears, hooks, clamps, brackets, random holes, or chains attached directly through the decorative artwork.

For the user's common iron-art product categories, choose scenes that fit:

- Iron decor: entryway, porch, living room wall, garden wall, workshop, family-name sign, holiday/gift context.
- Wall art/decorative painting: living room, bedroom, office, hallway, dining room, scale above sofa or console.

## Iron Art Product Rules

Apply these rules to every image unless the uploaded product photo contradicts them:

- Preserve the uploaded product design, outline, cutouts, text, and proportions exactly; do not stretch, compress, redraw, simplify, or deform the product.
- Present the product as a sturdy iron/metal-cut item with black matte powder-coated texture by default.
- Show subtle matte grain, black metal sheen, crisp laser-cut edges, slight bevels, and visible metal thickness.
- Use lighting that makes the metal readable: right-upper key light, soft side fill, subtle shadows, and small highlights on cut edges.
- Do not add screw holes, chains, hooks, text, icons, or accessories unless that image role requires them or the user marks their positions.
- For lifestyle scenes where the product is displayed on a wall, never add screws, screw heads, drilled holes, hanging rings, chains, hooks, tabs, brackets, or visible mounting hardware on the product. The wall-mounted lifestyle image should show the clean product face only; installation details belong only in the drilling/hardware image or the two mounting options image.
- When the product is a round sign and the image role requires mounting details, place wall-mount screw holes only inside the product's own left and right outer circular metal ring unless the user marks different positions; the holes must not protrude outside the product outline. For chain-hanging versions, add exactly two small round hanging rings outside the product body at the upper left and upper right edge of the circular outer frame, around the 10 o'clock and 2 o'clock positions. Route chains through these two external rings only; do not use flat tabs, ears, a single top center ring, or chains through the decorative cutout design.
- For drilling/hardware images, prefer a large centered product composition with magnifier-style close-up circles over the side holes, a small hardware kit icon/illustration for screws and wall anchors, and concise English text. Do not show chains in the drilling/hardware image unless the user explicitly asks.
- For color options images, preserve the exact product outline, text layout, cutouts, and proportions across all six variants. Change only the powder-coat finish color and match any uploaded color swatch/photo for color tone and texture. Keep the layout as two rows of three products on a light warm neutral background, with clear English color labels and no extra variants.
- For dimension images of round products, always label the measurement as diameter and list the exact sizes in both inches and centimeters: 12 in / 30.5 cm, 15 in / 38.1 cm, 20 in / 50.8 cm, 24 in / 61.0 cm, 28 in / 71.1 cm, 32 in / 81.3 cm, and 36 in / 91.4 cm. Do not replace these with generic size rows or "best for" rows unless the user explicitly provides a different size set.
- Keep all infographic text in English for Amazon US. Do not include Chinese text in generated images.
- Use only claims that fit the user's product: "Powder Coated", "Waterproof & Moisture-Proof", "Easy to Hang", "Screw Kit Included", "Personalized Metal Sign", "Choose Your Size", and similar concise claims.
- If the user marks holes or custom text areas with red circles/boxes, convert those marks into polished arrows, zoom callouts, labels, or clean highlight rings in the final concept. Do not leave rough annotation marks unless the user asks.
- Avoid copyrighted text, logos, protected designs, or brand-like graphics not provided by the user.

## Amazon US Compliance Rules

Read [references/amazon-image-rules.md](references/amazon-image-rules.md) before finalizing compliance-sensitive work. Apply these essentials every time:

- Use square 1:1 images at 1600 x 1600 px unless the user specifies a different Amazon-valid size.
- Use JPEG, PNG, TIFF, or GIF-compatible output; avoid animated GIFs.
- Keep images sharp, professionally lit, and true to the product being sold.
- Main image must use a pure white background, RGB 255/255/255.
- Main image must show only the product included in the purchase; no lifestyle props, people, inset images, badges, watermarks, borders, logos, or promotional text.
- Main image should fill at least 85% of the frame while keeping the entire product visible.
- Do not include misleading scale, accessories, packaging, extra props, or variants unless they are included in the purchase.
- Do not add Amazon badges, star ratings, review counts, "Best Seller", "Amazon's Choice", discounts, coupons, competitor claims, or guarantees that the seller has not documented.
- Do not show prohibited, offensive, sexually suggestive, unsafe, or regulated-use content.
- Use English text for US listing infographics unless the user explicitly needs bilingual assets.
- Treat category-specific rules as stricter than this general checklist. If the product is apparel, jewelry, baby, medical, food, or another sensitive category, verify current category rules before final output.

## Workflow

1. Verify required inputs:
   - Confirm the user uploaded the required three reference images: one clear base product image, one drilled-hole product image, and one top-hanging-ring product image.
   - Confirm the user provided the product title.
   - If any required image or the product title is missing, ask the user to provide the missing input(s) before continuing.
2. Gather product facts:
   - Product title, product type, material, dimensions, color/finish, customization method, included items, target buyer, occasion, style, and details visible in the reference photos.
   - For personalized products, ask or infer placeholder personalization such as "The Johnson Family" only when needed.
3. Define the seven-image storyboard:
   - Assign each image a goal, composition, background, text/callouts if allowed, and risk notes.
4. Write generation prompts:
   - Include product accuracy details, camera angle, lighting, composition, Amazon compliance constraints, and exact 1600 x 1600 output.
   - For main image prompts, explicitly say pure white background, product only, no text, no props, no watermark, no border.
5. Generate the images by default:
   - Use product reference images whenever accuracy matters.
   - For infographics, keep copy short and legible at mobile size.
   - Save or copy all generated image files to the user's Desktop under `C:\Users\bjenf\Desktop\zyc0531_generated_images`. If multiple batches are generated, create a clearly named subfolder inside that Desktop folder.
   - Do not stop at a storyboard or prompt table unless the user explicitly asks for planning-only output.
6. Validate each image before delivery:
   - Confirm 1600 x 1600 px, square crop, no edge clipping, readable text, no overlap, no policy-risk text, and correct role in the seven-image set.
   - Confirm the main image has pure white background and no secondary elements.

## Prompt Pattern

Use this structure for each image prompt:

```text
Create a 1600 x 1600 px square Amazon US listing image for [product].
Image role: [main/lifestyle/dimension/selling point/detail/use-case/package].
Product facts: [material, dimensions, color, customization, included items].
Composition: [camera angle, crop, background, scene, props if allowed].
Text/callouts: [none for main image; short English callouts for infographic images].
Compliance constraints: [Amazon-specific constraints for this role].
Style: realistic commercial product photography, sharp focus, clean lighting, accurate scale, no misleading elements.
```

## Delivery Format

Default delivery is generated image files. All files generated with this skill must be saved or copied to the user's Desktop under `C:\Users\bjenf\Desktop\zyc0531_generated_images` before delivery. If multiple batches are generated, create a clearly named subfolder inside that Desktop folder. After generating actual files, provide the Desktop folder path, the generated images, and a short checklist confirming:

- 7 total images
- Each image is 1600 x 1600 px
- Main image is white-background product-only
- One dimension image is included
- One selling-point image is included
- One detail image is included
- One lifestyle image includes a person

When the user explicitly asks for planning only, return a table with:

- Image number
- Image role
- Visual concept
- Text/callouts
- Generation prompt
- Compliance notes

